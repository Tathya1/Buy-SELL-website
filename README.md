# IIIT Buy-Sell Website

## Project Overview
This is an exclusive Buy-Sell web application designed for the IIIT community. The platform provides as a marketplace while avoiding the new Whatscap taxation policy on community trade groups.

## Tech Stack
- **Frontend**: React
- **Backend**: Express.js
- **Database**: MongoDB
- **Runtime**: Node.js

## Features

### Authentication
- JWT-based authentication system
- Persistent login sessions
- User registration with IIIT email verification
- Secure password storage using hashing
- Google Recaptcha integration
- CAS Login support

### User Functionality
- Manage user profiles
- Search and filter items efficiently
- Add items to the cart
- Place and track orders
- View order history
- Leave and manage seller reviews

## Key Pages

### Dashboard
- Displays user profile and navigation to all main sections

### Search Items
- Case-insensitive search functionality
- Category-based filtering
- Quick preview of item details

### Individual Item Page
- Shows a detailed description of the item
- Add-to-cart functionality

### Orders History
- View pending orders with OTP verification
- Access purchase history
- Check sales history

### Deliver Items
- Track orders as a seller
- Complete transactions using OTP-based verification

### My Cart
- Manage added items
- View total cost calculations
- Place orders with ease

### Support (Bonus Feature)
- AI-powered chatbot for assistance
- Session-based conversation tracking

## Prerequisites
- Node.js installed
- MongoDB database setup
- npm installed
- ChakraUI installed

## Environment Variables
Create a `.env` file in the backend directory and configure the following:
- MongoDB connection string
- JWT Secret Key
- Recaptcha API keys 
- AI Chatbot API keys 

## Security Measures
- Secure password storage with bcrypt hashing
- JWT-based route protection
- IIIT email validation for account creation
- OTP verification for secure transactions

## Bonus Features
- Google Recaptcha for bot protection
- CAS Login for IIIT authentication
- AI Support Chatbot for user assistance

## Assumptions
- Users can leave unlimited reviews for each product
- Users must remember their OTP when placing an order or regenerate it if needed

## How to Run
1. Install dependencies:
   ```sh
   npm install

2. Navigate to the backend folder:
  cd backend
  npm run dev

3. Navigate to the frontend folder:
  cd frontend
  npm run dev