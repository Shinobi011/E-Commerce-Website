# MERN E-Commerce Application

This project is a full-fledged **E-Commerce Platform** developed using the **MERN stack** (MongoDB, Express, React, Node.js). It demonstrates essential e-commerce functionalities including product listings, cart management, order tracking, and user authentication.

## Features

- User authentication (JWT-based)
- Admin panel for managing products, users, and orders
- Payment integration using Stripe
- Product search, filtering, and pagination
- User profiles with order history
- Secure storage of user passwords with bcrypt
- Cloudinary integration for product image storage
- Responsive design for mobile and desktop screens

## Prerequisites

To run this project, ensure you have the following installed on your machine:

- Node.js
- MongoDB

## Getting Started

Follow these steps to set up the project locally:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/mern-ecommerce-app.git
   cd mern-ecommerce-app

2. **Install dependencies:**
   **For the backend:**
      - npm install
   **For the frontend:**
      - cd frontend
        npm install 
3. **Set up environment variables:**
   Create a config.env file in the backend/config directory with the following variables:

PORT=5000
DB_URI=your_mongodb_uri
STRIPE_API_KEY=your_stripe_api_key
STRIPE_SECRET_KEY=your_stripe_secret_key
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=7d
COOKIE_EXPIRE=7
SMTP_SERVICE=gmail
SMTP_MAIL=your_email@gmail.com
SMTP_PASSWORD=your_smtp_password
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret

4. **Run the application**
   In the root directory, run
   - npm run dev

   The backend will start on http://localhost:5000 and the frontend on http://localhost:3000.

5. **Technologies Used**

    Frontend: React, Redux, Bootstrap
    Backend: Node.js, Express.js
    Database: MongoDB
    Authentication: JWT (JSON Web Tokens)
    Payment Gateway: Stripe
    File Storage: Cloudinary
