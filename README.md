# Railway Reservation System

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Database Setup](#database-setup)
  - [Running the Railway Reservation System](#running-the-railway-reservation-system)
- [Usage](#usage)
- [Contribution](#contribution)

---

## Project Overview

The Railway Reservation System is a Java-based application designed for booking and managing train tickets. This system aims to streamline the ticket booking process for passengers and provides efficient ticket management tools for administrators within the railway industry.

## Features

- **User Registration and Authentication:**
  - New users can create accounts by providing their personal details.
  - Users can securely log in using their email or username and password.

- **Dashboard:**
  - A user-friendly dashboard provides quick access to essential functionalities.
  - Quick links to reservation, cancellation, and booking history.

- **Ticket Reservation:**
  - Passengers can search for available trains, select seats, and confirm bookings.
  - PRN (Passenger Reservation Number) is generated after successful booking.
  - Homepage automatically opens after booking completion.

- **Ticket Cancellation:**
  - Passengers can cancel booked tickets by entering their PRN.
  - Detailed reservation information is displayed for verification.

- **Ticket Management:**
  - Booking history allows passengers to review past and upcoming journeys.
  - Modify bookings (if allowed by railway policy).

- **Administrator Functions:**
  - Admin login for authorized personnel.
  - Manage train schedules, station data, and user accounts.
  
## Setup

### Prerequisites

Before running the Railway Reservation System, ensure you have the following:

- Java Development Environment (JDK)
- MySQL Database Server
- Java IDE or Compiler

### Database Setup

1. Create a MySQL database named `RailwayReservation`.
2. Import the provided SQL script to create tables and sample data.

### Running the Railway Reservation System

Launch the application using your preferred Java IDE or command-line tool.

## Usage

1. **User Registration:**
   - Create a new account with personal details.
   - Log in securely using email or username and password.

2. **Dashboard:**
   - Access reservation, cancellation, and booking history functionalities.

3. **Reservation:**
   - Search for trains, select seats, and confirm bookings.
   - Receive a PRN for future reference.

4. **Cancellation:**
   - Cancel booked tickets by entering the PRN.
   - Verify and confirm cancellation.
