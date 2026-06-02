# Blood Bank Management System

## Project Overview

The Blood Bank Management System is a full-stack web application designed to manage blood donors, recipients, donations, requests, and transfusions efficiently.

The system includes an analytical Admin Dashboard that provides real-time insights, statistics, and visual reports for effective monitoring and decision-making.

This project is developed using Node.js, Express.js, MongoDB, HTML, CSS, and JavaScript.

---

## Features

### User Module
- Donor Registration and Management
- Recipient Registration and Management
- Blood Donation Recording
- Blood Request Submission and Tracking

### Admin Dashboard
- Donor Analytics (distribution by blood group and gender)
- Donation Analytics (recent donations, expiring units, frequency tracking)
- Recipient Analytics
- Request Analytics (status distribution and fulfillment rate)
- Transfusion Monitoring and Validation
- Blood Group Availability Overview
- Expiry Alerts for Stored Blood
- Interactive Map Integration using Leaflet.js

---

## Technology Stack

### Backend
- Node.js
- Express.js

### Database
- MongoDB (v8.0)
- Mongoose

### Frontend
- HTML5
- CSS3
- JavaScript

### Libraries
- Chart.js (Data Visualization)
- Leaflet.js (Map Integration)

---

## Installation and Setup

1. Clone the repository:
   
2. Navigate to the project folder:
   cd Blood-Bank-Management-System

3. Install dependencies:
   npm install

4. Create a .env file in the root directory and add:
   MONGO_URI=your_mongodb_connection_string
   PORT=3000

5. Start the server:
   node server.js

6. Open in browser:
   http://localhost:3000

---

## Project Structure

BloodBank-Project/
│
├── models/
├── routes/
├── public/
│   ├── admin.html
│   ├── map.html
│   ├── styles.css
│   ├── scripts.js
│
├── server.js
└── README.md

---

## Author
Manal Tariq
