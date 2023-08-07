# Web_Scrapping
![Web Scrapping](https://github.com/JOCRZ/Web_Scrapping/blob/main/web_scrapping.png?raw=true)

### About
 1. What is web Scrapping?
 - Web scraping is the process of automatically extracting data from websites.
 2. Why do we need to extract data from website?
  - We need data for research, analysis, making informed decisions, or creating useful applications. 
3. Why do we use Scrapping?
 - Web scraping enables you to collect data from multiple sources quickly and efficiently, eliminating the need for manual copying and pasting. With the use of web scrapping tools we can extract the information that we wanted rather than extracing everything from the webpage and when data is presented in a clear and organized manner, it's easier to analyze, make comparisons, and draw insights. 

### Basic Tools/Library used:
- BeautifulSoup - HTML parsing library
- Requests -	HTTP library for making web requests
- Scrapy	- Web scraping framework
- Selenium	- Browser automation and testing

### The Difference:

| Feature | BeautifulSoup | Requests | Scrapy | Selenium |
|:--- |:--- |:--- |:--- |:--- |
| Description | HTML parsing library | HTTP library for making web requests | Web scraping framework | Browser automation and testing |
| Usage | Parse HTML/XML documents | Make HTTP requests and handle responses | Crawl and scrape web pages | Automate browser interactions |
| Interaction Level | Parse static content only | No interaction with JavaScript or dynamic content | Full web page interaction | Full web page interaction |
| Pros | Lightweight, simple syntax | Simplicity and ease of use | Highly customizable, large-scale scraping | Full browser emulation |
| Cons | Limited to static content | Limited interaction with dynamic content | Learning curve for complex scraping tasks | Slower compared to non-browser scraping |
| Asynchronous | No | No | Yes, built-in asynchronous capabilities | No (unless combined with async lib) |
| AJAX Support | No | No | Yes, built-in AJAX support | Yes |
| JavaScript | No (only static content) | No | Can handle JavaScript-rendered content | Yes |
| Pagination | Manual handling required | Manual handling required | Built-in pagination support | Manual handling required |
| Form Submission | No | Yes | Yes | Yes |
| Scalability | Suitable for small-scale scraping | Suitable for simple HTTP requests | Suitable for large-scale projects | Suitable for complex web apps |
| Learning Curve | Easy | Easy | Moderate to advanced | Moderate to advanced |
