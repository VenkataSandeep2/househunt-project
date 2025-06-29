# 🏠 HouseHunt: Finding Your Perfect Rental Home

## 📌 Project Overview
**HouseHunt** is a full-stack MERN (MongoDB, Express, React, Node.js) application designed to simplify and streamline the property rental process. This platform caters to three main user types: **Renters**, **Owners**, and **Admins**.

### 👥 User Roles:
- **Renter**: Browses properties, makes booking requests.
- **Owner**: Lists and manages rental properties (requires admin approval).
- **Admin**: Oversees owner approval and ensures platform integrity.

## 🔑 Key Features
-  JWT-based Authentication & Role Management
-  Property Listings with Smart Filters
-  Booking Requests and Status Tracking
-  Owner Dashboard for Property Management
-  Responsive UI with Bootstrap + Material UI

## 📐 Technical Architecture
- **Frontend**: React, Bootstrap, Material UI, Axios
- **Backend**: Node.js, Express.js, MongoDB, JWT
- **Database**: MongoDB (Mongoose ODM)

## 💡 Use Case Scenario
> Alice, a renter, registers and browses apartments. She finds one she likes, sends a booking request. The owner (Bob) is approved by the admin and receives Alice’s request. Once Bob confirms, the lease is negotiated through the app.

## 📁 Folder Structure
```
house-hunt/
├── backend/        # Node + Express API
├── frontend/       # React.js client
├── README.md       # This file
```

## 🧰 Technologies Used
- **Frontend**: React, Bootstrap 5, Material UI
- **Backend**: Express, Node.js
- **Database**: MongoDB + Mongoose
- **Authentication**: JSON Web Tokens (JWT)
