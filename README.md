# Components

## What is Components?

**Components** are one of the core concepts of React. They are the foundation upon which you build user interfaces (UI), which makes them the perfect place to start your React journey!

## Defining a component

Traditionally when creating web pages, web developers marked up their content and then added interaction by sprinkling on some JavaScript. This worked great when interaction was a nice-to-have on the web. Now it is expected for many sites and all apps. React puts interactivity first while still using the same technology: a React component is a JavaScript function that you can sprinkle with markup. Here’s what that looks like (you can edit the example below):

```jsx
export default function Profile() {
  return (
    <img
      src="https://i.imgur.com/MK3eW3Am.jpg"
      alt="Katherine Johnson"
    />
  )
}
```
---

## How to build component?

### Step 1: Export the component 

The export default prefix is a standard JavaScript syntax (not specific to React). It lets you mark the main function in a file so that you can later import it from other files. (More on importing in Importing and Exporting Components!)

### Step 2: Define the functio

> With function Profile() { } you define a JavaScript function with the name Profile.

React components are regular JavaScript functions, but their names must start with a capital letter or they won’t work!
---

## Core Concepts of React

### 1. Components
Components are the building blocks of a React application. Each component represents a part of the user interface (e.g., buttons, forms, navigation bars).

Components can be:
- **Functional components**
- **Reusable and independent**

### 2. JSX (JavaScript XML)
JSX is a syntax extension that allows developers to write HTML-like code inside JavaScript.

Example:
```jsx
function Welcome() {
  return <h1>Hello, React!</h1>;
}
```
---

## Author

**John Paul L. Saac**  

---

