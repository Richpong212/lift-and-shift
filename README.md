# Project Overview

This project showcases the implementation of a lift and shift strategy to deploy a Java application using various technologies including Maven, Tomcat, Memcached, MySQL, and RabbitMQ on AWS infrastructure. The project leverages EC2 instances for application deployment, AWS S3 for artifact storage, and Route 53 for DNS queries.

## Application URL and Test Credentials

You can access the deployed application using the following URL: [VProfile Application](http://vprofileapp.codegenitor.com/)

**Test Credentials:**

- Username: admin_vp
- Password: admin_vp

## Prerequisites

Before running the application, ensure that the following prerequisites are met:

- JDK 11
- Maven 3
- MySQL 8

## Technologies Used

The project utilizes the following technologies:

- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- RabbitMQ
- ElasticSearch

## Database Configuration

MySQL is used as the database backend for this application. To set up the database, follow these steps:

1. Import the SQL dump file provided:
   ```
   mysql -u <user_name> -p accounts < db_backup.sql
   ```

**Note:** The `db_backup.sql` file contains the necessary database schema and initial data.

---
