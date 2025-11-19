# 🧾💰 Utility Bill Management System

**Bill Management System-Backend** The Jumerirah Apartments utility bill management system allows users to manage and pay their utility bills.

---
<h1 align = "left">Project Overview</h1>
<p>Bill Management System (Backend) The Jumerirah Apartments utility bill management system backend provides APIs that allow users to manage their utility bills securely using CRUD operations. </p>

<img width="941" height="903" alt="Screenshot 2025-11-19 at 1 14 17 AM" src="https://github.com/user-attachments/assets/7b64eb59-f48b-4ea9-8f44-f4213d3da365" />

## 📌  Description
This backend application is built with Node.js and Express and uses MongoDB as the database. It allows users to browse bills, pay bills, and manage user-specific bill records.

<h1>APIs are designed for handling CRUD operations efficiently:</h1>
<ul>
  <li>Browse bills with optional filtering by category or limit</li>
  <li>Retrieve bill details by ID</li>
  <li>Add user-specific bill records (pay bills)</li>
  <li>Update bill information</li>
  <li>Delete bill records</li>
</ul>

<h1>The backend is designed to be easily integrated with frontend frameworks and supports secure, user-specific bill management.</h1>

<h1 align="left">Key Features</h1>
<ul>
  <li>CRUD operations for all utility bills</li>
  <li>User-specific bill management</li>
  <li>Secure and scalable backend API for integration with frontend apps</li>
</ul>

<h1 align="left">Bills Collection APIs</h1>
<ul>
  <li>GET /bills - Retrieve all bills, optionally filtered by category or limited by limit.</li>
  <li>GET /bills/:id - Retrieve details of a specific bill by ID.</li>
</ul>

<h1 align="left">MyBills Collection APIs (User-Specific)</h1>
<ul>
  <li>POST /mybills - Add a bill record for a user (pay a bill).</li>
  <li>GET /mybills - Retrieve all bills associated with a user (filter by email).</li>
  <li>PATCH /mybills/:id - Update a specific user bill.</li>
  <li>DELETE /mybills/:id - Delete a specific user bill by ID.</li>
</ul>


## 🛠 Tech Stack & Tools

- **Backend**:  Node.js, Express
- **DataBase**: MongoDB
- **Environment Management**: React Router
- **MIDDLEWARE**: CORS, express.json()
- **Deployment**: Vercel 
- **npm packages**:express, cors, dotenv, mongodb

<h1 align = "left">Live Link and preview this application on your device</h1>
<h3>#Clone the repository:</h3>
<h3>git clone:https://github.com/TCahnaf/Utility-Bill-Management-System-Server.git </h3>
<h3>Live Link:</h3>
<h3> https://ph-assignment10-server-livid.vercel.app// </h3>
