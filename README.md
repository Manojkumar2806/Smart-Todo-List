# Dynamic To-Do List App ✅

A simple and interactive to-do list web application that allows users to add, delete, and mark tasks as completed. The app also saves the list in the browser's `localStorage` to persist data across sessions.

---

## 🌐 Live Demo  
🔗 [Click here to use the To-Do List App](https://manojtasks.ccbp.tech/)  

---

## 🖼️ Screenshots  

### 📋 Task List View  

## Before Tasks Completed
![image](https://github.com/user-attachments/assets/a619a609-0c4d-490f-ae17-e1bb5da16d16)

## After Tasks Completed
![image](https://github.com/user-attachments/assets/7fe718a7-4922-4f1c-9e34-64b2b1e2fb79)

---

## Features ✨

- **Add Tasks**: Users can add new tasks to the list.
- **Mark as Completed**: Tasks can be checked off as completed.
- **Delete Tasks**: Users can remove tasks from the list.
- **Save Progress**: The to-do list is saved in `localStorage`, so it persists even after page reloads.
- **Complete/Incomplete Task Toggle**: Tasks can be toggled between completed and pending states.

## Technologies Used ⚙️

- **HTML**: Structure of the webpage.
- **CSS**: Styling with custom design.
- **JavaScript**: Handles interactivity, including task creation, deletion, and marking as complete.
- **Bootstrap**: For basic layout and responsiveness.
- **Font Awesome**: For icons (e.g., delete icon).

## How to Use 🚀

1. **Add a Task**: Type a task in the input field and click the "add" button.
2. **Mark a Task as Complete**: Check the checkbox next to a task to mark it as completed.
3. **Delete a Task**: Click the trash icon to remove a task from the list.
4. **Save the List**: Click the "Save" button to save the list in `localStorage`.

## 🧠 Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Maintaining state after reload | Integrated `localStorage` for persistent data |
| Toggling task styles dynamically | Used `classList.toggle()` to apply "completed" styles |
| Handling delete operations for dynamic elements | Attached event listeners dynamically using delegation |
| Keeping the UI clean on mobile | Leveraged Bootstrap's responsive grid system |

## THANK YOU for Visiting My repo 💖

