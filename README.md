
## **1. Introduction**

This project is a GUI-based To-Do List Application built using Python’s `tkinter` library. It allows users to add, delete, cross out, uncross, and save their daily tasks with ease. The application has a clean interface with colorful buttons, a list display, and a menu bar for file operations. It helps in learning file handling with `pickle`, event-driven GUI programming, and list-based task management.

---

## **2. Main Objectives**

1. To build a functional to-do list app using Python's `tkinter` GUI.
2. To understand how to manage and organize tasks using a graphical listbox.
3. To learn file handling using the `pickle` module.
4. To apply basic event-driven programming (buttons and menu interactions).
5. To develop a user-friendly tool for daily task management.

## **3. Software & Tools Used**

* **Programming Language**: Python 3.x
* **Library**: tkinter (built-in GUI library in Python)
* **IDE**: PyCharm / VS Code / IDLE
* **Platform**: Desktop (Windows recommended)
* **Input Device**: Keyboard and Mouse

## **4. System Design**

The application contains the following key components:

* **Listbox**: To display tasks.
* **Entry widget**: To input new tasks.
* **Buttons**: Add, delete, cross, uncross, delete crossed.
* **Menu Bar**: To open/save lists using file dialogs and the `pickle` module.
* **Scrollbar**: For scrolling through the task list.
## **5. Functionalities Implemented**

* Add a task
* Delete a selected task
* Cross out a task (strikes it visually by changing the font color)
* Uncross a task (resets the color back)
* Delete all crossed-out tasks
* Save the current list to a `.data` file
* Load a previously saved list from file
* Clear the entire task list
## **6. Workflow**

1. User opens the application.
2. A pre-filled list of dummy tasks is displayed.
3. The user can type a new task in the entry box and click **Add Task**.
4. Tasks can be selected and modified (delete/cross/uncross).
5. The list can be saved or loaded from a `.data` file.
6. The application keeps running until **Exit** is selected from the menu.

## **7. Sample Input/Output**

| **Action**                | **Expected Output**                      |
| ------------------------- | ---------------------------------------- |
| Add "Finish homework"     | Task appears in the list                 |
| Delete selected task      | Task removed from the list               |
| Cross out "Go to college" | Task turns light gray (visual strikeout) |
| Save the list             | Creates a `.data` file with tasks         |
| Load a file               | Loads tasks from the selected file       |

## **8. Advantages**

* Simple, intuitive interface for task management.
* Helps improve productivity and daily planning.
* Uses Python’s built-in GUI module — no external dependencies.
* Demonstrates real-world use of `pickle` for data persistence.
* Easy to expand with features like task priorities, due dates, etc.

## **9. Limitations**

* No support for task priorities or categories.
* No confirmation prompts for delete actions.
* File format `.data` is not human-readable.
* Tasks are not timestamped.

## **10. Future Enhancements**

* Add a calendar/date picker for deadlines.
* Enable drag-and-drop task reordering.
* Allow users to set reminders.
* Use SQLite or JSON instead of `.data` for better readability and integration.
* Improve UI with modern themes using `tk` or custom styles.

## **11. Conclusion**

The To-Do List project using Python’s `tkinter` is a practical and interactive application that demonstrates important programming concepts like GUI development, file I/O, and modular coding. It is an excellent hands-on project for beginners to learn how to build and manage real-world applications.


 ## **12.OUTPUT**
 
![Screenshot 2025-07-03 212051](https://github.com/user-attachments/assets/43ad04b4-4c8e-4d90-aff5-2af9a264e886)
![Screenshot 2025-07-03 212111](https://github.com/user-attachments/assets/268b7044-5112-4082-8a2e-a4d530fcdcbe)
![Screenshot 2025-07-03 212152](https://github.com/user-attachments/assets/1e74e0f2-a505-4e15-b329-f405696d8569)

![Screenshot 2025-07-03 212217](https://github.com/user-attachments/assets/a9a0bc6d-c31d-49ac-87ed-d0b79feade8e)
![Screenshot 2025-07-03 212228](https://github.com/user-attachments/assets/96c80aa4-c274-47c5-ace5-442b0252a557)
