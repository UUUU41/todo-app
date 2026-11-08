# To-Do App

A to-do list app with add, complete and delete features.

## Features

- Add a task in seconds with the input box and Add button
- Mark a task as complete with one click - completed tasks are struck through
- Delete tasks you no longer need
- Filter the list: All, Active or Completed
- See at a glance how many tasks are left to do
- Clear all completed tasks in one click
- Tasks are saved in the browser with localStorage, so they survive a refresh

## Tech Stack

- HTML5 - structure and task form
- CSS3 - layout and styling (inline in `index.html` for simplicity)
- JavaScript - add, complete, delete, filter and localStorage (inline in `index.html`)
- No build tools, frameworks or server required

## How to Run / Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/UUUU41/todo-app.git
   cd todo-app
   ```

2. Open `index.html` in any modern web browser, or serve the folder:

   ```bash
   python3 -m http.server 8000
   ```

   Then visit `http://localhost:8000`.

3. Type a task, for example `Finish maths homework`, and click Add. Click a task's checkbox to complete it, or Delete to remove it. Use the All / Active / Completed buttons to filter the list.

## Project Structure

```text
todo-app/
- index.html   (structure, styling and all app logic in one file)
- README.md    (project documentation)
```

## Future Improvements

- Add due dates and priorities
- Add drag-and-drop reordering
- Add task categories and search
- Add a dark mode
- Sync tasks across devices with a backend

## Author

Chandan Yadav (UUUU41) - https://github.com/UUUU41
