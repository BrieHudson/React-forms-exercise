# React-forms-exercise

React Project: Color Box Maker & Todo App

This project is a combination of two small applications built with React: a Color Box Maker and a Todo App. Both apps demonstrate the use of React components, state management, and handling user inputs to add, remove, and display content dynamically.

Description

Part 1 - Color Box Maker
In this part of the project, a Color Box Maker allows users to create color boxes with custom dimensions and colors. The application lets the user input the box's width, height, and background color, and display it on the page. Each box also has a button to delete it.

- App: Renders the BoxList component.
- BoxList: Manages the state of the boxes and renders both the Box components and the NewBoxForm component.
- Box: Displays a box with a specified background color, width, and height, and includes a button to delete it.
- NewBoxForm: Allows users to input width, height, and background color for a new box. After submitting the form, a new box is created and the input fields are cleared.

Part 2 - Todo App
The Todo App lets users add and remove tasks. Each task is displayed in a list, and users can remove individual tasks with an “X” button.

- App: Renders the TodoList component.
- TodoList: Manages the state of all todos and renders the NewTodoForm for adding new tasks.
- NewTodoForm: A form with an input field to add a new todo task.
- Todo: Displays the todo task with a button to delete it.

Technologies Used

- React: For creating dynamic components.
- JavaScript (ES6): For application logic and state management.
- CSS: For styling the components.

Installation

1. clone the repository
2. navigate to project directory
3. install dependencies
   npm install
4. start the server
   npm start
5. Navigate the specified server in terminal

Usage

Using Color Box Maker
1. Enter the dimensions (width and height) and background color in the form.
2. Click the "Submit" button to create a new color box.
3. Each box will have an "X" button that you can click to delete the box.

Using Todo App
1. Enter a task in the input field and click "Add Todo."
2. The task will appear in the list of todos.
3. Click the "X" button next to a todo to remove it from the list.
