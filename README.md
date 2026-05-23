Hospital Management System

This is a full stack hospital management system made for a database systems project. It uses PHP for the backend, HTML, CSS, and JavaScript for the frontend, and Microsoft SQL Server for the database.

The project helps show hospital data such as patients, doctors, wards, care units, treatment records, complaints, and consultant teams.

Project Features:
1) View a hospital dashboard with live database counts.

2) View patient records.

3) View ward records and admitted patients.

4) View consultant team details.

5) Run the required SQL Server queries from the web interface.

6) Show recent treatment records.

7) Show complaint summary and ward occupancy.


Technologies Used

1) HTML

2) CSS

3) JavaScript

4) PHP

5) Microsoft SQL Server


Project Structure:

The hospital folder contains the PHP web application.

The assets folder contains the CSS and JavaScript files.

The includes folder contains shared PHP files for the header, footer, database connection, and query functions.

The sql folder contains the database scripts.

The PDF files contain the normalization and table description documents.


Database Files:

The project includes SQL scripts for creating the database tables, inserting initial data, and running project queries.

Use the DDL script to create the database structure.

Use the insertion script to add sample data.

Use the queries script to view the required SQL queries.


How To Run:

Install Microsoft SQL Server.

Create the database using the DDL script.

Insert the sample data using the insertion script.

Install PHP and enable the SQLSRV extension.

Place the hospital folder in your local server directory.

Update the database connection in hospital/config.php if needed.

Open the project in a browser using your local server.

Default Database Connection

The project currently connects to localhost\SQLEXPRESS.

The database name used in the project is IvorPaineHospital.

If your SQL Server name or database name is different, update hospital/config.php.

Purpose

This project was created to demonstrate a complete database backed hospital management system. It connects a PHP web interface with a Microsoft SQL Server database and displays real hospital records through forms, reports, and queries.
