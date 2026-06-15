# Football Ticket Booking System (PostgreSQL) -- Assignment - 03

## Project Resources

### ERD Diagram :

https://drawsql.app/teams/topper/diagrams/ticket-booking-assignment-3

### GitHub Repository :

https://github.com/hanifulislam160/football-booking-system-sql

### Interview Video :

https://app.usebubbles.com/pUUZDSfCeiWJzSYBRHK8we/recording-jun-15-2026


---

## Project Overview

This project is a **Football Ticket Booking System Database Design Assignment** built using **PostgreSQL**.

The system manages:

- Users (Ticket Manager & Football Fan)
- Football Matches
- Ticket Bookings

This project demonstrates:

- Database schema design
- ERD relationships
- Primary Key & Foreign Key implementation
- Referential integrity
- SQL queries with filtering, joins, aggregation, and search operations

---

## Database Schema

### Users

Stores all registered users.

Fields:

- user_id
- full_name
- email
- role
- phone_number

### Matches

Stores football match information.

Fields:

- match_id
- fixture
- tournament_category
- base_ticket_price
- match_status

### Bookings

Stores ticket purchase information.

Fields:

- booking_id
- user_id
- match_id
- seat_number
- payment_status
- total_cost

---

## Relationships

- One User → Many Bookings
- One Match → Many Bookings

Users (1) → Bookings ← (1) Matches

---

## Technologies Used

- PostgreSQL
- SQL
- DrawSQL

---

## SQL Features Implemented

- CREATE TYPE (ENUM)
- CREATE TABLE
- PRIMARY KEY
- FOREIGN KEY
- GENERATED ALWAYS AS IDENTITY
- JOIN Queries
- Aggregate Functions
- Pattern Matching (ILIKE)
- GROUP BY & HAVING
- Pagination

---

## Author

Haniful Islam
