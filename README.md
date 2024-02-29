# CRUD Application with React and Spring Boot

This is a simple CRUD (Create, Read, Update, Delete) application built using React for the frontend and Spring Boot for the backend. MySQL database is used to store and retrieve the data.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Backend Implementation](#backend-implementation)
  - [Spring Boot Setup](#spring-boot-setup)
  - [MySQL Database Configuration](#mysql-database-configuration)
  - [Creating JPA Entity](#creating-jpa-entity)
  - [Creating Spring Data JPA Repository](#creating-spring-data-jpa-repository)
  - [Service Layer Implementation](#service-layer-implementation)
  - [Controller Layer Implementation](#controller-layer-implementation)
- [Frontend Implementation](#frontend-implementation)
  - [React Setup](#react-setup)
  - [Adding Bootstrap](#adding-bootstrap)
  - [Consuming Backend APIs](#consuming-backend-apis)
  - [List Employee Component](#list-employee-component)
  - [Header and Footer Components](#header-and-footer-components)
  - [Routing Configuration](#routing-configuration)
  - [Add and Update Employee Components](#add-and-update-employee-components)
  - [Delete Employee Feature](#delete-employee-feature)
- [Running the Application](#running-the-application)
- [Conclusion](#conclusion)

## Introduction

This project demonstrates the implementation of a CRUD application using React and Spring Boot. It allows users to perform basic CRUD operations on employee records.

## Technologies Used

- React
- Spring Boot
- MySQL
- Axios
- Bootstrap

## Backend Implementation

### Spring Boot Setup

- Dependencies: `spring-boot-starter-data-jpa`, `spring-boot-starter-web`, `mysql-connector-j`, `lombok`
- Database configuration
- JPA Entity creation
- Spring Data JPA Repository
- Service layer implementation
- Controller layer implementation

## Frontend Implementation

### React Setup

- Create React app using `create-react-app`
- Install Bootstrap

### Consuming Backend APIs

- Axios for making HTTP requests to backend
- List Employee Component to display employee data
- Add and Update Employee Components for CRUD operations
- Header and Footer Components for UI

## Running the Application

1. Ensure backend (Spring Boot) is running.
2. Navigate to the frontend directory.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the React app.

## Conclusion

In this project, we successfully built a CRUD application using React and Spring Boot. The application allows users to manage employee records efficiently.

