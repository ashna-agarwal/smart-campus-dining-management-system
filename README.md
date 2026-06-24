# smart-campus-dining-management-system

# Smart Campus Dining

A Database Management System (DBMS) project designed to reduce waiting times and overcrowding at university food outlets through an integrated online ordering and pickup management system.

## Live Demo

https://scd-final.vercel.app/

<img width="1001" height="524" alt="image" src="https://github.com/user-attachments/assets/71cb2c08-7804-4425-9203-28b93070f831" />

<img width="999" height="524" alt="image" src="https://github.com/user-attachments/assets/701f094c-bf57-407e-8c89-31534e1f2175" />

<img width="1000" height="525" alt="image" src="https://github.com/user-attachments/assets/99be39c7-c682-4b54-b415-eb29400378c4" />


## Problem Statement

University campuses often experience long queues and overcrowding at food outlets during peak hours. Traditional manual ordering systems lead to delays, inefficient service, and poor user experience.

Smart Campus Dining addresses these issues by enabling students to:

- Place food orders online
- Select pickup slots
- Make digital payments
- Receive real-time order updates
- Reduce waiting time and crowding

The system also assists food outlets with better order management and operational efficiency.

---

## Features

### User Management
- User registration and login
- Profile management
- Secure authentication

### Food Ordering
- Browse available menu items
- View pricing and nutritional information
- Select quantity and pickup slot

### Order Management
- Create orders
- Track order status
- View order history

### Payment Management
- Online payment support
- Payment status tracking
- Order-payment association

### Outlet Management
- Multiple food outlets
- Outlet-specific menu items
- Availability tracking

---

## ER Model

The database is designed using an Entity Relationship (ER) Model consisting of:

### Entities

1. User
2. Order
3. Payment
4. Outlet
5. Menu Items
6. Ordered Items

### ER Diagram

![ER Diagram](assets/er-diagram.png)

---


## Relationships

- A User places Orders.
- An Order contains multiple Menu Items.
- A Menu Item belongs to an Outlet.
- A User makes Payments.
- A Payment is associated with an Order.
- Ordered_Items acts as a bridge table between Orders and Menu Items.

---

## Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- SQL
- Database Management Concepts

### Deployment
- Vercel

---

## Academic Information

Course: Database Management System (CDCS0302)

Institution: Netaji Subhas University of Technology (NSUT)

---

## Future Enhancements

- Real-time order notifications
- QR-based pickup system
- Analytics dashboard for outlets
- AI-based demand forecasting
- Mobile application support

