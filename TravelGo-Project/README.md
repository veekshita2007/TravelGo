Overview

TravelGo is a web-based travel booking platform that allows users to easily book transportation and accommodation services such as Flights, Trains, Buses, and Hotels. The application provides a simple and user-friendly interface where users can create accounts, search travel options, make bookings, view booking history, and cancel reservations.

The system is built using Python Flask, HTML, CSS, and JavaScript, with optional integration with AWS DynamoDB and SNS for cloud data storage and notifications.

Features
User Authentication

User Registration

Secure Login System

Password hashing for security

Session-based authentication

Travel Booking

Users can book different types of travel services:

Bus Tickets

Train Tickets

Flight Tickets

Hotel Reservations

Booking System

Select source city and destination

Choose travel date

Automatic seat allocation

Dynamic price generation

Unique booking ID generation

Booking Management

View booking history

Cancel bookings

Track booking status (Confirmed / Cancelled)

Notifications

Sends booking notifications using AWS SNS

Provides confirmation alerts for bookings and cancellations

Cloud Integration

TravelGo supports:

AWS DynamoDB for storing users and bookings

AWS SNS for sending notifications

If AWS credentials are not available, the system automatically switches to local storage mode.

Technologies Used
Backend

Python

Flask Framework

Frontend

HTML5

CSS3

JavaScript
