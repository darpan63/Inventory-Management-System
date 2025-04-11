 
# Inventory Management System (IMS)

An Inventory Management System built with Vite, React.js for the frontend, and Node.js, Express, and MongoDB for the backend.

## Table of Contents

- [Features](#features)
- [Folder Structure](#folder-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Environment Variables](#environment-variables)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization
- Manage products, companies, locations, and brands
- Track product history
- Dashboard with analytics
- Responsive design with Tailwind CSS


## Prerequisites

- Node.js
- npm or yarn
- MongoDB

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Backend Setup:**
   ```bash
   cd Backend
   npm install
   ```

3. **Frontend Setup:**
   ```bash
   cd ../Frontend
   npm install
   ```

## Running the Application

1. **Run Backend:**
   ```bash
   cd Backend
   npm start
   ```

2. **Run Frontend:**
   ```bash
   cd ../Frontend
   npm run dev
   ```

## Environment Variables

Create a `.env` file in the Backend and Frontend directories and configure the following:

### Backend `.env`:
```env
MONGODB_URI=your_mongodb_connection_string
PORT=3000
SECRET_KEY=your_secret_key
NODE_ENV=development
ORIGIN=http://localhost:3000
```

### Frontend `.env`:
```env
VITE_SERVER=https://inventory-management-backend-hsaf.onrender.com
VITE_MODE=PROD
VITE_LOCAL=http://localhost:3000
```
