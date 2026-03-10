# Counter Application using React (useState)

## Overview
This project is a simple Counter Application built using **React** and **Vite**.  
The application displays a number on the screen and allows the user to increase or decrease the value using buttons.

The project demonstrates basic React concepts such as **Functional Components**, **State Management using useState**, and **Event Handling**.

---

## Task Description
Create a React Counter Application that:

- Displays a number on the screen
- Has two buttons: **Increment** and **Decrement**
- Updates the number when buttons are clicked

---

## Project Structure
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
