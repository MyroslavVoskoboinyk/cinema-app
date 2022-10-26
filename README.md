# Cinema Application
This application is a cinema reservation system simulator based on Spring and Hibernate technologies. User authentication is implemented (by default) and an administrator can be added if needed. The user can add tickets to the shopping cart, after which the user can make an order, which will be saved in the order history.

## The project has an N-Tier Architecture
- DAO - data access objects - all the work with the database takes place at this stage(CRUD methods)
- Service - all business logic takes place at the service level
- Controller - accepts requests from clients and send responses

## Features:
- Registration
- Log in / Log out
- User has an ability to purchase tickets for a movie session
- Admin has an ability to create/delete new session, new movie

## Technologies:
- Java 11
- Hibernate
- Spring MVC
- Spring Security
- Hibernate 
- Tomcat 
- MySQL

## Quickstart:
1. Fork this repository
2. Clone the repository to PC
3. Edit resources/db.properties - set the necessary parameters:
> ```
> db.driver=YOUR_DRIVER
> db.url=YOUR_DATABASE_URL 
> db.user=YOUR_USERNAME 
> db.password=YOUR_PASSWORD
> ```
4. Install and configure Tomcat (9.0.50)
5. Run project