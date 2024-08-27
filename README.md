# E-Mart

E-Mart is a B2C e-commerce system developed to allow registered members to browse and purchase items through various categories. The system supports handling discounts, loyalty points, and generates invoices in PDF format which are emailed upon successful transactions.

## Project Overview

- **Duration**: 1 Month
- **Technologies Used**:
  - **Backend**:
    - **Spring 6** 
    - **Maven 3**
    - **Spring Boot 3**
    - **REST API**
    - **MySQL 8**
    - **JPA**
    - **Docker**
    - **JWT**
    - **Microservices**
    - **.NET Core 7.0**
    - **Web API Core 7.0**
    - **Entity Framework Core 7.0**
  - **Frontend**:
    - **React.js 18**

## Features

- **Browse & Purchase**: Users can browse through various categories and purchase items.
- **Discount Handling**: The system manages various types of discounts on products.
- **Loyalty Points**: Members can use loyalty points during checkout.
- **Invoice Generation**: Invoices are generated in PDF format and emailed upon successful transactions.
- **Microservices**: The architecture uses microservices for scalability and flexibility.

## Installation

### Prerequisites

- **Java JDK 17+**
- **.NET SDK 7.0+**
- **Node.js 18+**
- **Docker**

### Backend Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/pravin2706/E-Mart.git
   cd E-Mart
   ```

2. **Spring Boot Application:**
   - Navigate to the `backend` directory.
   - Build the application using Maven:
     ```bash
     mvn clean install
     ```
   - Run the Spring Boot application:
     ```bash
     mvn spring-boot:run
     ```

3. **.NET Core Web API:**
   - Navigate to the `dotnet-api` directory.
   - Restore dependencies and build the project:
     ```bash
     dotnet restore
     dotnet build
     ```
   - Run the .NET Core application:
     ```bash
     dotnet run
     ```

### Frontend Setup

1. **Navigate to the `frontend` directory:**
   ```bash
   cd frontend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the React application:**
   ```bash
   npm start
   ```

### Docker Setup

1. **Build and run Docker containers:**
   ```bash
   docker-compose up --build
   ```

## Configuration

- **Database**: Configure `application.properties` or `appsettings.json` with the appropriate database credentials.
- **Email Service**: Set up SMTP configuration for email notifications in the application properties.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.


## Contact

For any questions, please contact [Pravin](mailto:pravinypawar@gmail.com).

---

Feel free to customize the sections, especially the installation and configuration details, based on your project setup and requirements.
