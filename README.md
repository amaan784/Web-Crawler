The notebook is divided into 2 parts.

# Web Crawler
 
This was one of the interview questions I was asked.
"code a simple web crawler that takes the web url as input and outputs all the links reacheable from that url"

Example-
	amazon.com
      amazon.com/product/1
         amazon.com/product/1/description
      amazon.com/product/2
         amazon.com/product/1/description

# Web Crawler vs Web Scraper-

A Web Crawler will generally go through every single page on a website, rather than a subset of pages. 
On the other hand, Web Scraping focuses on a specific set of data on a website. 
These could be product details, stock prices, sports data or any other data sets.

Web crawling and web scraping are two different but related concepts.
Web crawling is a component of web scraping, the crawler logic finds URLs to be processed by the scraper code.
A web crawler starts with a list of URLs to visit, called the seed. For each URL, the crawler finds links in the HTML, filters those links based on some criteria and adds the new links to a queue. 
All the HTML or some specific information is extracted to be processed by a different pipeline.

#### Sources-

- https://pythonprogramminglanguage.com/get-links-from-webpage/

- https://www.codecademy.com/resources/docs/python/requests-methods

- https://appdividend.com/2021/02/06/python-urllib-request-urlopen-function-with-example/
