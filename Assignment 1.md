# Assignment 1: TODO Application Test Plan

## Test Environment
- **Browser:** Chromium family
- **Operating System:** Ubuntu

## Test Scope
The test plan covers only the happy paths for the functionalities of the TODO application. The main functionalities include task creation, task edit, task status, task deletion, and task status views.

## Functionality Check
1. **Task Creation**
   - Users should be able to add a new task.
   - Created tasks should be visible in the list.
   - New tasks created should be visible in the All and Active status tabs.

2. **Task Edit**
   - Users should be able to edit the task by double-clicking on the task name.
   - After editing, the changes should be reflected in the list.

3. **Task Status**
   - Users should be able to mark the status of the task by clicking on the radio button.
   - Completed tasks should be visible under the completed tasks list.

4. **Task Deletion**
   - Users should be able to delete the task.
   - Deleted tasks should be removed from the task list.

5. **Task Status Views**
   - When the user selects All status, all the tasks should be visible.
   - When the user selects Active status, only the active tasks should be visible.
   - When the user selects Completed status, only the completed tasks should be visible.

## Test Use Cases for "Task Deletion" and "Task Edit" Features using BDD Language

### Task Deletion:
Given task "Run to the door"
When user clicks on the cross mark next to the task "Run to the door"
Then "Run to the door" task should be removed from the list



### Task Edit:
Given a task "Pay water bill" in the task list
When user edits "Pay water bill" to "Pay all the water bills"
Then "Pay water bill" should be updated with "Pay all the water bills"



## Bug Report
- When all the items are selected, "1 item left" message is displayed.
- When the user is selecting one task item, the other task is also being selected.
- When the user selects a task, the tasks are getting greyed out except one.
- Instead of radio button, checkbox should be used since there is an option for multiselect.
- When user hovers on the radio button, it is showing a pointer instead of a hand glove.

## Enhancement
- Edit option can be used instead of double click.
- Delete icon can be added instead of cross mark to delete the task.

## Test Strategies
- Functional testing
- Regression testing
- Smoke testing
- Sanity testing
- End-to-end testing





