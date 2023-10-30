---
title: Distributed Day Trading System
publishDate: 2018-03-02 00:00:00
img: /assets/projects/day-trading-system.jpg
img_alt: Iridescent ripples of a bright blue and pink liquid
github: https://github.com/seiyaterada/day-trading-system
description: |
  A distributed day trading system that allows users to buy and sell stocks in real time.
tags:
  - Design
  - Full Stack
  - Testing
---

This application is a scalable day trading application application that allows users to buy and sell stocks in real time. The application was designed with priorities set on scalability and efficiency to be able to handle a concurrent user load of 10,000 users. The application architecture is a distributed system with a client-server architecture. It consists of various components that are responsible for different tasks and can be deployed independently. MongoDB was used to store user information, while Redis was used to cache stock information that is frequently accessed from an external stock quote server. React was used for the frontend, while NodeJS was used for the backend. Docker was used to containerize the different services and make the application more scalable.