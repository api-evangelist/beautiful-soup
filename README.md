# Beautiful Soup (beautiful-soup)
Beautiful Soup is a Python library for pulling data out of HTML and XML files, widely used for web scraping and screen scraping tasks. It provides a parse tree API with simple methods for navigating, searching, and modifying parsed HTML/XML documents. Beautiful Soup automatically handles encoding, supports multiple parsers (html.parser, lxml, html5lib), and integrates with CSS selectors via the Soup Sieve library. Current stable version is 4.14.3.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/beautiful-soup/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Data Extraction, HTML Parsing, Python, Scraping, Web Scraping, XML Parsing

## Timestamps

- **Created:** 2026-03-29
- **Modified:** 2026-04-19

## APIs

### Beautiful Soup
Beautiful Soup 4 is a Python library providing a parse tree API for HTML and XML documents. It exposes Tag, NavigableString, BeautifulSoup, and Comment objects with navigation methods (find, find_all, CSS selectors), tree traversal (parents, children, siblings), and modification methods (append, extract, replace). Supports html.parser, lxml, and html5lib parsers with automatic encoding detection.

**Human URL:** [https://www.crummy.com/software/BeautifulSoup/](https://www.crummy.com/software/BeautifulSoup/)

#### Tags:

 - Data Extraction, HTML Parsing, Python, Scraping, Web Scraping, XML Parsing

#### Properties

- [Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [GettingStarted](https://www.crummy.com/software/BeautifulSoup/bs4/doc/#quick-start)
- [SDK - Python Package (PyPI)](https://pypi.org/project/beautifulsoup4/)

## Common Properties

- [Website](https://www.crummy.com/software/BeautifulSoup/)
- [Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [SDK - PyPI Package](https://pypi.org/project/beautifulsoup4/)
- [Changelog](https://bazaar.launchpad.net/~leonardr/beautifulsoup/bs4/view/head:/CHANGELOG)

## Features

| Name | Description |
|------|-------------|
| Multi-Parser Support | Supports html.parser (built-in), lxml (fast), and html5lib (browser-like) parsers for flexible HTML/XML parsing. |
| CSS Selector Support | Full CSS4 selector support via the Soup Sieve library for familiar CSS-based element selection. |
| Tree Navigation API | Rich API for navigating the parse tree upward, downward, and sideways including find(), find_all(), parents, children, and siblings. |
| Automatic Encoding Detection | Automatically detects and handles document encoding using Unicode, Dammit, ensuring correct text extraction. |
| Tree Modification | Full tree modification support including append, insert, extract, decompose, replace_with, wrap, and unwrap operations. |
| Output Formatting | Multiple output formatters including prettify(), get_text(), and custom formatters for controlled serialization. |

## Use Cases

| Name | Description |
|------|-------------|
| Web Scraping | Extract data from websites by parsing HTML pages with Beautiful Soup and navigating the DOM tree to find target elements. |
| Data Mining | Mine structured data from HTML tables, lists, and other markup patterns across large numbers of web pages. |
| Content Extraction | Extract article text, product information, or other content from web pages for NLP pipelines and data analysis. |
| Screen Scraping Legacy Systems | Automate data extraction from legacy HTML web interfaces that lack modern APIs. |
| HTML Sanitization | Parse and clean HTML documents by removing unwanted tags, scripts, and formatting. |
| XML Processing | Parse and query XML documents using Beautiful Soup's tree navigation and search capabilities. |

## Integrations

| Name | Description |
|------|-------------|
| Requests | Python HTTP library used in combination with Beautiful Soup to fetch and parse web pages. |
| Scrapy | Python web crawling framework that can use Beautiful Soup selectors for content extraction. |
| lxml | Fast XML and HTML parsing library used as an alternate parser backend for Beautiful Soup. |
| html5lib | Pure-Python HTML5 parser used with Beautiful Soup for browser-compatible HTML parsing. |
| Pandas | DataFrame library commonly used with Beautiful Soup to convert scraped HTML tables into structured data. |
| Selenium | Browser automation tool used with Beautiful Soup to scrape JavaScript-rendered pages. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
