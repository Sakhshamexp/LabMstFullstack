# React Counter Application (useState)

## Overview
This project is a simple Counter Application built using **React + Vite**. The application displays a number and allows the user to increase or decrease it using buttons. It demonstrates basic React concepts such as functional components, state management, and event handling.

## Task
Create a counter app that:
- Displays a number on the screen
- Has **Increment** and **Decrement** buttons
- Updates the number when the buttons are clicked

## Folder Structure
src
├── components
│ └── Counter.jsx
├── App.jsx
└── main.jsx


## File Description
- **main.jsx** – Entry point that renders the App component to the browser.
- **App.jsx** – Root component that imports and displays the Counter component.
- **Counter.jsx** – Contains the counter logic and UI using the `useState` hook.

## Concepts Used
- React Functional Components  
- `useState` Hook for state management  
- Event Handling using `onClick`

## Logic
The counter value is stored using the `useState` hook with an initial value of **0**. When the **Increment** button is clicked, the value increases by 1. When the **Decrement** button is clicked, the value decreases by 1. Whenever the state changes, React automatically re-renders the component and updates the UI.

## Functionalities
- Increase counter value
- Decrease counter value
- Dynamic UI updates

## Possible Improvements
- Add a **Reset button**
- Add **minimum/maximum value validation**
- Separate UI elements into reusable components
- Improve styling using CSS or frameworks like Tailwind


