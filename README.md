# shopping-cart
simple vegetable shopping app 
# 🥕 Vegetable Shopping App

A simple Vegetable Shopping App built using React and the `useReducer` Hook.

## Features

- Add vegetables to cart
- Increase quantity
- Decrease quantity
- Remove individual items
- Clear entire cart
- Calculate total items
- Calculate total price
- State management using `useReducer`

## Technologies Used

- React
- JavaScript (ES6+)
- useReducer Hook
- JSX
- CSS (Inline Styling)

## Available Vegetables

- 🍅 Tomato
- 🥔 Potato
- 🧅 Onion
- 🥕 Carrot
- 🫘 Beans

## Project Structure

```text
src/
│
├── App.jsx
└── main.jsx
```

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/vegetable-shopping-app.git
```

2. Navigate to the project folder

```bash
cd vegetable-shopping-app
```

3. Install dependencies

```bash
npm install
```

4. Start the development server

```bash
npm run dev
```

## How It Works

### Add Item

```js
dispatch({
  type: "ADD_TO_CART",
  payload: veg,
});
```

### Increase Quantity

```js
dispatch({
  type: "INCREMENT",
  payload: item.id,
});
```

### Decrease Quantity

```js
dispatch({
  type: "DECREMENT",
  payload: item.id,
});
```

### Remove Item

```js
dispatch({
  type: "REMOVE",
  payload: item.id,
});
```

### Clear Cart

```js
dispatch({
  type: "CLEAR_CART",
});
```

## Learning Concepts

This project demonstrates:

- React Hooks
- useReducer
- State Management
- Arrays and Objects
- map()
- filter()
- find()
- reduce()
- Conditional Rendering
- Event Handling

## Author

Ezhil Kumar

## License

This project is open source and available under the MIT License.
