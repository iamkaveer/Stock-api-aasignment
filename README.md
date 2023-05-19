# Stock-api-aasignment
The Stock Management System is a web-based application developed using Spring Boot. It offers a comprehensive set of RESTful endpoints to facilitate efficient management of stocks. Users can retrieve stocks based on different criteria, update stock information, insert new stocks, and delete stocks based on the owner count.

## Technology Stack
The Stock Management System is built using the following technologies and frameworks:
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- RESTful API

## Endpoints
The Stock Management System exposes the following endpoints:
```bash
  GET /stock/type/{stockType} - Retrieves stocks based on the specified stock type.
```
```bash
GET /stocks/price/above/{price}/date/lower/{date} - Retrieve stocks with a price above a given value and a date lower than a specific date.
```
```bash
GET /stocks/cap/{capPercentage} - Retrieve stocks with a market capitalization above a certain percentage.
```
```bash
POST /stocks - Insert new stocks into the system.
```
```bash
PUT /stocks/{id}/marketCap/{marketCap} - Update the market capitalization of a stock by its ID.
```
```bash
PUT /stocks/{id}/type/{stockType} - Update the stock type of a stock by its ID.
```
```bash
PUT /stocks/{id} - Update stock information by its ID.
```
```bash
DELETE /stocks/ownerCount/{count} - Delete stocks based on the owner count.
```

## How to Use
To use the Stock Management System, follow these steps:
- Clone the repository or download the project files.
- Import the project into your preferred Java development environment.
- Set up the necessary dependencies and configurations (e.g., database configuration).
- Build and run the application.
- Access the endpoints using an HTTP client (e.g., cURL, Postman, or a web browser) by sending requests to the appropriate URL and HTTP method.
- Make sure to provide the required request parameters and payload as specified in the endpoint documentation.

## Summary
The Stock Management System is a powerful web-based application that leverages Spring Boot to provide an efficient solution for managing stocks. With its comprehensive set of RESTful endpoints, users can retrieve stocks based on various criteria, update stock information, insert new stocks, and delete stocks based on the owner count. By following the provided documentation and utilizing the appropriate HTTP methods and request parameters, users can effectively interact with the system and streamline their stock management processes.
