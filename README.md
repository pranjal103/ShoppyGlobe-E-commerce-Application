# ShoppyGlobe E-commerce Application
ShoppyGlobe is a modern e-commerce application built using React and Redux. It allows users to browse products, add them to the cart, and manage their purchases efficiently.

## Description
This application allows users to browse products, view product details, add items to their cart and wishlist, and also perform checkout. It's built using React with Vite, React Router for navigation, and Redux for managing application state and other tools.

## Features
-   Home page displaying a list of products.
-   Product detail pages.
-   Cart functionality using Redux to manage cart items, including adding, 
    removing, and updating quantities.
-   Wishlist functionality using Redux to manage wishlist items, including 
    adding and removing products.
-   Error handling for API calls.
-   Lazy loading using Suspense.

## Prerequisites
Make sure you have the following installed:

- Node.js (v16 or higher recommended)
- npm or yarn package manager

steps:
1) Install dependencies
         npm install
        # or using yarn
          yarn install

2) Run the application
          npm run dev
        # or using yarn
         yarn dev


## Project Structure

ShoppyGlobe-Ecommerce-Application
│── src
│   │── components  # Reusable components
│   │── pages       # Application pages
│   │── store       # Redux store setup
│   │── assets      # Static assets
│   ├── App.js      # Main application file
│   ├── index.js    # Entry point
│── public         # Public assets
│── package.json   # Dependencies and scripts
│── README.md      # Project documentation

## Troubleshooting

Common Issues

- Duplicate React Import Error
 Ensure you are not importing React multiple times in the same file.
 Check your imports and remove duplicate import React from "react".

- Module Not Found Error
 Run npm install to ensure all dependencies are installed.

- Port Already in Use
 Run npx kill-port 5173 and restart the server.

Github link:https://github.com/pranjal103/ShoppyGlobe-E-commerce-Application.git
