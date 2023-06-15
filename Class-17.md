# Class 17
1. Key differences between scraping static and dynamic websites:

- Static Websites: Static websites are composed of HTML and CSS files that are pre-rendered and served as-is to users. Scraping static websites involves fetching the HTML content from a URL and parsing it to extract the desired data. The data extraction process is relatively straightforward as the content remains unchanged.

- Dynamic Websites: Dynamic websites use client-side rendering and often rely on JavaScript to load and update content dynamically. Scraping dynamic websites requires executing JavaScript code to retrieve the complete content before extracting data. This may involve using headless browsers or tools that can execute JavaScript to access and scrape the dynamically generated content.

2. Techniques to avoid getting blocked while scraping websites:

- Respect robots.txt: Check the website's robots.txt file, which specifies crawling rules. Adhere to the rules mentioned to avoid scraping restricted pages or overwhelming the server.

- Use delay and rate limiting: Add delays between requests to simulate human-like behavior and avoid sending an excessive number of requests in a short period. Respect the website's terms of service and consider implementing rate limiting to control the frequency of your requests.

- Rotate User Agents and IP addresses: Vary the user agent headers of your requests to mimic different browsers or devices. Additionally, consider using rotating IP addresses or proxies to avoid IP-based blocking.

3. Playwright and its benefits in web scraping:

- Playwright is an open-source automation library that allows developers to automate web interactions, including scraping, testing, and UI automation tasks. It provides a high-level API to control web browsers like Chrome, Firefox, and Safari.

- Playwright is particularly beneficial for web scraping tasks because it supports headless execution, handles JavaScript rendering, and provides powerful capabilities for interacting with modern web applications. It enables actions like form filling, clicking, scrolling, and capturing screenshots.

- Use case: Let's say you need to scrape a website that heavily relies on JavaScript to load and display data. Using Playwright, you can automate the interaction with the website, wait for the content to be fully loaded, and extract the required data. Playwright's support for headless browsing and JavaScript execution makes it a suitable choice for scraping dynamic websites.

4. Purpose of using XPath in web scraping:

- XPath (XML Path Language) is a query language used to navigate XML documents or HTML structures. In web scraping, XPath is commonly used to locate specific elements within an HTML document for extraction.

- XPath expressions allow you to select elements based on their tag names, attributes, or hierarchical relationships. It provides a powerful way to traverse and query the structure of an HTML document.

Example XPath expression to select a specific HTML element:
Suppose we want to select all `<a>` elements with a class attribute equal to "link" within a `<div>` with an id attribute of "container". The XPath expression would be:
```xpath
//div[@id="container"]//a[@class="link"]
```
This XPath expression starts with `//div[@id="container"]`, which selects the `<div>` element with the specified id. Then, it uses `//a[@class="link"]` to select all `<a>` elements with the given class attribute within that `<div>`.