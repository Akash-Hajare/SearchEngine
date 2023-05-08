# Search Engine

# Introduction
  - Search Engine project will able to provide users required information they are looking for online using keywords.
  - Introducing the three stages of Search Engine project

        1: Web Crawling
        2: Indexing 
        3: Serving search results
   
 # Web Crawling
 - Web crawling is the process of systematically scanning and collecting data from websites on the internet. The process involves using web crawlers, to navigate through websites, following links and collecting data along the way.
 - Web crawlers are automated programs that visit websites and extract information such as text, images, and links. They start by visiting a seed URL, which is typically a homepage or a list of URLs, and then follow links to other pages on the website. As they crawl through the website, they collect data from each page and store it in a databas.
 - Web crawler is an essential component of search engine technology, as it enables search engines to build an index of the web's content. By crawling web pages and collecting data, search engines can create a database of all the words and phrases contained in web pages. This index allows search engines to quickly retrieve relevant information when a user enters a search query.
 - https://github.com/Akash-Hajare/WebCrawler
 
 # Indexing
 - Indexing in search engine technology refers to the process of analyzing and organizing data collected from web pages during the web crawling process. The data collected during web crawling is typically in the form of text, images, and other multimedia elements.
 - Using Jsoup which is a Java library that provides a convenient way to parse HTML documents and extract data from them. Jsoup is a java html parser. It is a java library that is used to parse HTML document. Jsoup provides api to extract and manipulate data from URL or HTML file.  It allows developers to quickly and easily extract information such as text, links, and images from HTML documents.
 - Jsopu extract hyperlinks from html document. It stores title and hyperlink into database.

# Serving search results
- When a user enters a query or keywords, the search engine retrieve and present a list of relevant 30 results in table having name (title) and hyperlinks in response to the query.
- It also stores users search query or keywords in history table. So that user can easily find history of keywords which they search in past.

# Tech stack used 
- Java Servlet : Used to handle the request obtained from the webserver, process the request, produce the response, then send a response back to the webserver. 
- Maven : Maven is a build automation tool and a project management tool used primarily for Java-based projects. It provides a way to manage project dependencies, build and package projects, and generate reports on project status.
- MYSQL: Database to store web crawling results ie Title and hyperlink and also search results.
- Apache Tomcat 
- Html css

 
