# **Accommodation Booking Tool**
## **Tech used: ASP.NET MVC 5 + Microsoft SQL Server**
### **Project description: The tool allows users to browse/ add/ book and rate accommodation**



## Project Structure
The project follows a standard ASP.NET 5 structure. Here's an overview of the important files and folders:


* BLL - Contains the business logic. An intermediary between the presentation layer (UI) and the data access layer (DAL)
* DAL - Deals with database-related operations, including querying and updating data in the database
* Common -  Holds utility classes, shared models, and other components that are used across multiple layers of your application
 
* Controllers/: Contains the controller classes for handling HTTP requests
* Models/: Includes the model classes representing data entities
* Views/: Holds the Razor views for rendering HTML





# Installation

## Prerequisites

- Visual Studio (2013 or later) with ASP.NET and Web Development workload
- Microsoft SQL Server (Express edition or higher)



## Installation of dependencies using Composer

`composer install`

## Database setup 

- `php bin/console doctrine:database:create`
- `php bin/console doctrine:migrations:migrate`

## Start the Development Server
navigate to the project's root directory and run:

`symfony serve`
