# Building 

This site is built using myst. It is deployed as part of a subproject of it's parent site using jekyll on github pages.

It's possible to work and make changes on just the myst portion of the website by testing locally (you cannot run `myst start` as it will not host the image files correctly)

## Testing Changes Locally

### .vsode/launch.json

If you are working with this project as a submodule the easiest way to test is to add `external/cse163` to your workspace so you have a `multi vscode workspace`. Then you can simply select the build and debug configuration for `Myst: Build & Start server`.

### Command Line

Install myst command line tools if needed:

```bash
npm install -g mystmd
```

For images to load and be tested you will need to build and host locally from the _build/html folder as follows (assumes running in codespaces)

```bash
cd ${CODESPACE_VSCODE_FOLDER}/external/cse163
myst build --html
cd _build/html
python -m http.server 8000

```