# Agile Board - Kanban Task Management App

Welcome to the Task Management System project! This application allows users to manage tasks across different boards and statuses, providing a dynamic and interactive user interface.

## Overview

The Task Management System is built using HTML, CSS, and JavaScript. It utilizes localStorage for data persistence within the browser, allowing users to add, edit, and delete tasks across various boards and statuses.The application is designed to be easy to use and intuitive, with a clean and modern user interface that is responsive to different screen sizes.

## Features

- **Task Management**: Add, edit, and delete tasks within specific boards and statuses.

- **Dynamic UI**: Real-time updates to the user interface based on user interactions.

- **Data Persistence**: Data is stored locally using localStorage, ensuring tasks are retained between sessions.

### Installation

1. Clone the repository to your local machine:
   [git clone](https://github.com/mariusmokoka/JSL_Portfolio_Piece_BOIMOK510_BCL2401_GroupA_Boikhutso-Mokoka_JSL11.git)
2. Open the project folder in Visual Studio Code.
3. Install Live Server extension to run the project locally.
4. Open index.html with Live Server to start the application.

### Project Overview

As a newly hired developer at Agile Board, a fictional company specializing in innovative task management solutions, you'll embark on an exciting journey to enhance their flagship Kanban Task Management App.

### Usage

- **Adding a New Task**:
  - Click the "Add New Task" button to open a modal.
  - Fill in the task details (title, description, status) and click "Save" to add the task.
- **Editing a Task**:
  - Click on an existing task to open the edit modal.
  - Update task details and click "Save Changes" to apply changes.
- **Deleting a Task**:
  - In the edit modal, click "Delete Task" to remove the task from the board

## Project Structure

- **index.html**: Main HTML file for the task management application.
- **style.css**: CSS file for styling the user interface.
- **script.js**: JavaScript file containing application logic and functionalities.

## Code Overview

The project consists of the following components:

- **Task Functions**:
  - **utils/taskFunctions.js**: Helper functions for managing tasks (get, save, create, update, delete).
- **Initial Data**:
  - **initialData.js**: Initial dataset used to populate localStorage if no existing data is found.
- **Functionality**
  - **script.js**: Main JavaScript file implementing task management functionalities.

## Bugs & Fixes

Several bugs have been identified and fixed in the codebase:

- Initialization of localStorage with initialData if no tasks exist.
- Dynamic display of boards and tasks based on stored data.
- Proper filtering and display of tasks by board and status.
- UI updates and event handling for adding, editing, and deleting tasks.

## Challenges

- Challenge: Managing tasks and their associated data (title, description, status) efficiently within localStorage
- Ensuring proper error handling and data validation to prevent invalid inputs and unexpected behaviors.
- Creating a dynamic and responsive user interface that updates in real-time based on user interactions.
- Addressing these challenges requires a combination of technical expertise, problem-solving skills, and a thorough understanding of software development best practices.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please submit a pull request or open an issue on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE)

## Presentation

[Loom Video](https://www.loom.com/share/e6b3363f72b9462d81e8530d36c29000?sid=94183501-5ea9-4fad-9443-c2f149566246)

🚨 Make sure that you clear the localStorage as you are building your project. This will help with checking that the tasks are loading correctly.

![alt text](assets/clear-localStorage.gif)

## Preview of the project:

![alt text](assets/JSL11_solution.gif)

## Author

- [BoikhutsoMokoka](https://github.com/mariusmokoka)

## Acknowledgments

- [CodeSpaceProject](https://github.com/CodeSpace-Academy/JSL_Portfolio_Piece_StudentNo_Classcode_Group_Name-Surname_JSL11)
