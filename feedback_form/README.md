# Feedback Form

## Overview
A React application that collects user feedback through a form, asks for confirmation before submitting, and resets the form after a successful submission.

## What I Learned

### Controlled Forms
- Managing form state with `useState` for `name`, `email`, and `feedback` fields
- Using a single `handleChange` function with computed property names `[name]: value` to update any field dynamically

### Form Submission
- Preventing default form submission with `event.preventDefault()`
- Using `window.confirm()` to ask for user confirmation before submitting
- Resetting form fields after successful submission

### Event Handling
- Handling `onChange` on inputs and textarea
- Handling `onSubmit` on the form element

## Features
- Name, email, and feedback input fields
- Confirmation dialog before submission
- Form resets after successful submission
- Success alert message after submission

## Technologies
- React 18
- Vite
- CSS

---
**Author:** Ndatimana Assa
