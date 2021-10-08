---
layout: portfolio_detail
order: 12
title: Noise Reduction
name: noise-reduction
badge-description: A project removes noises from noisy images.
filter: filter-ai
badge-image: badge.png
category: AI
client:
project-date: Fall 2017
project-url:
github-repository: haniehst/Noise-Reduction
full-description: A project adding noise to sample pictures and denoise them later using spatial and frequency domain filters. 
images
    - address: 'gaussian.png'
      caption: 'A picture which has Gaussian Noise'
    - address: 'median.png'
      caption: 'Remove the noise using median filter'
    - address: 'mean.png'
      caption: 'Remove the noise using mean filter'
---

#### Introduction
This project is implemented for **Artificial Intelligence** course during my B.Sc. period. With the help of OpenCV three types of noises are added to our test images:
* gaussian
* salt & pepper
* speckle
then with the help of spatial (median and mean filters) and frequency domain filters the noise is removed from the image.

#### Technologies/Languages Used

{: .table .table-striped}
| Technology | Usage |
|------------------|--------|
| <img src="{{'assets/img/portfolio/technologies/python.png' | relative_url}}" width="60" height="60"> | **Python** language is used for developing the applications |
| <img src="{{'assets/img/portfolio/technologies/opencv.png' | relative_url}}" width="60" height="70"> | **OpenCV** framework is used for implementing the image processing algorithm |
| <img src="{{'assets/img/portfolio/technologies/git.png' | relative_url}}" width="60" height="60"> | **Git** is used for version control |