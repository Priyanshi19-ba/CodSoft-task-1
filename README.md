Name: Priyanshi Bansal 
Company: CodSoft 
Batch: B33
Duration: 10 June 2025 - 10 July 2025
Domain : Python Programmig 
**Overview of the project**
Project: A To-Do List Application Developed in Python.
![image alt](https://github.com/Priyanshi19-ba/CodSoft-task-1/blob/main/Screenshot%202025-07-03%20164626.png?raw=true)
**Objective**
The objective of this project is to create a simple To-Do List app using Python to help users manage their daily tasks easily and stay organized.
**Key Activities**
1.Display Menu Options:
Shows a list of options (View, Add, Mark as Done, Delete, Exit) for user interaction in a loop.
2.View Tasks:
Displays all current tasks along with their status ("Pending" or "Done").
If the list is empty, shows a message accordingly.
3.Add Task:
Takes user input to add a new task to the list.
Every task is stored as a pair: [task_name, status] where status is initially False (Pending).
4.Mark Task as Done:
Lists all tasks with their current status.
Takes input of the task number and updates its status to Done.
5.Delete Task:
Lists all current tasks.
Takes input of the task number to remove that task from the list.
6.Exit the Program:
Ends the loop and exits the application gracefully with a goodbye message.
7.Input Validation:
Checks for valid numeric inputs to prevent errors (e.g., when marking or deleting tasks).
**Technologies Used**
1. Programming Language
Python
The entire code is written in the Python programming language.
2. Data Structures
List
A list named tasks is used to store tasks. Each task is represented as a sub-list containing the task description and its status (done or pending).
Example: ["Task Name", False]
3. Control Flow
while loop:
An infinite loop (while True:) is used to repeatedly show the menu and accept user input until the user chooses to exit.
if-elif-else statements:
Conditional statements are used to handle different user choices.
4. Input/Output
input() function
Used to take input from the user.
print() function
Used to display messages and the to-do list on the screen.
5. String Formatting
f-strings
Used for formatting output strings in a readable way, for example:
f"{i+1}. {tasks[i]} - [{status}]"
6. Basic Input Validation
isdigit() method
Used to check if the user input is a valid number before converting it to an integer.

**Key Insights:**
1. Interactive Menu-Driven Interface
The program uses a continuous loop to present a menu of options, allowing users to interactively manage their tasks until they choose to exit.
2. Dynamic Task Management
Users can view, add, mark as done, and delete tasks, making the program a fully functional to-do list manager.
3. Task Status Tracking
Each task is stored as a pair: [task_description, status], where status is a boolean indicating whether the task is "Pending" or "Done".
This allows for clear status updates and visual feedback for completed tasks.
4. Input Validation
The program checks user inputs for validity (e.g., ensuring task numbers are digits and within the correct range) to prevent errors and improve user experience.
5. User Feedback
After each operation (add, mark as done, delete), the program provides immediate feedback, confirming the action or indicating errors.
6. Handles Empty List Scenarios
The code gracefully handles situations where there are no tasks to view, mark as done, or delete, ensuring robustness.
7. Simple Data Structure
Tasks are stored in a list of lists, making the code easy to understand and modify for beginners.
8. Extensible Design
The structure allows for easy addition of new features, such as editing tasks, saving/loading from a file, or categorizing tasks.
