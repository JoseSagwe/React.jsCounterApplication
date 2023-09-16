# React.jsCounterApplication

![CounterApp](https://github.com/JoseSagwe/React.jsCounterApplication/assets/110198843/685e064a-7b3e-4384-a275-a2ed3a2e40d3)

# CounterApplication

CounterApplication is a simple React application that allows you to keep track of and manipulate a counter's value. This project consists of a counter component and counter button components, which can be customized to increment and decrement the counter by specific amounts.

## Getting Started

To get started with CounterApplication, follow these steps:

1. Clone the repository to your local machine:

2. Navigate to the project directory:

3. Install the required dependencies:

   ```bash
   npm install
   ```
4. Start the development server:

   ```bash
   npm start
   ```

This will launch the CounterApplication in your browser, allowing you to interact with the counter.
Access the applicatio on localhost:3000


## Usage

The CounterApplication project consists of the following key components:


### `Counter`

The `Counter` component is the main component that displays the counter value and provides buttons for incrementing, decrementing, and resetting the counter.

- `count`: The current value of the counter, which is initially set to 0.
- `incrementCounterParentFunction(by)`: A function to increment the counter by the specified value (`by`).
- `decrementCounterParentFunction(by)`: A function to decrement the counter by the specified value (`by`).
- `reset()`: A function to reset the counter to 0.


### `CounterButton`

The `CounterButton` component is a reusable button component that can be customized to increment or decrement the counter by a specified amount (`by`).

- `by`: The amount by which the counter is incremented or decremented when the button is clicked.
- `incrementMethod`: A callback function provided by the parent component to handle incrementing the counter.
- `decrementMethod`: A callback function provided by the parent component to handle decrementing the counter.

