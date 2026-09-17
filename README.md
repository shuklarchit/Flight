# Airline Ticket Booking Management System
The Airline Ticket Booking Management System is a Java-based desktop application project that can be developed using Java Swing and AWT. The purpose of the project is to provide a simple interface for various airline-related tasks like managing passengers, flights, and ticket bookings.

The project has been mainly developed for educational and demonstration purposes to showcase how Java GUI components, JDBC, and database interactions can be used in a desktop application.                                                          

## Project Overview                              

The system provides a variety of modules to manage airline operations. A user can log in to the application and use various functionalities based on the available modules.

Some of the key operations are:                                             

--> User login and authentication
--> Adding and managing passenger information
--> Adding and viewing flight information
--> Booking airline tickets
--> Updating booking information
--> Cancelling tickets
--> Using database for managing records
--> A simple desktop GUI for interaction with the system

## Project Structure

The project comprises of various java classes that perform specific operations.

For example:
```text

Airline Management System

│

├── Login.java

├── Passenger Details

├── Flight Information

├── Ticket Booking

├── Cancellation

├── Update Details

├── Database / JDBC Classes

└── Other Utility Classes

```

### Key Classes

--> Login.java
This class comprises the login screen and handles the basic authentication process.

--> Passenger Details
Used to manage information related to passengers.

--> Flight Information
This provides different options to add or view available flight details.

--> Ticket Booking
Handles all the steps involved in the booking tickets for the passengers.

--> Cancellation / Update
This is used to cancel any previously booked tickets or update passenger information.

--> Database Classes
These are the classes that interact with the MySQL database to perform the various operations like insert data, update, delete, and retrieve information.

## Technologies Used

Java
Java Swing
Java AWT
JDBC
MySQL
JCalendar
NetBeans
The project can work with JDK 8 or later.

## Features

### 1. Login
The user can use the login screen to login into the application.

### 2. Passenger
Passenger information can be added/viewed/updated from this module.

### 3. Flight
The system allows flight-related information to be added/viewed.

### 4. Ticket Booking
Users can enter passenger-related details and flight information to book tickets.

### 5. Cancellation
The ticket booking functionality allows users to cancel tickets that had been previously booked.

### 6. Update
User can update passenger or ticket details where necessary.

### 7. Desktop GUI
The desktop application uses Swing and AWT components like frames, panels, buttons, text fields, tables, and etc. to provide an interface for the application.

## Database
The database component of the project requires the installation of MySQL. The application makes use of JDBC (Java Database Connectivity) to connect to the MySQL database.

Before running the project make sure that:

1. MySQL is installed and running.
2. The required database has been set up.
3. The required tables are available.
4. The database username and password in the Java connection code are valid.
5. The MySQL JDBC driver has been added to the project.

## How to Run

### Step 1: Download the Project
Download or clone the project and extract the zip file if necessary.

### Step 2: Open the Project
Open the project in NetBeans, IntelliJ IDEA, or Eclipse.
NetBeans can be used to open the project, if it was created as a NetBeans project.

### Step 3: Configure Java
Make sure that JDK 8 or above is installed and configured in the IDE.

### Step 4: Configure the Database
If the project uses MySQL, create the required database and tables.
Once the database is set up, check the JDBC details in the project and update where necessary.

### Step 5: Add Required Libraries
Ensure that all required `.jar` files are added to the project.

For example, if the project uses a calendar component, add the required JCalendar libraries.

### Step 6: Run the Application
Run:

```text

Login.java

```

The login screen should appear and from there a user can access various modules of the application.

## Requirements

Before running the project make sure that you have the following:

JDK 8 or later
Java IDE such as NetBeans, IntelliJ IDEA, or Eclipse
MySQL (if database functionality is used)
MySQL JDBC Driver
JCalendar library (if required by the project)

## Common Issues

### JCalendar Error
If you get an error related to JCalendar, check whether the JCalendar `.jar` file has been added to the project libraries.

### ClassNotFoundException
This usually means that a required library is missing or has not been added correctly.

Try:

Checking the project libraries
Adding the required `.jar` file
Cleaning and rebuilding the project
Restarting the IDE if necessary

### Database Connection Error

Check the following:
MySQL server is running
Database name is correct
Username and password are correct
JDBC driver is present
Database port is correct

## Future Improvements

=> Some of the features that can be added to the project to make it more production-ready in the future are:
=> Better login and user roles
=> Online flight search
=> Improved ticket generation
=> Email confirmation for bookings
=> Payment integration
=> Better database security
=> Improved UI design
=> Admin dashboard
=> Search and filter options for flights and passengers

## Purpose of the Project

The purpose of this project is mainly educational. This project helps in understanding Java GUI development, object-oriented programming, JDBC, and the basic structure of a desktop-based management system.
