# Java Microservices

A Spring Boot Microservices project demonstrating a service-based architecture using independent services for Product, Order, and Inventory management.

## Architecture

The project consists of the following microservices:

### Product Service

* Manage product information
* Create and retrieve products
* Exposes REST APIs for product operations

### Order Service

* Handles customer orders
* Communicates with other services when processing orders
* Manages order-related business logic

### Inventory Service

* Tracks product availability
* Verifies stock before order processing
* Maintains inventory records

## Technologies Used

* Java
* Spring Boot
* Spring Data JPA
* Maven
* MySQL
* REST APIs

## Project Structure

```text
java-microservice/
│
├── inventory/
├── order/
├── product/
├── pom.xml
└── README.md
```

## Getting Started

### Prerequisites

* Java 17 or higher
* Maven
* MySQL

### Clone Repository

```bash
git clone https://github.com/<your-username>/java-micorservice.git
```

### Build Project

```bash
mvn clean install
```

### Run Services

Run each microservice separately from its main application class.

## Features

* Microservices Architecture
* RESTful APIs
* Database Integration with MySQL
* Service Separation and Modularity
* Maven Multi-Module Project Structure

## Author

Oshada Nethmina
