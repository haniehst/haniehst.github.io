---
layout: portfolio_detail_large
order: 1
title:  Telegram Crawler
name: telegram-crawler
badge-description: A web application for crawling the telegram.
filter: filter-software
badge-image: badge.jpg
category: Software
client:
project-date: August 2021
project-url:
github-repository: 
full-description: This project is a web application
# images:
#     - 'cnn-overall.png'
#     - 'cnn-details.png'
#     - 'twitter-overall.png'

---
****NOTE: None of Exa's projects are open source. So, I am not allowed to share the code which I have developed in this project.**
#### Introduction
This project is developed for crawling public channels and groups
#### Components


**PostgreSQL**: This databased is used for storing crawled data from CNN and Twitter.

#### Data Crawling

1. ##### CNN Crawling
    The latest articles about PS5 is fetched from search section of CNN's website. Like many other modern websites, CNN pages are dynamic. It makes AJAX calls for receiving the latest search results. Hence, utilizing traditional parsers are not useful for crawling the search results.  
    
    Selenium can be utilized for automated crawling complex websites. it gives the user full control of the browser. For example, in crawling search results, the results will arrive after some time. So, the result elements are not available, and the user has to wait for the elements to be completely loaded. Selenium wait functions gives the user the ability to wait for some elements to load.
2. ##### Twitter Crawling
    Instead of using selenium, Twitter's Developer API is used for crawling data. Each time the latest 25 tweets containing the word PS5 are fetched from Twitter. Username, publish date, and text of the tweets are extracted from the results.

    Then, the body of tweet is analyzed by **Stanford Core NLP** for extracting the tweet's sentiment and labeling it in the GUI application. There are five possible values including, [VERY POSITIVE, POSITIVE, NEUTRAL, NEGATIVE, and VERY_NEGATIVE]. Tweet's sentiment is persisted with other fields extracted to the database.

#### Technologies/Languages Used

{: .table .table-striped}
| Technology | Usage |
|------------------|--------|
| <img src="{{'assets/img/portfolio/technologies/python.png' | relative_url}}" width="60" height="60"> | **Python** is the languages used for projects. |
| <img src="{{'assets/img/portfolio/technologies/typescript.png' | relative_url}}" width="60" height="60"> | **Typescript** is the main language used for developing Angular applications. |
| <img src="{{'assets/img/portfolio/technologies/spring-boot.png' | relative_url}}" width="60" height="60"> | **Spring Boot** framework is used for developing backend services for exposing REST endpoints and crawling CNN and Twitter |
| <img src="{{'assets/img/portfolio/technologies/spring.png' | relative_url}}" width="60" height="60"> | **Spring** frameworks, including Spring Cloud, Spring Security, Spring Data, etc. are used for developing backend services. |
| <img src="{{'assets/img/portfolio/technologies/core-nlp.png' | relative_url}}" width="120" height="60"> | **Stanford Core NLP** is used for extracting crawled tweets' sentiments in order to analyze people's oponion about PS5|
| <img src="{{'assets/img/portfolio/technologies/angular.png' | relative_url}}" width="60" height="60"> | **Angular** framework is used for developing GUI web applications. |
| <img src="{{'assets/img/portfolio/technologies/selenium.png' | relative_url}}" width="60" height="60"> | **SELENIUM** is an standalone browser for crawling CNN. |
| <img src="{{'assets/img/portfolio/technologies/docker.png' | relative_url}}" width="60" height="60"> | **Docker** is used for virtualization and containerizing services, including backend and frontend services. |
| <img src="{{'assets/img/portfolio/technologies/postgre.png' | relative_url}}" width="60" height="60"> | **PostgreSQL** databse is used for persisting news and tweets |
| <img src="{{'assets/img/portfolio/technologies/nginx.svg' | relative_url}}" width="110" height="60"> | **NGINX** web server is used for deploying angular application. |
| <img src="{{'assets/img/portfolio/technologies/git.png' | relative_url}}" width="60" height="60"> | **Git** is used for version control. |