💎 Jewellery Management System — React + Vite + Node.js + MongoDB

A full-stack Jewellery Management System built with React + Vite on the frontend and Node.js + Express + MongoDB on the backend.
This system helps manage jewellery products, categories, stock, customers, sales, and admin operations.

Tech Stack

Frontend:
  React (UI)
  Vite (Fast bundler with HMR)
  Tailwind CSS / Bootstrap (optional)
  Axios / Fetch API for backend communication
  
Backend:
  Node.js
  Express.js
  JWT Authentication
  Bcrypt for password hashing
Database:

  MongoDB (NoSQL database)
  Mongoose (ODM for modeling schema)

Main Features::

Admin Panel:
    Add / Edit / Delete Jewellery Products
    Manage Categories (Gold, Diamond, Silver, Platinum etc.)
    Upload product images
    Track inventory and stock levels
    View sales history
    Generate reports (Daily / Weekly / Monthly)

User Panel:
    Browse jewellery items
    Search & Filter
    Add to Cart
    Purchase / Checkout
    User Authentication (JWT-based)

Database (MongoDB) Features:
    Jewellery Product Schema
    Category Schema
    User Schema
    Orders / Sales Schema
    Images stored via:
        Cloudinary (recommended)
        Or locally in server
