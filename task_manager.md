# Task: Task Manager

**Objective:** Create a program that serves as a task manager, allowing the user to add, view, mark as completed, and delete tasks. Write a program in Python that includes the following topics:

1. Basic concepts: variables, data types, operators, input, and output of data.
2. Loops: while.
3. Conditional statements: if, elif, else.
4. Lists.

**Description:**
1. Create a menu that presents the user with the following options:
   - View the current task list.
   - Add a new task.
   - Mark a task as completed.
   - Delete a task.
   - Exit the task manager.

2. Create a list to store tasks. Each task should include the task name and its completion status (completed or not).

3. Depending on the user's choice in the menu, perform the corresponding action:
   - When the user selects "View the current task list," display all tasks and their statuses on the screen.
   - When the user selects "Add a new task," prompt them to enter the task name and add it to the list with the initial status "not completed."
   - When the user selects "Mark a task as completed," allow them to choose a task from the list and change its status to "completed."
   - When the user selects "Delete a task," allow them to choose a task from the list and remove it from the task list.
   - When the user selects "Exit the task manager," end the program.

4. After performing each operation, return to the main menu so that the user can continue working with the task manager.

**Example Output:**
```
=== Task Manager ===

1. View the current task list
2. Add a new task
3. Mark a task as completed
4. Delete a task
5. Exit

Choose an action: 2

Enter the task name: Plant flowers in the garden

Task "Plant flowers in the garden" added successfully!

=== Task Manager ===

1. View the current task list
2. Add a new task
3. Mark a task as completed
4. Delete a task
5. Exit

Choose an action: 1

Current task list:
1. [uncompleted] Plant flowers in the garden

=== Task Manager ===

1. View the current task list
2. Add a new task
3. Mark a task as completed
4. Delete a task
5. Exit

Choose an action: 3

Choose a task to mark as completed: 1

Task "Plant flowers in the garden" marked as completed!

=== Task Manager ===

1. View the current task list
2. Add a new task
3. Mark a task as completed
4. Delete a task
5. Exit

Choose an action: 4

Choose a task to delete: 1

Task "Plant flowers in the garden" deleted.

=== Task Manager ===

1. View the current task list
2. Add a new task
3. Mark a task as completed
4. Delete a task
5. Exit

Choose an action: 5

The exit was successful. Have a nice day!
```

**Note:**
Ensure that your program handles possible input errors and provides informative messages in such situations. Use loops and conditional statements to ensure the correct functioning of the task manager.
