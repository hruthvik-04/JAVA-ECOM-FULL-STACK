# JAVA-ECOM-FULL-STACK: FullStack E-Commerce App using SpringBoot & React

## Introduction

Welcome to my full-stack e-commerce application built with Java (Spring Boot) and React! This project demonstrates a modern, scalable, and secure online store with features like product catalog, shopping cart, order management, authentication, and more.

## Features

- Spring Boot 3.2.3 backend with Java 21
- RESTful APIs for all operations
- MySQL & Redis integration (via Docker)
- Secure authentication and authorization (JWT, Spring Security)
- React frontend with Redux, Thunk, Material UI
- Modern UI/UX and best practices

## Project Structure

- **Backend:** Java, Spring Boot, JPA, Security, MySQL, Redis
- **Frontend:** React, Redux, Material UI
- **Docker:** For easy setup of MySQL and Redis

## How to Run

1. Clone this repo:  
   `git clone https://github.com/hruthvik-04/JAVA-ECOM-FULL-STACK.git`
2. Set up MySQL and Redis (see docker/ directory for scripts).
3. Configure your database credentials in `src/main/resources/application.yaml`.
4. Start the backend:  
   `./mvnw spring-boot:run` (Windows: `./mvnw.cmd spring-boot:run`)
5. Start the frontend:  
   `cd client`  
   `npm install`  
   `npm run dev`



## Credits

Developed by [Hruthvik](https://github.com/hruthvik-04)
