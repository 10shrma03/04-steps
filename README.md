# Steps - React Mini Project

Steps is a simple React application that guides the user through a series of steps with messages. This project demonstrates the use of React hooks, state management, and conditional rendering.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Key Concepts](#key-concepts)
- [App.js Code](#appjs-code)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Steps application allows users to navigate through three steps, each with a specific message. Users can go to the previous or next step using navigation buttons.

## Features

- Step-by-step navigation
- Conditional rendering of steps
- Simple and intuitive user interface

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/steps.git
```
2. Navigate to the project directory:
   ```sh
   cd fast-react-pizza-co
   ```
3. Install the dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
    npm start
   ```
## Usage

Once the development server is running, open your browser and navigate to `http://localhost:3000` to see the application in action.

 ## Technologies Used

- **HTML**: For structuring the web pages.
- **CSS**: For styling the application.
- **JavaScript**: For adding interactivity.
- **React**: For building the user interface.
- **Create React App**: For setting up the React project.

## Key Concepts

### React Hooks

The project uses `useState` to manage the state of the current step and the visibility of the steps component.

### State Management

Two pieces of state are managed:
- `step`: Tracks the current step (1, 2, or 3).
- `isOpen`: Tracks whether the steps component is visible.

### Conditional Rendering

The application conditionally renders the steps component based on the `isOpen` state. It also highlights the current step based on the `step` state.

### Event Handling

Two functions handle the navigation between steps:
- `handlePrevious`: Decreases the step count by 1, ensuring it doesn't go below 1.
- `handleNext`: Increases the step count by 1, ensuring it doesn't exceed 3.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.
