# Accommodation Booking Website developed using ASP.NET MVC + Microsoft SQL Server 
### This tool allows users to add/ browse / book and rate accommodation.

Features
Browse and search for available services.
View detailed information about each service, including descriptions, prices, and availability.
Select booking preferences, such as date, time, and quantity.
Make bookings by adding selected services to the cart and proceeding to checkout.
Secure user authentication and authorization mechanisms.
Admin panel to manage services, availability, and user bookings.
Technologies Used
ASP.NET MVC: The web application framework used for building the frontend and backend components.
Microsoft SQL Server: The relational database management system for storing user data, service information, and bookings.
HTML, CSS, JavaScript: Used to create the website's frontend and enhance user interactions.
Razor View Engine: Integrated with ASP.NET MVC to generate dynamic HTML content.
Bootstrap: Frontend framework for responsive and visually appealing designs.
C#: The primary programming language used for backend development.
Git and GitHub: Version control system and hosting platform for collaborative development and source code management.
Database Design
The database schema includes the following main tables:

Users: Stores user information including usernames and hashed passwords.
Services: Contains details about the available services or events.
Bookings: Records user bookings with related service information and booking preferences.
Application Structure
The application follows the standard ASP.NET MVC structure:

Models: Contains the data models that represent database tables.
Views: Includes Razor views responsible for rendering the frontend.
Controllers: Manages the application's logic and handles user interactions.
Services: Implements business logic and interfaces between controllers and data models.
User Roles and Authentication
The website has two main user roles:

User: Can browse services, make bookings, and manage their profile.
Admin: Can manage services, availability, view bookings, and perform administrative tasks.
User authentication is implemented using ASP.NET Identity, ensuring secure user registration and login processes.

Booking Process
Users browse services and select the ones they want to book.
They choose booking preferences such as date, time, and quantity.
Selected services are added to the cart.
Users proceed to checkout, where they review their selections.
Bookings are confirmed, and users receive a confirmation email.
Deployment
The application can be deployed using various hosting services such as Microsoft Azure, AWS, or on a private server. Deployment involves configuring the web server, setting up the database, and publishing the application.

Conclusion
The Booking Website developed using ASP.NET MVC and MSSQL provides a user-friendly platform for making bookings. The combination of a robust backend, responsive frontend, and secure authentication ensures a seamless experience for both users and administrators.

Feel free to contribute to this project by submitting pull requests or reporting issues. Your contributions will help enhance the functionality and usability of the Booking Website.
