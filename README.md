# Beautiful Soup (beautiful-soup)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
