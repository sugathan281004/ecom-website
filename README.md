# Ecommerce App

A simple ecommerce web application for browsing and purchasing products.

## Table of Contents

- [Description](#description)

- [Features](#features)

- [Technologies Used](#technologies-used)

- [Installation](#installation)

- [Usage](#usage)

- [Login Credentials](#login-credentials)

- [Contributing](#contributing)

- [Acknowledgments](#acknowledgments)

- [Contact](#contact)

## Description

This project is a web-based ecommerce application built with Thymeleaf, Bootstrap, and the Java Spring Framework. It allows users to view products, learn about the company, and contact the team. The project is designed with a responsive layout and includes essential features for a small-scale ecommerce platform.

## Features

- Responsive design with Bootstrap
- User authentication and authorization
- Product browsing and search
- Contact form integration

## Technologies Used

- **Java Spring Framework** for backend services
- **Thymeleaf** for server-side rendering
- **Bootstrap 5** for frontend styling
- **MySQL** for database management

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sugathan281004/ecom-website.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ecommerce-app
   ```
3. Configure the database:
   - Update the `application.properties` file with your database credentials.
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```
4. Install dependencies and build the project:
   ```bash
   ./mvnw clean install
   ```
5. Start the server:
   ```bash
   ./mvnw spring-boot:run
   ```

## Usage

1. Open your browser and navigate to:
   ```
   http://localhost:8080
   ```
2. Explore the features:
   - Browse products via the "Products" page.
   - Learn about the company on the "About Us" page.
   - Use the contact form on the "Contact Us" page.

## Login Credentials

### Admin

- **Email:** [johnwick@gmail.com](mailto\:johnwick@gmail.com)
- **Password:** qwerty

### User

- **Email:** [smith@gmail.com](mailto\:smith@gmail.com)
- **Password:** qwerty

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## Acknowledgments

- Bootstrap for frontend styling.
- Thymeleaf documentation for template rendering.
- Spring Boot community for backend support.

## Contact

Maintainer: [p.suganthan04@gmail.com](mailto\:p.suganthan04@gmail.com)

Feel free to reach out with any questions or suggestions!

