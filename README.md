# Medical Information Management System

## Overview
This project is designed to manage user medical information securely and efficiently, allowing users and medical professionals to access necessary data based on permissions. Key features include mapping of medical facilities, prescription tracking, appointment scheduling, and detailed access to medical information.

## Features

### Permissions
- Configurable access to user information.
- Access can require approval from the user, their doctor, or emergency contact.
- Access is limited based on role (e.g., general practitioners, pharmacists, EMTs).

### Maps
- Integration with Google Maps API or other Map APIs.
- Displays relevant medical facilities.

### Prescription Tracking
- Alerts for when prescriptions are ready.
- Ability to order prescriptions from participating pharmacies.

### Appointments
- Schedule appointments with pharmacies, hospitals, and clinics.
- Integration with Google Calendar API for appointment tracking.

### Access to Information
- Users have access to all their medical information.
- Doctors can access user history and family history with permission.

## Tech Stack
- HTML
- CSS
- JavaScript
- MySQL

## Installation

To install and run this project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/PMwelase/MedicalDB.git

# Navigate to the project directory
cd MedicalDB

# Install dependencies
npm install

# Start the application
npm start
