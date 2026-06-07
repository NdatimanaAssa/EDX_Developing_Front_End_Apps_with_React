# E-Commerce App with Redux Toolkit

## Overview
A React e-commerce application that uses Redux Toolkit (RTK) for global state management. Users can add products to a cart, adjust quantities, remove items, and see the total amount.

## What I Learned

### Redux Toolkit (RTK)
- Setting up a global store using `configureStore`
- Creating a slice with `createSlice` to define initial state and reducers together
- Exporting action creators and the reducer from a slice

### useSelector & useDispatch
- Reading global state from the Redux store using `useSelector`
- Dispatching actions to update state using `useDispatch`

### Cart Logic
- Adding a product only once and disabling the button after it is added
- Increasing and decreasing item quantity in the cart
- Removing a single item or clearing the entire cart
- Calculating the total amount dynamically using `Array.reduce()`

## Features
- Product list with Add to Cart button (disabled once added)
- Shopping cart with quantity controls (+/-)
- Remove individual items
- Clear entire cart
- Total amount display

## Technologies
- React 18
- Redux Toolkit
- Vite
- CSS

---
**Author:** Ndatimana Assa
