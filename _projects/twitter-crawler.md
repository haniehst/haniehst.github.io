---
layout: portfolio_detail_large
order: 3
title:  Twitter Crawler
name: twitter-crawler
badge-description: Crawling public users' twitter timeline.
filter: filter-software
badge-image: badge1.jpg
category: Software
client:
project-date: December 2020
project-url:
github-repository: 
full-description: This project crawls twitter's timeline and produces crawled data into kafka topic.

---
#### Introduction
This project is developed for crawling public users' timeline with two different approaches:
* Scrapy
* Selenium + Beautiful soup  
then the crawled data is writen into a file in json format. The kafka producer then reads the file and produce its data into 'raw-tweets' topic.

#### Technologies/Languages Used

{: .table .table-striped}
| Technology | Usage |
|------------------|--------|
| <img src="{{'assets/img/portfolio/technologies/python.png' | relative_url}}" width="60" height="60"> | **Python** is the languages used for projects. |
| <img src="{{'assets/img/portfolio/technologies/scrapy.png' | relative_url}}" width="60" height="60"> | **SCRAPY** is a standalone browser. |
| <img src="{{'assets/img/portfolio/technologies/selenium.png' | relative_url}}" width="60" height="60"> | **SELENIUM** is a standalone browser. |
| <img src="{{'assets/img/portfolio/technologies/bs.jpg' | relative_url}}" width="60" height="60"> | **BEAUTIFUL SOUP** is a standalone browser. |
| <img src="{{'assets/img/portfolio/technologies/docker.png' | relative_url}}" width="60" height="60"> | **Docker** is used for virtualization and containerizing services, including backend and frontend services. |
| <img src="{{'assets/img/portfolio/technologies/kafka.png' | relative_url}}" width="60" height="60"> | **Kafka** Kafka is used to produce data |
| <img src="{{'assets/img/portfolio/technologies/git.png' | relative_url}}" width="60" height="60"> | **Git** is used for version control. |