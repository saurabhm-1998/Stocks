# StockApp Using SpringBoot

The Stocks application is a simple stock management system built using Java. It allows users to manage and track stocks in different categories. The application provides functionality to add, update, and delete stocks, as well as retrieve stock information.

## Project

The project is developed using the following frameworks and languages:

Spring Boot: A Java-based framework for building web applications.

Java: The primary programming language used for developing the application


## Data Flow

The data flow in this project follows the typical MVC (Model-View-Controller) pattern, with the following components:

### Controller
The Controller layer handles incoming HTTP requests and manages the flow of data.
It receives user input and invokes the appropriate methods in the Service layer.
The Controller is responsible for processing requests, validating data, and sending responses back to the client.

### Service
The Service layer contains the business logic of the application.
It performs operations on the data received from the Controller.
The Service layer communicates with the Repository to fetch or store data.
It may also apply additional business rules or transformations to the data before returning it to the Controller.

### Model
The Model layer represents the data structure used in the application.
In this project, the Stock model is defined, which contains properties like ID, stock name, stock price, and stock type.
The stock type is defined as an enumeration (enum) with values FMGG, IT, and HEALTH to categorize the stocks.

### Repository
The Repository layer is responsible for data storage and retrieval.
It interacts with the underlying database or data source to perform CRUD operations on the data.
In this project, the Repository is responsible for managing stocks and storing them in memory or a persistent storage system.

## Project Summary

The Stocks application is a simple stock management system built using Java. It allows users to manage stocks in different categories. The application follows the typical flow of data between the Controller, Service, and Repository layers. It utilizes the Stock model to represent stock data, including properties like ID, stock name, stock price, and stock type. The application can be extended to include additional features such as stock performance analysis, user authentication, and real-time stock updates, based on specific requirements.
