---
layout: project
type: project
image: img/download.jpg
title: "Personal Finance Tracker"
date: 2025
published: true
labels:
  - React
  - Java
  - Spring Boot
  - REST API
  - MySQL
  - AWS
summary: "A full-stack personal finance tracking application that allows users to securely manage income and expenses, visualize spending patterns, and gain actionable financial insights through interactive dashboards."
---

<img class="img-fluid" src="../img/download.jpg">

The Personal Finance Tracker is a full-stack web application I built to help users better understand and manage their finances by tracking income, expenses, and spending categories over time. The project was designed with an emphasis on usability, secure data handling, and real-world deployment.

The application enables users to register, authenticate, and interact with their financial data through a clean, responsive interface backed by a robust RESTful backend.

<hr>

### Project Overview

Many personal budgeting tools are either overly complex or lack transparency in how financial data is stored and processed. This project was built to explore full-stack system design while delivering a practical tool that improves financial awareness for individuals and households.

Users can log income and expenses, assign categories, and view summaries that make spending patterns easier to understand at a glance.

<hr>

### Architecture and Key Components

The frontend is built with **React**, providing a responsive user experience and dynamic dashboards that visualize income, expenses, and key financial statistics. State management and component-driven design enable real-time updates as users interact with their data.

The backend is a **Java-based REST API** built with **Spring Boot**, using **JPA and Hibernate** for object-relational mapping. The API handles user authentication, request validation, and CRUD operations for financial records.

A **MySQL database** persists user accounts, income entries, expenses, and categories, ensuring reliable and secure data storage. The system was tested using **Postman** to validate API endpoints and workflows.

<hr>

### Deployment

The application is fully deployed using **AWS cloud infrastructure**:

- **Amazon RDS** hosts the MySQL database  
- **Elastic Beanstalk** deploys and manages the Spring Boot backend  
- **S3 and CloudFront** serve the React frontend  

This deployment setup ensures scalability, reliability, and cost-efficient hosting while making the application publicly accessible.

<hr>

### Impact

This project helped improve financial awareness among friends and household members by providing a simple, intuitive way to track spending and income. From a technical perspective, it strengthened my experience in building and deploying production-style full-stack applications, integrating frontend and backend systems, and managing cloud infrastructure.

<hr>

Source: <em>Personal project (source code available upon request)</em>
