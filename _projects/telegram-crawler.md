---
layout: portfolio_detail_large
order: 2
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

---
**NOTE: None of Exa's projects are open source. So, I am not allowed to share the code which I have developed in this project.**
#### Introduction
This project is developed for crawling data from public channels and groups. Collected data is later being analyzed to be accessible by our users. 


#### Data Crawling

All posts and messages from telegram public channels and groups are collected on daily basis. For groups, participants are also extracted.
With the help of NLP modules, data is analyzed and visualized, then users can have access to the analysis through a UI platform. They can also search the keywords and get the related news and data.

   
#### Technologies/Languages Used

{: .table .table-striped}
| Technology | Usage |
|------------------|--------|
| <img src="{{'assets/img/portfolio/technologies/python.png' | relative_url}}" width="60" height="60"> | **Python** is the language used for this project |
| <img src="{{'assets/img/portfolio/technologies/rabbitmq.png' | relative_url}}" width="60" height="60"> | **RabbitMQ** is used to publish tasks for the service |
| <img src="{{'assets/img/portfolio/technologies/postgre.png' | relative_url}}" width="60" height="60"> | **PostgreSQL**  is used for credentials and authentication parameters |
| <img src="{{'assets/img/portfolio/technologies/kafka.png' | relative_url}}" width="60" height="60"> | **Kafka** is used to produce collected data |
| <img src="{{'assets/img/portfolio/technologies/mongo.gif' | relative_url}}" width="60" height="60"> | **MongoDB** is used to store produced data |
| <img src="{{'assets/img/portfolio/technologies/redis.png' | relative_url}}" width="60" height="60"> | **Redis** is used to store telegram sessions |
| <img src="{{'assets/img/portfolio/technologies/flask.png' | relative_url}}" width="60" height="60"> | **Flask** is used for authentication service |
| <img src="{{'assets/img/portfolio/technologies/docker.png' | relative_url}}" width="60" height="60"> | **Docker** is used for virtualization and containerizing services|
| <img src="{{'assets/img/portfolio/technologies/git.png' | relative_url}}" width="60" height="60"> | **Git** is used for version control |