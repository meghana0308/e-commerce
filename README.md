# E-Commerce Website

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Configuration](#configuration)
7. [Contact](#contact)

## Introduction
Welcome to our E-Commerce Website project! This project is designed to provide a robust, scalable, and customizable platform for online retail. It supports various features essential for a modern e-commerce experience, including user authentication, product management, and more.

## Features
- User Authentication and Authorization
- Product Management (CRUD)
- Shopping Cart and Checkout
- Responsive Design
- Admin Dashboard
- Search and Filtering
- Wishlist

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript, React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)

## Installation
Follow these steps to get a local copy up and running.

### Prerequisites
- Node.js (v14.x or higher)
- npm (v6.x or higher) or yarn
- MongoDB

### Steps
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/ecommerce-website.git
    cd ecommerce-website
    ```

2. **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

3. **Set up environment variables:**
    Create a `.env` file in the root directory and add the following:
    ```env
    NODE_ENV=development
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. **Run the application:**
    ```bash
    npm run dev
    # or
    yarn dev
    ```

5. **Access the application:**
    Open your browser and go to `http://localhost:5000`

## Usage
Once the application is running, you can:
- Register and log in as a user
- Browse products, add them to the cart, and proceed to checkout
- Manage your account and orders
- If logged in as an admin, manage products, orders, and users from the admin dashboard

## Configuration
Additional configuration options can be managed through the `.env` file and other configuration files within the project.

## Contact
For any questions, please contact:
**Meghana:** meghanavjiet@gmail.com
