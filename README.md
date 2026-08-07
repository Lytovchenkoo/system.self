# 📔 Personal Diary

**Personal Diary** is a personal web application designed to help users organize their daily lives efficiently. It combines the functionality of a personal diary, habit tracker, task planner, and expense tracker in a single, user-friendly interface.

---

## 🧩 Features

| Module | Description |
|--------|-------------|
| 📅 **Calendar** | A calendar with daily task indicators and the ability to add quick notes. |
| ✅ **To-do** | A task management system that allows users to create, edit, and delete tasks. |
| 📊 **Habits** | A habit tracker with progress visualization to help users maintain daily routines. |
| 💸 **Expenses** | An expense tracker with automatic currency conversion using real-time exchange rates. |

---

## ⚙️ Technologies

- **HTML** — Semantic page structure.
- **CSS** — User interface styling.
- **JavaScript (Vanilla)** — Client-side logic and interactivity.
- **LocalStorage** — Browser-based data persistence.
- **ExchangeRate-API** — Integration for automatic currency conversion in the expense tracker:
  - Retrieves real-time exchange rates.
  - Dynamically converts expenses between different currencies.

---

## 📂 Project Structure

```text
System.Self/
├── index.html
├── habits.html
├── todo.html
├── expenses.html
├── css/
│   ├── todo.css
│   ├── habits.css
│   ├── expenses.css
│   ├── schedule.css
│   └── global.css
├── js/
│   ├── main.js
│   ├── todo.js
│   ├── habits.js
│   ├── expenses.js
│   ├── calendar.js
│   ├── page-init.js
│   └── storage.js
```
