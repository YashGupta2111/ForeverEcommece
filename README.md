# Forever E-commerce Website

## Overview
Forever is a modern e-commerce website designed to provide a seamless online shopping experience. It features a user-friendly interface, secure payment gateways, and a dynamic product catalog. This project is built using the MERN (MongoDB, Express.js, React, Node.js) stack.

## Features
- **User Authentication**: Secure login and signup using JWT authentication.
- **Product Management**: Browse, search, and filter products easily.
- **Shopping Cart**: Add, update, and remove products from the cart.
- **Checkout & Payment**: Secure payment integration with Stripe.
- **Admin Panel**: Manage users, orders, and products.
- **Responsive Design**: Optimized for both mobile and desktop devices.

## Tech Stack
- **Frontend**: React.js, Redux, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: JSON Web Token (JWT)
- **Payment Gateway**: Stripe API

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js (>=14.x)
- MongoDB

### Steps to Run Locally
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/forever-ecommerce.git
   cd forever-ecommerce
   ```
2. **Install dependencies:**
   ```bash
   npm install
   cd client && npm install
   ```
3. **Set up environment variables:**
   Create a `.env` file in the root directory and add:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```
4. **Run the development server:**
   ```bash
   npm run dev
   ```
   This will start both the frontend and backend servers.

## Usage
- Visit `http://localhost:3000` to access the website.
- Sign up or log in to start shopping.
- Add items to the cart and proceed to checkout.

## Deployment
For production deployment:
- Use **Vercel** or **Netlify** for frontend hosting.
- Deploy backend on **Heroku** or **Render**.
- Configure environment variables in the respective platforms.

## Contributing
Feel free to contribute by submitting issues or pull requests.

## License
This project is licensed under the MIT License.

## Contact
For any queries, reach out to [your-email@example.com].

