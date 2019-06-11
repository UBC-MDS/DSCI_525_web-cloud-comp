# DSCI 525: Web and Cloud Computing

How to use the web as a platform for data collection, computation, and publishing. Accessing data via scraping and APIs. Using the cloud for tasks that are beyond the capability of your local computing resources.

## Teaching Team

| Position | Name  | Slack Handle | GHE Handle | Office hour
| :------: | :---: | :----------: | :--------: | :--------: |
| Lecturer | Mike Feeley | `@mike.feeley` |  | MoWeThFr 2-3 (ICCS 393)
| Lab Instructor | Rodolfo Lourenzutti | `@lourenzutti` | `@lourenzu` | N/A
| Teaching Assistant | Aaron Berk | `@aberk` | `@aberk` | Thursdays 3:30pm~4:30pm (ESB 1045) |
| Teaching Assistant | Hayley | `@hayley` |  | Wednesday 1:00pm~2:00pm (ESB 1045) |
| Teaching Assistant | Julian Ho | `@julian` | | Fridays 10:00am~11:00am (ESB 1045) |
| Teaching Assistant | Minzhi Liao | `@Minzhi Liao` |  | Thursdays 12:30~1:30pm (ESB 1045) |

## Lectures

| # | Date | Topic
|---|-------------|-------------
| 1 | 2019-03-19 | Web scraping; tools in Python and R (scrapy, BeautifulSoup, rvest, Pandas read_html)
| 2 | 2019-03-21 | APIs, JSON
| 3 | 2019-03-26 | How the Internet works (short version): what happens when you go a website; notion of a protocol and protocol stack; distributed computing
| 4 | 2019-03-28 | Demystifying all those words: web tools, standards, and terminology (HTML, CSS, PHP, Ruby on Rails, django, JavaScript, HTTP, IP address, TCP/IP, DNS, Apache, listening on a port ...)
| 5 | 2019-04-02 | Cloud computing, benefits of cloud computing, effects on the industry (lower barrier to entry for startups, etc.); pricing, use cases, challenges 
| 6 | 2019-04-04 | Review of MapReduce, distributed scalable databases stored in the cloud
| 7 | 2019-04-09 | distributed hash tables, NoSQL databases, comparison with relational databases 
| 8 | 2019-04-11 | Moore's law, parallel computing, "Big Data"; which algorithms can be parallelized; how do we write code for parallel computing

Time: 11:00am - 12:30pm

## Labs

| Lab  | Lab topic   | Due Date |
|------|-------------|-----------|
| 1 | Lectures 1 & 2 | 2019-03-23 |
| 2 | Lectures 3 & 4 | 2019-03-30 |
| 3 | Lectures 5 & 6 | 2019-03-06 |
| 4 | Lectures 7 & 8 | 2019-03-13 |

## Quizzes
|     | Time | Date | Location |
|-----|------|------|----------|
| 1 | 13:30 - 14:00 | 2019-04-04 | Your lab session |
| 2 | 10:00 - 10:30 | 2019-04-17 | DPM 301 |

## Course Learning Outcomes
By the end of the course, students are expected to be able to:

1. Scrape data from websites and access data using application programming interfaces (APIs) where available.
2. Author web content for public access.
3. Host a simple application on a cloud computing platform such as Amazon’s EC2. 
4. Connect the concepts in databases to those of distributed computing
5. Parallelize computations in an environment such as ipyparallel. 


## Lecture Learning Goals

Read as "The student should be able to ..."

1. The web as a datasource, understanding the structure of web-fronted data and to collect it.
    - Compare and contrast HTML and XML.
    - Identify the HTML tags that are used to structure data on a web page and describe how they do this.  
    - Be able to explain, given an example HTML document, how the Javascript, hyperlinks and forms found there are used to interact with a web server and how this interaction results in changes to the web page or replacement of it with a new page.
    - Explain the difference between static and dynamic web data and how these concepts relate to the the first three learning goals and how they impact web scraping.
    - Explain what a web scraper is, why it is useful and how it works.
2. Datasources on the web: APIs, what they are, how to use them and how they structure data
    * Describe the role of and the tradeoffs between XML and JSON in formatting data obtained from web scraping.
    * Describe key benefits and limitations of web scraping.
    * Explain why some web services might provide alternative mechanisms through an API for accessing data they possess and why some don’t (e.g., banks).  And describe the benefits and limitations of API’s compared to web scraping.
    * Be able to use a common web API (e.g., yahoo, twitter, etc.) to collect data and analyze it in an interesting way.
    * Compare this approach and the results achieved to what could have been achieved using web-scraping alone.
3. The internet, the web, and distributed computing in a nutshell
    * Explain and distinguish the roles of Internet domain names, IP addresses, port numbers, communication hardware, network protocols, end-point computers, routers, internet service providers, operating system, servers and applications in the operation of the Internet.
    * Describe the difference between the “Web” and the “Internet” and explain and distinguish the roles of URLs, browsers, web servers, and web applications in the operation of the Web.
    * Describe the key points in the history of the development of the Internet, the Web and Internet-based services.
    * At an introductory level, explain and describe key tradeoffs among the following alternatives for structuring network-based applications and services: local, client-server, peer-to-peer, server-side web computation, client-side web computation, and the cloud.
    * Explain the term “distributed computing” by describing defining characteristics and key benefits.
4. Overview to protocols, languages, frameworks and other components of web-based computation
    * Briefly explain each of the following and their role in the Web: HTTP, HTTPS, socket, SSL, HTML, XML, JSON, URL, DNS, ISP, TCP, IP, CSS, Javascript, AJAX, JQuery, Apache, Nodejs, IIS, PHP, ASP, JSP, GWT, Ruby on Rails, Python, Django, Express, Pug, Berkeley DB, SQLite, MySQL, MongoDB, Spark.
    * Describe the difference between a protocol, an application, a server, a framework, a service, a language, a database, a file system, client-side tools and server-side tools, and give examples from the list above.
    * Given a set of web components from the list above draw a directed graph showing the flow of data and control among them for basic web user operations such as entering a URL in a browser, clicking on a hyperlink, hitting a submit button, and using an interactive Web application such as Facebook or Google Docs.
5. The cloud, what it is and how it changes things
    * Place the development of the cloud in an historical context by comparing it to similar and contrasting ideas from the past, by describing how and why it emerged, and by describing the problems it is designed to solve.
    * Explain the role that each of the following play in providing infrastructure for the cloud: commodity computing components, load-balancing, virtual machines, encryption, hardware failure, data centres, air conditioning, electrical power, service-level agreements, ISPs, data replication, tertiary storage.
    * For each of the following concerns, describe the concern in the context of the cloud and describe how the cloud addresses the concern, how it makes things better, how it might make things worse, and what hardware and software techniques are used to address the concern: availability, durability, scalability, consistency (in the face of replication), and also briefly indicate the impact on privacy and security (coverend in more detail in DSCI 541).
    * Intelligently discuss the social, political and environmental impact of cloud computing by giving specific benefits and concerns in each of these areas.
   * Explain key alternate business models for who pays for the cloud, compare costs to non-cloud alternatives, and examine the benefits and potential drawbacks of advertising-based models relative to user privacy.
6. Storing data at scale in the cloud: challenges and approaches
   * Describe the challenges of storing, querying and updating data at scale, and identify key characteristics that are required to perform these operations well. 
   * Describe how satisfying scalability and availability goals places constraints on data placement, what these constraints are, and how they complicate data access and management.
   * Using examples of simple operations on a data collection (maybe examples from census data) and comparing iteration to operations like map/reduce, provide insight into which of these techniques is most appropriate for accessing a large, distributed data collection.
   * Design and deploy an small program that uses map/reduce-like operations to access a large, distributed collection.
7. Distributed hash tables and NoSQL databases
   * Describe the operation, implementation, benefits and limitations of distributed hash tables as a way to structure large-scale data and give examples of publicly available distributed hash table (DHT) services and also publicly available services that depend on DHTs.
   * Identify the key differences between peer-to-peer and cloud-based DHTs and give examples of each. 
   * Identify specific features of the relational model that are difficult to provide at cloud scale and explain why, at an introductory level.
   * Explain what a NoSQL database is, how it is similar to and different from both (a) relational databases and (b) distributed hash tables.
   * Use a NoSQL database to store and access a (potentially) large, and interestingly complex data collection.  Perform complex queries on this data.  
   * Identify queries that would be interesting to perform that could be performed on a relational database but that can not be performed on a NoSQL database and explain the benefit that NoSQL databases achieve from these limitations.
8. Big Data and Parallel computation in the cloud
   * Compare and contrast: sequential, concurrent, parallel, and distributed computation.  
   * Describe the benefits of parallel computation and the limitations.
   * Describe the tradeoffs between shared-memory and non-shared memory parallel programs. 
   * Explain the term “speedup” and the factors that can limit speedup.
   * Explain the term “Big Data” and the ways in which it can benefit from scalable-data and parallel-computation services provided by the cloud.
   * Write a simple, massively parallel application and deploy it in the cloud.

##  Resources
* Docker
  * http://ropenscilabs.github.io/r-docker-tutorial/
  * https://www.linux.com/news/4-tutorials-using-docker-tools-run-truly-distributed-application-production
* EC2
  * http://angus.readthedocs.io/en/2015/amazon/index.html
* EC2 with Docker
  * http://angus.readthedocs.io/en/2015/week3/CTB_docker.html 
* [What happens when...](https://github.com/alex/what-happens-when)
