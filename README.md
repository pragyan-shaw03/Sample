# Task Management System

TaskQuest is a simple command-line task management application written in Java. It allows users to organize and manage their tasks efficiently. This README file provides an overview of the code structure, classes used, and how to use the application.

## Classes

### Task
The `Task` class represents an individual task with the following attributes:
- `title`: Name or title of the task.
- `category`: Category of the task (e.g., work, personal, etc.).
- `priority`: Priority level of the task (High, Medium, Low).
- `deadline`: Deadline of the task in the format YYYY-MM-DD.
- `completed`: Boolean value indicating whether the task has been completed or not.

#### Methods:
- `getTitle()`: Returns the title of the task.
- `getCategory()`: Returns the category of the task.
- `getPriority()`: Returns the priority level of the task.
- `getDeadline()`: Returns the deadline of the task.
- `isCompleted()`: Returns true if the task is completed, false otherwise.
- `setCompleted(boolean completed)`: Sets the completion status of the task.

### TaskManager
The `TaskManager` class manages a collection of tasks and provides methods to perform operations on them. It contains the following attributes and methods:
- `tasks`: An ArrayList to store Task objects.

#### Methods:
- `addTask(Task task)`: Adds a new task to the task list.
- `completeTask(int index)`: Marks the task at the specified index as completed.
- `displayTasks()`: Displays all tasks along with their details.

### TaskQuest
The `TaskQuest` class contains the main method and serves as the entry point for the application. It provides a command-line interface for users to interact with the TaskManager and perform various actions such as viewing tasks, completing tasks, and adding new tasks.

## How to Use
To use the TaskQuest application, follow these steps:
1. Compile the `TaskQuest.java` file using a Java compiler (`javac TaskQuest.java`).
2. Run the compiled program (`java TaskQuest`).
3. Follow the on-screen instructions to perform various tasks such as viewing, completing, and adding tasks.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

