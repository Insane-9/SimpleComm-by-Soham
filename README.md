# SimpleComm - E-Commerce Platform

A full-stack e-commerce application built with Node.js, Express, MongoDB, and React/Vite.

## Quick Setup

### Prerequisites

- Node.js (v18+)
- MongoDB
- npm

### Installation & Running

#### Backend Setup

```bash
cd backend
npm install
npm run dev
```

Backend will run on `http://localhost:5001`

#### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend will run on `http://localhost:5173`

## Features

### User Features

- User Authentication (Signup/Login)
- Browse Products
- Add/Remove Items from Cart
- Update Cart Quantities
- Manage Delivery Addresses
- Place Orders (COD)
- Order Success Confirmation

### Admin Features

- Access Admin Panel at `/admin/products`
- Add New Products
- Edit Existing Products
- View Product List
- Delete Products

## Environment Variables

Create a `.env` file in the `backend` folder with:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```