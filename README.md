# React Todo App with API - Usage Tutorial

Welcome to the usage tutorial for the React Todo App with API. This tutorial will guide you on how to use the app effectively. Please note that this tutorial is not focused on implementation details, but rather on how to interact with the app's features.

## To add a new todo with the entered title:

- Fill in the title of the todo in the input field provided.
- Press `Enter`.

## To remove a todo:

- Hover over the task you want to delete.
- Click on the `X` associated with that particular todo.

## Toggling a Todo Status:

- To toggle the completed status of a Todo, find the Todo you want to modify in the list.
- Click on the TodoStatus checkbox to change its completed status.
- While waiting for the API response, the Todo will be covered with a loader overlay.
- On a successful API response, the Todo's status will be updated accordingly.
- In case of an API error during the update, a notification with the message "Unable to update a todo" will be displayed.
## Toggling All Todos' Status:

- To toggle the completed status of all the Todos, locate the "toggleAll" checkbox at the top of the list.
- Clicking on the "toggleAll" checkbox will change its status to the opposite one and set it for all the Todos.
- This action will work the same as individually updating each Todo's status that has actually changed.

## To remove all the completed todos:

- Click on the "Clear completed" button to initiate the deletion process.
- The deletion will work as several individual deletions running at the same time, removing all the completed todos from the list.
## Renaming a Todo:

- To edit a Todo title, double click on the Todo's title that you wish to modify.
- The title will be replaced with an edit form, and the remove button will be hidden.
- Make the necessary changes to the title in the edit form.
- To save the changes, either press the Enter key or move the focus away from the edit field.
- If the new title is the same as the old one, the editing process will be canceled automatically.
- Alternatively, you can press the Esc key during editing to cancel the changes.
- If you delete the title completely (empty field), the Todo will be deleted, just like clicking the x button does.
- While waiting for the API response after saving changes, a loader will be displayed.
- On a successful API response, the Todo's title will be updated with the new value.
- If an API error occurs during the update, a notification with the message "Unable to update a todo" will be shown. If we tried to delete the todo and encountered an error, a deletion error message will be displayed.