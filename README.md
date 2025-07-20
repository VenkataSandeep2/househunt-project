
# 🏠 HouseHunt: Finding Your Perfect Rental Home

HouseHunt is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application designed to simplify and streamline the property rental process. It connects **Renters**, **Owners**, and **Admins** in a centralized platform, making it easy to list, search, book, and manage rental properties.

---

## 📌 Project Overview

This application caters to three primary user roles:

- **👤 Renter**: Browses available properties and sends booking requests.
- **🏠 Owner**: Lists and manages rental properties (requires admin approval).
- **🛡️ Admin**: Verifies and approves property owners, manages listings, and ensures platform security.

---

## 🔑 Key Features

- 🔐 JWT-based Authentication & Role-Based Access Control
- 🏘️ Property Listings with Advanced Search Filters
- 📆 Booking Requests with Status Tracking
- 📊 Owner Dashboard to Manage Properties and Bookings
- 📱 Responsive UI using Bootstrap and Material UI
- 🧾 Lease Agreement Flow (conceptual support)

---

## 📐 Technical Architecture

| Layer         | Technology |
|---------------|------------|
| **Frontend**  | React, Axios, Bootstrap 5, Material UI |
| **Backend**   | Node.js, Express.js |
| **Database**  | MongoDB (Mongoose ODM) |
| **Auth**      | JWT (JSON Web Tokens) |

---

## 💡 Use Case Scenario

> *Alice*, a renter, signs up and explores listed apartments. She finds a suitable place and submits a booking request. *Bob*, the property owner (approved by the admin), receives Alice’s request and confirms it. They proceed to lease agreement discussion — all managed within the HouseHunt app.

---

## 📁 Folder Structure

house-hunt/
├── backend/ # Express.js server-side code
│ ├── controllers/ # Logic for each route
│ ├── models/ # Mongoose schemas
│ ├── routes/ # API routes
│ ├── middleware/ # Authentication, validation
│ └── server.js # Entry point
│
├── frontend/ # React.js client-side code
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Login, Home, Dashboard, etc.
│ │ ├── api/ # Axios calls
│ │ ├── context/ # Auth context
│ │ └── App.js
│ └── public/
│
├── .env # Environment variables
├── README.md # Project documentation

## 🧰 Technologies Used

### 🔷 Frontend
- React.js
- Bootstrap 5
- Material UI
- Axios

### 🔶 Backend
- Node.js
- Express.js
- JWT (Authentication)
- Mongoose (MongoDB ODM)

### 🟩 Database
- MongoDB (Atlas or Local)

---

## 🚀 How to Run Locally

### 🔧 Prerequisites
- Node.js & npm
- MongoDB installed or MongoDB Atlas account

### 🖥 Backend Setup

\`\`\`bash
cd backend
npm install
npm start
\`\`\`

Update your \`.env\` in \`backend/\`:
\`\`\`
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret_key
\`\`\`

### 💻 Frontend Setup

\`\`\`bash
cd frontend
npm install
npm start
\`\`\`

The React app will start at \`http://localhost:3000\`.

---

## 📈 Future Enhancements

- In-app Messaging between Owners and Renters
- Lease Agreement PDF Generator
- Payment Gateway Integration (e.g., Stripe)
- Real-time Notifications
- Google Maps API for Location-based Search

---

## 🤝 Contributors

- Siva Sanjay (Full Stack Developer)

---

## 🙏 Acknowledgments

Special thanks to mentors and guides who supported the successful completion of the **HouseHunt** project. Their mentorship played a key role in shaping and deploying this rental platform.

---
