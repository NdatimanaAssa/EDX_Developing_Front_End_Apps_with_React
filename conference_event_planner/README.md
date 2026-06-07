# Conference Event Planner

## Overview
A React application for planning conference events. Users can select venue rooms, add-ons, and meals while tracking the total cost using Redux Toolkit for state management.

## What I Learned

### Redux Toolkit with Multiple Slices
- Managing separate state slices for venue, AV add-ons, and meals using `venueSlice`, `avSlice`, and `mealsSlice`
- Configuring a store with multiple reducers using `configureStore`
- Dispatching `incrementQuantity` and `decrementQuantity` actions to update item quantities

### useSelector & useDispatch
- Reading venue items from the Redux store using `useSelector`
- Dispatching quantity actions using `useDispatch`

### Conditional Rendering
- Toggling between the items selection view and the total cost summary view using `showItems` state
- Conditionally applying CSS classes based on item quantity limits

### Component Composition
- Splitting the UI into focused components: `ConferenceEvent`, `TotalCost`, `AboutUs`
- Passing props like `totalCosts` and handler functions between components

### useState with UI Logic
- Using `showItems` to toggle the details panel
- Using `numberOfPeople` to track headcount input

## Features
- Venue room selection with quantity limits (e.g. max 3 Auditorium Halls)
- Add-ons and meals selection sections
- Total cost calculation per section
- Show/hide details panel toggle
- Get Started button to reveal the planner

## Technologies
- React 18
- Redux Toolkit
- Vite
- CSS

---
**Author:** Ndatimana Assa
