# React + Vite

# E-Commerce App

This is a simple e-commerce web application built using React, Material-UI, Axios, and React Toastify. The app fetches product data from the fake store API (https://fakestoreapi.com/products) and allows users to view products, add them to a shopping cart, and see notifications when items are added or already exist in the cart.

# Features

Fetch product data from an API and display them as product cards.
Add products to the cart and view the number of items in the cart.
Display toast notifications for successful or failed actions (e.g., item added to cart, already in cart).
Modal for displaying cart contents and removing items.
Simple footer with developer credit.

# Technologies Used

React - JavaScript library for building user interfaces.
Material-UI - A popular React UI framework for responsive design.
Axios - Promise-based HTTP client for making API requests.
React Toastify - A library to show toast notifications.
CSS - Styling for the application.

# Installation

Clone the repository:

git clone https://github.com/yourusername/e-commerce-app.git
Navigate into the project directory:

cd e-commerce-app
Install dependencies:

npm install
Run the development server:

npm start
Open your browser and go to http://localhost:3000.

# File Structure

/e-commerce-app
|-- /public
| |-- index.html
|-- /src
| |-- /components
| | |-- Navbar.jsx
| | |-- ProductCard.jsx
| | |-- CartModal.jsx
| |-- App.js
| |-- App.css
| |-- index.js
|-- package.json
|-- README.md

Here's a simple README file for your React application that describes the project, its installation steps, and how to run it:

E-Commerce App
This is a simple e-commerce web application built using React, Material-UI, Axios, and React Toastify. The app fetches product data from the fake store API (https://fakestoreapi.com/products) and allows users to view products, add them to a shopping cart, and see notifications when items are added or already exist in the cart.

Features
Fetch product data from an API and display them as product cards.
Add products to the cart and view the number of items in the cart.
Display toast notifications for successful or failed actions (e.g., item added to cart, already in cart).
Modal for displaying cart contents and removing items.
Simple footer with developer credit.
Technologies Used
React - JavaScript library for building user interfaces.
Material-UI - A popular React UI framework for responsive design.
Axios - Promise-based HTTP client for making API requests.
React Toastify - A library to show toast notifications.
CSS - Styling for the application.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/e-commerce-app.git
Navigate into the project directory:

bash
Copy code
cd e-commerce-app
Install dependencies:

bash
Copy code
npm install
Run the development server:

bash
Copy code
npm start
Open your browser and go to http://localhost:3000.

File Structure
lua
Copy code
/e-commerce-app
|-- /public
| |-- index.html
|-- /src
| |-- /components
| | |-- Navbar.jsx
| | |-- ProductCard.jsx
| | |-- CartModal.jsx
| |-- App.js
| |-- App.css
| |-- index.js
|-- package.json
|-- README.md

# How It Works

1.Product Listing:
Products are fetched from the fake store API (https://fakestoreapi.com/products).
Each product is displayed as a card with details like the product name, price, and image.

2.Add to Cart:
When a user clicks the "Add to Cart" button on a product, it is added to the cart.
If the item is already in the cart, a toast notification informs the user.
The cart is managed using React's useState hook.

3.Toast Notifications:
Success Toast: Shown when an item is successfully added to the cart.
Info Toast: Shown when an item is already in the cart.

4.Cart Modal:
A modal is shown when the user clicks the cart icon in the navbar.
The modal displays the items in the cart with an option to remove items.

5.Footer:
A simple footer at the bottom of the page shows the developer's name.
