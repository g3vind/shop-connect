# Shop Connect - MERN Stack Multi-Vendor Ecommerce Website

This project is a full-stack MERN (MongoDB, Express, React, Node.js) application designed for a multi-vendor ecommerce platform. This platform enables users to buy products from various vendors as well as become sellers themselves. It also offers real-time chat functionality between buyers and sellers through Socket.IO. The authentication system employs Nodemailer SMTP with Gmail to send email verification links for login and signup. Additionally, the platform supports payment through Stripe, with options to pay via PayPal or debit card. Users can also apply coupon codes for discounts on their purchases. For administrators, there is a dashboard to manage orders and products.

## Features

- **Multi-Vendor**: Users can buy products from multiple vendors or become vendors themselves.
- **Real-Time Chat**: Buyers can chat with sellers in real-time using Socket.IO.
- **Email Verification**: Nodemailer SMTP with Gmail is used for secure email verification during login and signup.
- **Payment Integration**: Stripe integration allows for payments via PayPal or debit card.
- **Coupon Codes**: Users can apply coupon codes for discounts on their purchases.
- **Admin Dashboard**: Administrators have access to a dashboard to manage orders and products.

## Technologies Used

### Backend

- **Express.js**: Web application framework for Node.js
- **Socket.IO**: Library for real-time bidirectional event-based communication
- **Nodemailer**: Email sending library
- **Stripe**: Payment processing platform
- **bcrypt/bcryptjs**: Library for hashing passwords
- **mongoose**: MongoDB object modeling tool
- **cloudinary**: Image and video management API

### Frontend

- **React**: Frontend library for building the user interface
- **Redux**: State management library
- **Material-UI**: React components for faster and easier web development
- **axios**: Promise based HTTP client for the browser and Node.js

## Getting Started

1. **Clone the repository**: `git clone https://github.com/g3vind/shop-connect.git`
2. **Install dependencies**: `cd shop-connect` then `npm install` in both the root and `client` directories.
3. **Set up environment variables**: Create a `.env` file in the root directory with the following variables:
   - `MONGO_URI`: MongoDB connection string
   - `JWT_SECRET`: Secret key for JSON Web Tokens
   - `EMAIL`: Gmail account for Nodemailer SMTP
   - `PASSWORD`: Password for the Gmail account
   - `STRIPE_SECRET_KEY`: Stripe secret key
   - `PAYPAL_CLIENT_ID`: PayPal client ID
4. **Run the app**: `npm run dev` in the root directory.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, feel free to submit a pull request.
