# Web Scraping

For web-scraped data, you should have at least started your attempt to scrape the data. The full collection of the data isn’t due until the next Deliverable (Organize). However, you still need to describe the data fully as you would any other dataset. 

Scraping data from a web page can get complicated due to the dynamic nature of web pages. The request API to download the HTML may not work out of the gate because the data is asynchronously loaded into the page. You should at least know if you can easily capture the data in a file. You might be able to alter the URL you download to get the data, but that can get difficult if the pages do a POST request instead of a GET. (HTTP protocol includes a “post” action where there are potentially many parameters included in the “headers” of the request.) 

You may have to manually save the HTML to a local file and then update your code to read the local file. If there are many pages to download, you may want to look into crawling a site programmatically through automation. This is wrought with potential failures and is not easy. 

In short, you cannot let web-scraping be a roadblock to your Data Science research! Find a solution early, even if it involves some manual work. Strive to understand the scope of the web scraping task; start scraping early. The more work you get done early, the better things will go for the rest of the project.  

:::{warning}
While using the internet to help you scrape a webpage is acceptable, you are still required to **cite** the specific source and **understand** the code in your project. To avoid uncomfortable interviews, add comments in your code that amply describe how it all works.  
:::
