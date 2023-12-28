# Ecommerce-App
Complete mern stack ecommerce project.

## Overview

My eCommerce Website is a fully-featured online store platform built with the MERN (MongoDB, Express.js, React, Node.js) stack. Website provides a seamless shopping experience for customers. Key features include:

- **User Authentication:** Secure user accounts with authentication and authorization functionalities.
- **Product Management:** Easily add, edit, and remove products with detailed information and images.
- **Shopping Cart:** A fully functional shopping cart system for users to add and manage their selected items.
- **Order Processing:** Streamlined order processing, from checkout to payment and confirmation.

The MERN stack ensures a robust and modern architecture, making the platform efficient, scalable, and easy to maintain.

## Technologies Used

- JavaScript
- React
- Node.js
- MongoDB
- Tailwind CSS
- Express.js

  # Setup

## Dependencies

Find all the dependencies in the `package.json` file.

## Code Examples

```bash
# Clone repository
gh repo clone prathamesh-bhujbal/Ecommerce-MERN-Website

# Install all the dependencies
npm install

# Add config.env file in the root directory with the following details
echo "DATABASE=mongodb+srv://<username>:<password>@cluster0.qu8zntg.mongodb.net/SamarthLab" >> config.env
echo "SECRET_KEY=<your secret key>" >> config.env

# Start the server in the root directory
npm start

# Start frontend in the client directory
cd client
npm start
