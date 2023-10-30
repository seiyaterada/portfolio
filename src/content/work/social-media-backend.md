---
title: Scalable Social Media Backend
publishDate: 2019-10-02 00:00:00
img: /assets/projects/social-media-backend.jpg
img_alt: Soft pink and baby blue water ripples together in a subtle texture.
github: https://github.com/seiyaterada/socialMediaApp
description: |
  A scalable social media backend that allows users to create posts, follow other users, and like posts.
tags:
  - System Design
  - API Development

---

<p>
    This application is a scalable high-performance social media application that allows users to post messages, follow other users, and view their timeline. The application is built using the distributed architecture using docker. The application was made to handle large numbers of concurrent users and support real-time notifications and messaging. To achieve this the following technologies were used to make the application more scalable:
    <li>NodeJS</li>
    <li>MongoDB</li>
    <li>Redis</li>
    <li>NGINX</li>
    <li>RabbitMQ</li>
    <li>Docker</li>
</p>
<p>
    MongoDB was used for storing user, post, commnet, and notification information. Redis was used for caching user information and RabbitMQ was used for messaging between the different services. NGINX was used as a reverse proxy to load balance the requests to the different services. Docker was used to containerize the different services and make the application more scalable.
</p>