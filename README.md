 # 🧩 Todo Card UI — Accessible & Testable Frontend Project

## 🚀 Overview

This project is a **responsive and accessible Todo Card UI** built using **HTML, CSS, and vanilla JavaScript**.

It was created as a frontend development exercise focusing on:
- Semantic HTML structure
- Accessibility best practices (ARIA + screen reader support)
- Testable UI design using `data-testid`
- Responsive design across devices
- Dynamic JavaScript behavior (time calculations)

---

## ✨ Features

- 📌 4 Todo task cards
- 🏷️ Priority system (High / Medium / Low)
- 📅 Due date display using `<time>` element
- ⏱️ Live “time remaining” updates (auto-refresh every 60s)
- ✅ Checkbox to mark tasks as complete
- 🏷️ Tags system using semantic `<ul>` and `<li>`
- ✏️ Edit button (icon-based)
- 🗑️ Delete button (icon-based)
- 📱 Fully responsive layout (mobile → desktop)

---

## 🧪 Testing (Important)

This project includes all required `data-testid` attributes for automated testing:

- test-todo-card  
- test-todo-title  
- test-todo-description  
- test-todo-priority  
- test-todo-due-date  
- test-todo-time-remaining  
- test-todo-status  
- test-todo-complete-toggle  
- test-todo-tags  
- test-todo-edit-button  
- test-todo-delete-button  

---

## ♿ Accessibility Features

- Semantic HTML:
  - `<article>`, `<time>`, `<label>`, `<ul>`, `<li>`
- Keyboard navigation support
- Screen reader support using:
  - `aria-label` for icon buttons
  - `aria-live="polite"` for time updates
- Visible focus states for interactive elements

---

## ⏱️ Time Logic

- Calculates difference between current time and due date
- Displays:
  - “Due in X days”
  - “Due now!”
  - “Overdue by X hours”
- Automatically updates every 60 seconds using `setInterval`

---

## 📱 Responsiveness

- Mobile-first design approach
- Works across screen sizes from **320px to 1200px+**
- No horizontal scrolling
- Flexible layout with wrapping elements

---

## 🛠️ Tech Stack

- HTML5 (semantic structure)
- CSS3 (Flexbox + responsive design)
- Vanilla JavaScript (DOM + Date logic)
- Google Fonts (Inter)
- Remix Icons

---

## 📸 Preview

> Screenshots will be added soon after initial submission.

Planned updates:
- Desktop view
- Mobile view
- Interaction states (checked/completed tasks)

---

## 🌐 Live Demo

👉 https://todo-card-khaki.vercel.app

---

## 📂 Repository

👉 https://github.com/Cryptodoll-sketch/todo-card

---

## 👨‍💻 Author

Built by: **Olamide Tobun**

Frontend Developer (Aspiring)

