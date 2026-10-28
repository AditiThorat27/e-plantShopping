# e-plantShopping

**Project name:** Paradise Nursery Shopping Application

## Overview

e-plantShopping is a shopping cart web application for an online plant shop called Paradise Nursery. Users can browse a range of house plants, add them to a cart, and manage the quantities before checkout. It is built with React and Redux Toolkit.

## Features

- **Landing page** with a "Get Started" button that links to the product listing page
- **Navigation bar** with links to the landing page, the plant listing page and the shopping cart, plus a cart icon showing the total number of items
- **Product listing page** with plants grouped into categories (for example Aromatic Plants, Medicinal Plants), each shown as a card with image, name, description, price and an "Add to Cart" button
- **Shopping cart page** with a card for every plant type in the cart showing:
  - thumbnail, name and unit cost
  - total cost for that plant type
  - buttons to increase and decrease the quantity
  - a Delete button
- **Cart summary** showing the total cost, with "Continue Shopping" and "Checkout" buttons
- **Dynamic updates:** the navbar cart count and cart totals update as quantities change

## Tech Stack

- React (functional components, `useState` and `useEffect` hooks)
- Redux Toolkit (store, slice, actions and reducers)
- JavaScript (JSX), CSS
- Vite

## Project Structure

```
e-plantShopping/
├── src/
│   ├── App.jsx            # Main app and page switching
│   ├── App.css            # Global styles
│   ├── AboutUs.jsx        # About Us component
│   ├── ProductList.jsx    # Plant listing page and navbar
│   ├── CartItem.jsx       # Shopping cart page
│   ├── CartSlice.jsx      # Redux slice (add, remove, update quantity)
│   └── store.js           # Redux store
├── package.json
└── README.md
```

## Getting Started

```bash
git clone https://github.com/<your-username>/e-plantShopping.git
cd e-plantShopping
npm install
npm run preview
```

The app runs on port 4173 (`npm run dev` can be used during development).

## Author

Built as the final project for the React / Redux course.
