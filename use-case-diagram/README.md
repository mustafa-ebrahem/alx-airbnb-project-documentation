# Airbnb Clone Use Case Diagram

## Overview
This document contains a use case diagram for the Airbnb Clone project, visualizing the interactions between different actors and the system. The diagram illustrates how users interact with key functionalities such as user registration, property management, booking, and payments.

## Actors
The use case diagram includes the following actors:

1. **Guest User**: Users who browse properties and make bookings
2. **Host User**: Users who list and manage properties
3. **Admin**: System administrators who manage the platform
4. **Payment System**: External payment processing systems

## Key Use Cases

### User Management
- Register Account
- Login to System
- Manage Profile
- Reset Password

### Property Management (Host)
- Create Property Listing
- Edit Property Details
- Upload Property Images
- Manage Availability Calendar
- Remove Property Listing
- View Booking Requests

### Booking System (Guest)
- Search Properties
- Filter Search Results
- View Property Details
- Book Property
- Cancel Booking
- View Booking History
- Review Properties

### Payment System
- Process Payment
- Issue Refund
- Pay Host

### Admin Functions
- Manage Users
- Moderate Content
- Resolve Disputes
- Generate Reports

## Diagram
The use case diagram below represents these interactions visually. The diagram was created using Draw.io and exported as an SVG file.

![Airbnb Clone Use Case Diagram](airbnb-clone-use-case-diagram.svg)

## Relationships
- **Include**: Represents that one use case necessarily includes the behavior of another
- **Extend**: Represents optional behavior that may be triggered under specific conditions
- **Association**: Connects actors to the use cases they participate in

This use case diagram serves as a visual guide to understand the system's functional requirements and how different actors interact with the system.