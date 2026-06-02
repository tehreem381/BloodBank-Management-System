# Blood Bank Management System

## Overview

The Blood Bank Management System is a web-based application developed to streamline the management of blood donations, donor records, recipient information, blood requests, and transfusion processes. The system provides an efficient platform for maintaining blood inventory while ensuring accurate tracking of donations and requests.

In addition to operational management, the application includes a comprehensive analytics dashboard that offers real-time insights into blood availability, donor activities, request fulfillment, and other critical statistics. These analytical features support administrators in making informed decisions and maintaining an effective blood supply network.

---

## Key Features

### Donor Management

* Register and manage donor information
* Maintain donor profiles and donation history
* Track donor eligibility for future donations

### Recipient Management

* Register and manage recipient records
* Store recipient details securely
* Monitor blood request activities

### Blood Donation Management

* Record blood donations
* Monitor donation dates and blood quantities
* Track blood unit expiration dates

### Blood Request Handling

* Submit and manage blood requests
* Monitor request status and fulfillment progress
* Validate blood group compatibility

### Transfusion Monitoring

* Record transfusion details
* Ensure donor-recipient compatibility checks
* Maintain transfusion history

### Administrative Analytics Dashboard

* Blood group distribution analysis
* Donor demographic insights
* Donation trends and activity reports
* Blood inventory monitoring
* Request fulfillment statistics
* Expiry alerts for stored blood units
* Real-time system statistics

### Location-Based Services

* Interactive donor location visualization using Leaflet.js
* Geographic representation of donor data

---

## Technology Stack

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose ODM

### Frontend

* HTML5
* CSS3
* JavaScript

### Additional Libraries

* Chart.js (Data Visualization)
* Leaflet.js (Interactive Maps)

---

## Installation Guide

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Navigate to Project Directory

```bash
cd Blood-Bank-Management-System
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the project root and add:

```env
MONGO_URI=your_mongodb_connection_string
PORT=3000
```

### 5. Start the Application

```bash
node server.js
```

### 6. Access the Application

Open your browser and visit:

```text
http://localhost:3000
```

---

## Project Structure

```text
BloodBank-Project/
│
├── models/
├── routes/
├── public/
│   ├── admin.html
│   ├── map.html
│   ├── styles.css
│   └── scripts.js
│
├── server.js
├── package.json
└── README.md
```

---

## Future Enhancements

* Email and SMS notifications
* Advanced donor eligibility verification
* Hospital integration support
* Blood demand prediction using analytics
* Mobile application support

---

## Author

Tehreem Amjad

This project was developed as part of an academic full-stack web development project to demonstrate the implementation of database management, analytics, and web application development concepts.
