# Workshop Spring Boot 3 & JPA

Welcome to the Workshop Spring Boot 3 & JPA repository! This project serves as a hands-on introduction to building applications using Spring Boot 3 and Java Persistence API (JPA).

## Table of Contents

- [About the Project](#about-the-project)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project

This workshop covers the basics of creating a RESTful API using Spring Boot 3 and JPA. The project includes:

- Setting up a Spring Boot application
- Configuring JPA and connecting to a database
- Creating entities and repositories
- Implementing CRUD operations
- Testing the application

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Java Development Kit (JDK) 17 or higher
- Maven 3.8.1 or higher
- An IDE such as IntelliJ IDEA or Eclipse
- A relational database such as MySQL or PostgreSQL

### Installation

1. Clone the repo

   ```sh
   git clone https://github.com/Taimisson/workshop-springboot3-jpa.git
   ```

2. Navigate to the project directory

   ```sh
   cd workshop-springboot3-jpa
   ```

3. Update the `application.properties` file with your database credentials

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/yourdatabase
   spring.datasource.username=yourusername
   spring.datasource.password=yourpassword
   ```

4. Build the project

   ```sh
   mvn clean install
   ```

5. Run the application

   ```sh
   mvn spring-boot:run
   ```

## Usage

After starting the application, you can access the API using tools like Postman or via a web browser. The base URL for the API is `http://localhost:8080`.

### API Endpoints

#### Categories
- `GET /categories` - Retrieve all categories
- `POST /categories` - Create a new category
- `GET /categories/{id}` - Retrieve a specific category by ID
- `PUT /categories/{id}` - Update a specific category by ID
- `DELETE /categories/{id}` - Delete a specific category by ID

#### Orders
- `GET /orders` - Retrieve all orders
- `POST /orders` - Create a new order
- `GET /orders/{id}` - Retrieve a specific order by ID
- `PUT /orders/{id}` - Update a specific order by ID
- `DELETE /orders/{id}` - Delete a specific order by ID

#### Products
- `GET /products` - Retrieve all products
- `POST /products` - Create a new product
- `GET /products/{id}` - Retrieve a specific product by ID
- `PUT /products/{id}` - Update a specific product by ID
- `DELETE /products/{id}` - Delete a specific product by ID

#### Users
- `GET /users` - Retrieve all users
- `POST /users` - Create a new user
- `GET /users/{id}` - Retrieve a specific user by ID
- `PUT /users/{id}` - Update a specific user by ID
- `DELETE /users/{id}` - Delete a specific user by ID

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
