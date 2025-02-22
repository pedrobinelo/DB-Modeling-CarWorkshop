# Conceptual database design 

Second project challenge of [DIO](https://www.dio.me/) "SQL Database Specialist" course.

## 🚗 Car Workshop

- **Entities:** 

## 📖 Story

- Control and management system for executing work orders in a car workshop. 
- Customers take vehicles to the shop to be repaired or to go through periodic inspections.
- Each vehicle is assigned to a team of mechanics who identify the services to be performed and fill out an OS with a delivery date.
- From the OS, the price of each service is calculated, consulting a reference table.
- The price of each part will also be a part of the OS.
- The customer authorizes the execution of the services.
- The same team evaluates and performs the services. 
- Mechanics have a code, name, address and specialty.
- Each OS has: number, issue date, value ($), status and completion date.
- An OS can be made up of several services and the same service can be in more than one OS.
- An OS can have several types of parts and a part can be present in more than one OS.

## 💻 Challenge description 

Create the conceptual schema for the workshop context based on the narrative provided. 

## 💻 Technologies 

![MySQL Workbench](https://img.shields.io/badge/MySQL%20Workbench-ffffff?style=for-the-badge&logo=mysql&logoColor=black)

