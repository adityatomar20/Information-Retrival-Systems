### Web Crawler:

The first code snippet is a simple web crawler implemented in Python. It utilizes the HTMLParser module to parse HTML content and extract hyperlinks (<a> tags) from a given web page. The LinkParser class extends the HTMLParser and defines methods to handle the start tags of HTML elements. The spider function initiates a web crawling process, visiting pages, and searching for a specified word within the page content. The crawler continues until either the word is found, the maximum number of pages is reached, or there are no more pages to visit.

### Web Scraper:

The second code snippet is a web scraper designed to extract information from a webpage. It uses the requests library to fetch the HTML content of a specified URL and then utilizes BeautifulSoup to parse and navigate the HTML structure. In this specific example, the scraper is configured to extract movie data from IMDb's search results page for movies released in 2018. The script retrieves information such as movie names, release years, IMDb ratings, and Metascores (if available). The extracted data is then organized into a Pandas DataFrame for further analysis or storage.

### Description:

These Python scripts showcase two fundamental techniques for interacting with web content. The web crawler demonstrates the process of systematically exploring web pages by following hyperlinks, while the web scraper focuses on extracting specific data from the HTML structure of a webpage. Both scripts are essential tools for web data extraction and can be adapted for various applications, including data analysis, content indexing, or monitoring changes on websites. Additionally, the use of libraries such as HTMLParser, requests, and BeautifulSoup underscores the convenience and flexibility of Python for web-related tasks.
