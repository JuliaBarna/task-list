# Task-List Application

## Description
The **Task-List Application** is a React-based project designed for managing tasks efficiently. It demonstrates best practices in handling dynamic components and array manipulations using modern React techniques like `map` and `filter`. The app is lightweight, responsive, and easy to use.

## Features
- Add, edit, and delete tasks.
- Dynamic rendering of task lists.
- Unique task identification using UUID (Universally Unique Identifier).

## Key Development Guidelines

### 1. Array Manipulation
- Use the `map` method to render the list of tasks dynamically.
- Apply the `filter` method for managing task removal or filtering based on conditions.

### 2. Avoid Indexes as Keys
- Do **not** use array indexes as the `key` attribute for dynamically created reusable components. Using indexes can lead to performance issues and incorrect UI updates.

### 3. Unique Identifiers with UUID
- Use the `uuid` library to generate unique identifiers for each task.
- UUIDs ensure that every task has a globally unique identifier, making it ideal for React components' `key` attributes.

#### Example UUID:
```
d29e9b42-9b97-ab6f-bc0c-2c3f938d10e4
```

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

#### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However, we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/task-list.git
   ```
2. Navigate to the project directory:
   ```bash
   cd task-list
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Usage
1. Start the development server:
   ```bash
   npm start
   ```
2. Open the app in your browser at `http://localhost:3000`.

## Dependencies
- React
- uuid: For generating unique identifiers







