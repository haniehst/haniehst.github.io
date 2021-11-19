---
layout: portfolio_detail
order: 6
title: Edge Caching
name: edge-caching
badge-description: Network Content Caching 
filter: filter-network
badge-image: badge.png
category: Network
client:
project-date: Spring 2020
project-url:
github-repository: haniehst/Edge-Caching
full-description: Optimization of Distributed Content Caching on the Edge of Wireless Networks with Malicious Users
images:
    - address: 'poten1.png'
      caption: 'Convergence of potential function'
    - address: 'poten2.png'
      caption: 'Convergence of the potential function in the presence of malicious users'
    - address: 'delay1.png'
      caption: 'Average Delay for users'
    - address: 'congestion.png'
      caption: 'Convergence of congestion on Backhaul links'
    - address: 'congestion1.png'
      caption: 'The amount of congestion on backhaul links in terms of Zipf parameter'
    - address: 'congestion2.png'
      caption: 'The amount of congestion on the backhaul links in terms of the number of stations'
---

#### Introduction
Demand for digital media services is increasing as the number of wireless subscribers is growing exponentially.
In order to meet this growing demand, wireless networks have developed with extraordinary rapidity recently.
One of the main challenges for these networks is the growth of traffic that can lead to delay increasing for users in order to access required content.
Transferring the content from source servers to users occupies a lot of bandwidth from the network back-haul links.
Content caching on the edge of wireless networks is a promising approach for increasing network performance.
This approach utilizes the storage of popular content at small base stations, which is an effective way to reduce network additional data traffic and improve the quality of service for users. Since some regions may appear in small cell networks which have overlap, the most popular content is not always optimal.
In the issue of content placement in small base stations, parameters such as content popularity, wireless channel status and bandwidth status for back-haul links are input parameters and the calculation of optimal placement depends on the values of these parameters. An effective placement algorithm using a potential game gives the potential to achieve improved performance delay by decreasing complexity. This Algorithm is consistently running between small base stations and users. Otherwise, a fraction of these users may be under the control of a destructive entity and by sending requests for contents which are not stored in small base stations covering them, they increase the ratio of placement and congestion in back-haul links. In this case, in order to develop the distributed solution, the problem formulation is proposed based on a multilevel game (Multi-leader One-follower Stackelberg Game). In fact, in addition to the game that is played among the small base stations to determine the placement of the content, a second-level game is played between small base stations in order to deal with the malicious entity, which is to compute the Stackelberg equilibrium through hierarchical
learning algorithms. The obtained results show the convergence of the potential function, the average delay, and congestion in back-haul links by increasing the number of iterations of the algorithm. Also, by increasing the number of small base stations and the parameter which is known as content popularity, 
average delay and congestion in back-haul links are decreased.
#### Technologies/Languages Used

{: .table .table-striped}
| Technology | Usage |
|------------------|--------|
| <img src="{{'assets/img/portfolio/technologies/matlab.jpg' | relative_url}}" width="60" height="60"> | **Matlab** is used for developing this project. |
