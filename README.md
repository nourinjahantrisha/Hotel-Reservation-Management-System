# Hotel Reservation Management System

A C-based Hotel Reservation Management System developed as part of the Software Engineering capstone project at Daffodil International University (DIU).

The project aims to simplify hotel room management, guest reservations, room availability tracking, and checkout billing using file handling in C.

## Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Key Features](#key-features)
- [System Workflow](#system-workflow)
- [Billing Calculation](#billing-calculation)
- [Technologies Used](#technologies-used)
- [Data Storage](#data-storage)
- [Project Status](#project-status)
- [Getting Started](#getting-started)
- [Testing Plan](#testing-plan)
- [Project Team](#project-team)
- [Course Instructor](#course-instructor)
- [Academic Purpose](#academic-purpose)

## Project Overview

The Hotel Reservation Management System is designed to provide a simple way to manage hotel rooms and reservations through a menu-driven C application.

Administrators can manage room details, update room rates, and monitor occupancy. Guests can search for available rooms, make reservations, and cancel bookings.

The system will use C file handling to store and retrieve room information, guest details, reservation records, and billing information without requiring a database management system.

## Objectives

- Simplify hotel room reservation and management.
- Track room availability and occupancy status.
- Store and retrieve records using file handling.
- Support booking and cancellation operations.
- Calculate room charges, taxes, and applicable discounts.
- Generate invoices during checkout.
- Apply seasonal pricing when required.

## Key Features

### 1. Room Management

- Maintain room numbers, room types, and nightly rates.
- Add rooms and update existing room details.
- Apply seasonal pricing.
- Track available and occupied rooms.

### 2. Reservation Management

- Search for available rooms.
- Display room types and nightly rates.
- Book available rooms and record guest information.
- Cancel existing reservations.
- Update room availability after booking or cancellation.

### 3. Billing and Checkout

- Calculate room charges based on the number of nights stayed.
- Apply configured taxes and eligible discounts.
- Calculate the final payable amount.
- Generate an invoice containing reservation and billing details.

### 4. File Handling

- Save and retrieve room information.
- Store guest and reservation records.
- Update records when bookings are created or cancelled.
- Maintain billing records where required.

## System Workflow

1. The user opens the application.
2. The user selects an available operation from the menu.
3. The system retrieves the required records from files.
4. The guest searches for a room or manages an existing reservation.
5. The system validates the requested operation and updates the relevant records.
6. At checkout, the system calculates the bill and generates an invoice.
7. The updated records are saved for future use.

## Billing Calculation

The billing module calculates the amount payable at checkout.

**Basic formula:**

- Room Charge = Nightly Rate × Number of Nights
- Subtotal = Room Charge + Other Applicable Charges
- Tax Amount = Taxable Subtotal × Tax Rate
- Discount Amount = Eligible Amount × Discount Rate
- Final Amount = Subtotal + Tax Amount − Discount Amount

The actual tax rate, discount rules, and any additional charges will follow the project's agreed requirements.

## Technologies Used

- **Programming Language:** C
- **Data Storage:** File handling in C
- **Development Environments:** Visual Studio Code and/or Code::Blocks
- **Version Control:** Git
- **Code Hosting and Collaboration:** GitHub

## Data Storage

The system will use files to persist application data.

Depending on the final implementation, separate files may be used for:

- Room records
- Guest information
- Reservation records
- Billing and invoice records

The final file formats and names will be documented after implementation.

## Project Status

**Current Status:** Planning and development.

The features described above represent the intended system functionality. Their implementation and testing progress will be updated as development continues.

## Getting Started

### Prerequisites

- A C compiler, such as GCC.
- Visual Studio Code with a suitable C development setup, or Code::Blocks.
- Git, if cloning the repository.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nourinjahantrisha/Hotel-Reservation-Management-System.git
   ```

2. Open the downloaded project folder in your preferred C development environment.
3. Compile the C source files using the instructions provided with the implemented source code.
4. Run the compiled application.

**Note:** Build and execution instructions will be updated as the project implementation progresses.

## Testing Plan

The system will be tested against scenarios such as:

- Searching for an available room.
- Attempting to book an unavailable room.
- Booking and cancelling a reservation.
- Checking whether room availability is updated correctly.
- Calculating bills for different stay durations.
- Applying valid taxes and discounts.
- Saving and retrieving records from files.
- Generating an invoice with correct billing details.

Testing results will be documented as these features are implemented.

## Project Team

| Role | Name | GitHub |
|---|---|---|
| Team Leader | Nourin Jahan Trisha | [GitHub Profile](https://github.com/nourinjahantrisha) |
| Team Member | Khalid Bhuiyan | [GitHub Profile](https://github.com/khalidbhuiyan12) |
| Team Member | Nusrat Jahan Rafi | [GitHub Profile](https://github.com/Nusrat-JR) |
| Team Member | Md. Humayun Kabir Anik | [GitHub Profile](https://github.com/kabiranik) |
| Team Member | Jubair Sadid Karim | [GitHub Profile](https://github.com/karim0174) |

## Course Instructor

**Instructor:** [Mehedi H. Faysal](https://github.com/MahdiBuilds)  
**Department:** Software Engineering  
**Institution:** Daffodil International University

## Academic Purpose

This project is developed for academic purposes as part of the Software Engineering capstone project at Daffodil International University.

The project is intended to apply C programming, file handling, problem-solving, software design, testing, and collaborative development practices to a practical reservation management scenario.
