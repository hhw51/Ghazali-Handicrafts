# Ghazali Handicrafts E-Commerce Platform

## Overview
Ghazali Handicrafts is an advanced e-commerce platform designed to provide a seamless and secure online shopping experience. Built using the MERN stack (MongoDB, Express, React, Node.js), the platform leverages TypeScript for enhanced code quality, Redis for efficient caching, Cloudinary for media management, BSecure for secure payment processing, Firebase for authentication and real-time database services, and Docker for containerization.

## Key Features

### User Authentication and Authorization
- Secure user registration and login using Firebase Authentication.
- Role-based access control for users and administrators.

### Product Management
- Robust CRUD operations for managing products, categories, and inventory.
- Image uploading and management using Cloudinary.

### Shopping Cart and Order Management
- Dynamic shopping cart with real-time updates.
- Order processing, tracking, and history.

### Payment Integration
- Secure payment processing using BSecure Payment Gateway.
- Multiple payment options and transaction tracking.

### Advanced Search and Filtering
- Comprehensive search functionality with filters for categories, price range, and more.

### Real-time Notifications and Updates
- WebSockets for real-time updates on order status, stock changes, and promotions.

### Caching and Performance Optimization
- Redis for efficient caching and reducing database load.

### Admin Dashboard
- Comprehensive dashboard for managing products, orders, users, and site settings.
- Detailed analytics and reporting tools.

### Responsive Design
- Fully responsive design ensuring seamless experience across all devices.

### Security and Compliance
- Implementation of best security practices including data encryption, secure APIs, and regular security audits.
- Compliance with industry standards and regulations.

## Technology Stack

### Frontend
- **React**: A powerful JavaScript library for building user interfaces.
- **TypeScript**: A statically typed superset of JavaScript to enhance code quality and maintainability.
- **Redux**: State management for React applications.
- **Sass**: CSS preprocessor for styling.

### Backend
- **Node.js**: A JavaScript runtime built on Chrome's V8 engine for scalable network applications.
- **Express**: A minimal and flexible Node.js web application framework.
- **MongoDB**: A NoSQL database for storing and managing data.
- **Redis**: An in-memory data structure store used as a database, cache, and message broker.
- **TypeScript**: Provides static typing to improve code quality.

### Additional Integrations
- **Cloudinary**: Cloud-based image and video management services.
- **BSecure**: A payment gateway for processing secure online transactions.
- **Firebase**: Provides authentication, cloud messaging, and real-time database services.
- **Docker**: Containerization platform for creating, deploying, and running applications in isolated environments.
- **JWT**: JSON Web Tokens for secure user authentication and authorization.

## Getting Started

### Prerequisites
- Node.js
- MongoDB
- Docker (for containerization)
- Cloudinary Account
- Firebase Account
- BSecure Account

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hhw51/Ghazali-Handicrafts.git
   cd Ghazali-Handicrafts

2. Install dependencies:

   ```bash
   npm install

3. Set up environment variables:
Create a .env file in the root directory and add the following:

   ```bash
   MONGO_URI=<your-mongodb-uri>
   CLOUD_NAME=<your-cloudinary-cloud-name>
   CLOUD_API_KEY=<your-cloudinary-api-key>
   CLOUD_API_SECRET=<your-cloudinary-api-secret>
   FIREBASE_API_KEY=<your-firebase-api-key>
   FIREBASE_AUTH_DOMAIN=<your-firebase-auth-domain>
   FIREBASE_PROJECT_ID=<your-firebase-project-id>
   FIREBASE_STORAGE_BUCKET=<your-firebase-storage-bucket>
   FIREBASE_MESSAGING_SENDER_ID=<your-firebase-messaging-sender-id>
   FIREBASE_APP_ID=<your-firebase-app-id>
   BSECURE_API_KEY=<your-bsecure-api-key>
   REDIS_URI=<your-redis-uri>

4. Run the application
   ```bash
   npm run dev
