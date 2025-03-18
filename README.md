# 📝 To-Do List App (SwiftUI)

## 📌 Project Overview
The **To-Do List App** is a task management application built using **SwiftUI**. It allows users to add, view, complete, and delete tasks efficiently while providing an intuitive user experience. The app features **dark mode support, animations, custom colors, and a responsive layout** to enhance usability.

## 🚀 Features
- ✅ **Multi-Screen Navigation:** Uses `NavigationStack` to navigate between Task List, Task Details, and Add Task screens.  
- ✅ **Task Management:** Users can add, delete, and mark tasks as completed.  
- ✅ **Task Filtering:** Sort tasks alphabetically with a single tap.  
- ✅ **Custom Colors:** Users can assign colors to tasks for better organization.  
- ✅ **Dark Mode Support:** Automatically adjusts UI based on system theme.  
- ✅ **Smooth Animations:** Uses `.animation()` and `.transition()` for a polished UI experience.  
- ✅ **Adaptive UI:** Supports various screen sizes with `GeometryReader`.  

---

## 📱 How It Works
1. **Add a Task**  
   - Tap the **➕ New** button in the top-right corner.  
   - Enter a **title**, **description**, **due date**, and **choose a color**.  
   - Tap **Add** to save the task.  

2. **View Task Details**  
   - Tap on a task to open its **detailed view**.  

3. **Mark a Task as Completed**  
   - Tap the **⭕ button** next to a task to mark it as completed.  

4. **Delete a Task**  
   - Tap the **🗑 Trash button** to remove a task.  

5. **Filter Tasks**  
   - Tap **Filter** (top-left) to sort tasks alphabetically.  
   - Tap again to shuffle back to the original order.  

---

## 🛠️ Technologies Used
- **SwiftUI** – Modern UI framework for declarative UI design.  
- **MVVM Architecture** – Uses `ObservableObject` for state management.  
- **Animations & Transitions** – `withAnimation()` and `.transition(.opacity.combined(with: .scale))`.  
- **Dark Mode Support** – `.preferredColorScheme()`.  

---
