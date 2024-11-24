# Workplace-Management-Application


## Overview

This project is designed to model a real-world workplace application where an admin can manage employee records securely. The system includes features like:

- **Employee Management**: Add, update, and view employee details including name, hourly rate, and start date.
- **Monthly Earnings Calculation**: Calculate monthly earnings based on an employee's hourly rate.
- **Secure Authentication**: Use bcrypt for password hashing to ensure secure user login and signup.
- **Data Persistence**: Store employee data securely in a SQL Server database, with functionality for reading and parsing CSV and JSON files.
- **Windows Forms Interface**: A user-friendly GUI built using Windows Forms for easy navigation and interaction.

## Features

- **Employee Information**: Allows storing and displaying employee details, including their ID, name, hourly rate, and start date.
- **Monthly Earnings Calculation**: Computes the monthly earnings of employees based on a fixed 160 working hours per month (can be adjusted).
- **Secure User Authentication**: Implements password hashing using BCrypt for secure login and user creation.
- **CSV and JSON Data Handling**: Provides functionality to read from and parse CSV and JSON files for importing employee data.
- **SQL Server Database Integration**: Data is stored securely in a SQL Server database with authentication handled through hashed passwords.

## Technologies Used

- **C#**: Object-oriented programming to structure the application.
- **Windows Forms**: GUI framework for building the application.
- **SQL Server**: Database for storing employee and user data securely.
- **BCrypt**: Password hashing for secure authentication.
- **CSV and JSON File Parsing**: Import/export employee data in CSV and JSON formats.
- **.NET Framework**: Utilized for building the Windows Forms application.

## Setup and Installation

### Prerequisites
- Visual Studio (or any C# compatible IDE)
- SQL Server for database management
- NuGet packages for BCrypt and SQL Server access

### Steps to Run the Application:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/repositoryname.git
