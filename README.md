# Next Talent Agency Website

Front-end website for a talent agency featuring actors, musicians, athletes, and models.

## Live Demo
Hosted on Netlify
[Visit the Live Website](https://golden-biscochitos-01a137.netlify.app/)

## Technologies Used
- HTML
- CSS
- JavaScript

## Pages
- Home
- About
- Booking
- Reviews
- Actors
- Athletes
- Models
- Musicians

## Database Integration

This project includes SQL database integration using JSP and JDBC.

The application connects to the Gateway Technical College IBM i (AS400) system
to retrieve talent data from the TALENTWEBSITE table.

Note: The database connection requires Gateway network/VPN access and valid
student credentials. For security reasons, the database credentials and server
environment are not included in this repository.

## Database Output

The application dynamically loads talent records from the SQL database.

![Database Output](images/db-results.png)

## Architecture

Frontend: HTML / CSS / JavaScript
Backend: JSP (Java Server Pages)
Database: DB2 on IBM i (AS400)
IDE: Apache NetBeans 27
Database access: JDBC
