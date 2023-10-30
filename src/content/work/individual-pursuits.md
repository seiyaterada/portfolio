---
title: Individual Pursuits
publishDate: 2023-12-01 00:00:00
img: /assets/projects/ip-homePage.jpg
img_alt: Home page of Individual Pursuits
description: |
  This application was developed for Individual Pursuits, a community social services organization, to allow staff to track goals and progress for each client
tags:
  - Design
  - Full Stack
---

### Problem Background and Project Description
Individual Pursuits is a community social services organization specializing in both residential supports and community inclusion programs for persons with a developmental disability. For goal tracking, they use a paper-based system that is difficult to maintain and track. The goal of this project is to create a web application that will allow staff to track goals and progress for each individual.

The web application will allow staff to create goals for each client and track their progress based on their goals. The application had to meet FOIPPA security requirements as this application will be storing personal information. The application will have role based access control to ensure that only specific staff can access pertinent information

### Development Phase
<p>
  The development team was comprised of myself, along with another student from my program I had worked with previously on school projects and had a valuable skillset for the project. I split the development tasks into four sprints, each lasting two weeks. There was also weekly meetings with stakeholders, and daily standups with the developers to ensure that the project was on track. The initial prototype was completed within the expected timeframe. The project was then deployed locally on the company network, where it was tested by the business stakeholders. The frontend was built using Next.js, a React framework with built-in routing and server-side rendering capabilities, along with Vercel's simple and cost effective deployment features. Material UI was used as the component library for the frontend for its ease of use and familiar design for end users.
</p>
<p>
  The backend was built using Express.js, a Node.js framework with TypeScript utilizing REST. Auth0 was used for authentication and authorization, integrated into our backend using Auth0's Node.js SDK.
</p>
<p>
  The database was built using PostgreSQL, a relational database. Prisma was used as an ORM to simplify database interactions and to ensure that the database schema was consistent with the application schema.
</p>

### Project Status
The application is currently in the user testing phase, where it is being tested by the business stakeholders. The application is expected to be deployed in the coming months to either DigitalOcean or AWS, and Vercel.
