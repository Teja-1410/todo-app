# 📝 To-Do List App

A clean, simple To-Do List web app built with vanilla **HTML, CSS, and JavaScript** — no frameworks, no build tools. Add tasks, check them off, delete them, and save your list to the browser's local storage.

🔗 **Live Demo:** [https://teja-1410.github.io/todo-app/]

## ✨ Features

- ✅ Add new tasks
- ✅ Mark tasks as complete/incomplete (with strikethrough styling)
- ✅ Delete tasks
- ✅ Save your list to `localStorage` so it persists across sessions
- ✅ **Manual save by design** — changes aren't auto-saved as you type or check items. This lets you freely add/check multiple tasks, review them, and only commit changes when you click **Save**. Reloading the page without saving discards unsaved changes, giving you a clean way to undo a batch of edits you're not sure about.

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla, DOM manipulation)
- Bootstrap 4 (base styling/layout)
- Font Awesome (icons)

## 📂 Project Structure

```
├── index.html      # Main HTML structure
├── todo.css        # Styling
└── todo.js         # App logic (add, delete, check, save/load)
```

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open `index.html` in your browser — that's it, no installation needed.

## 💡 Possible Future Improvements

- Auto-save option (toggle between manual and auto-save modes)
- Edit existing tasks inline
- Filter tasks (All / Active / Completed)
- Drag-and-drop reordering
- Due dates and priority levels

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
