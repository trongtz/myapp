[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YHSq4TPZ)
# To-Do App – Preliminary Assignment Submission
⚠️ Please complete **all sections marked with the ✍️ icon** — these are required for your submission.

👀 Please Check ASSIGNMENT.md file in this repository for assignment requirements.

## 🚀 Project Setup & Usage
**How to install and run your project:**  
- npm install
- npm run dev

## 🔗 Deployed Web URL or APK file
https://todo-bytz.netlify.app/


## 🎥 Demo Video
**Demo video link (≤ 2 minutes):**  
https://drive.google.com/file/d/1yl4iJYPbeG4N-a3WGrtpRlYulA_8d3uK/view?usp=sharing


## 💻 Project Introduction

### a. Overview
- This project is a modern **To-Do List application** designed to help users manage tasks effectively.  
- It allows students and professionals to create, organize, track, and complete their daily activities in multiple views such as **list view, calendar view, and a bingo challenge view**.  
- The app focuses on simplicity, usability, and motivation through gamification.

### b. Key Features & Function Manual

- **Task Management**: Add, edit, delete, and mark tasks as complete or failed.  
- **Views**: Switch between list view, calendar view, and bingo board for different task management experiences.  
- **Filters & Search**: Filter by status (all, active, conpleted, failed) or by tags, and search tasks with keywords.  
- **Sorting**: Sort by due date, name, or recently created tasks.  
- **Tags**: Categorize tasks with custom tags for better organization.  
- **Quick Add**: Add tasks with title, due date, and tags directly from the header.  
- **Drag & Drop**: Move tasks between statements (To-Do, Done, Failed) easily.  
- **Statistics**: View progress (total tasks vs. completed tasks).  
- **Persistence**: Data is stored locally in the browser with `localStorage`.  
- **Dark/Light Mode**: Toggle between themes for better user experience.
- **Task-Color based on deadline**: change from green to red base on the remaining real-time.
- **Clear all completed**: delete all completed task in the list. 

### c. Unique Features (What’s special about this app?) 

- **Bingo Board Gamification**: Completing tasks in rows or columns triggers a “Bingo!” win message to motivate users.  
- **Lightweight & Offline Ready**: Works directly in the browser without needing a backend.  
- **Student-Friendly Design**: Minimal, clean interface with motivational feedback.  

### d. Technology Stack and Implementation Methods
- **Frontend**: React (with TypeScript)  
- **Styling**: CSS with modern layout design (responsive, dark/light theme)  
- **State Management**: React hooks (`useState`, `useEffect`, `useMemo`)  
- **Storage**: Browser `localStorage` for persistence  
- **Extra Libraries**:  
  - Framer Motion (animations)  
  - Lucide React (icons)  

### e. Service Architecture & Database structure (when used)
- **Architecture**:  
  - Client-side single page application (SPA) built with React.  
  - Modular components for tasks, views, header, sidebar, and modal dialogs.  
- **Database**:  
  - No external database used.  
  - Tasks are stored in `localStorage` as JSON, with fields:  
    - `id`, `title`, `desc`, `tag`, `due`, `completed`, `created`, `col`.

## 🧠 Reflection

### a. If you had more time, what would you expand?

- Add **user authentication** and cloud sync (so tasks are available across devices).  
- Support **collaborative task sharing** between multiple users.  
- Add **push notifications / reminders** for upcoming due dates.  
- Improve **calendar integration** with Google Calendar or Outlook.  
- Optimize **mobile UI** with gestures for task control.  

### b. If you integrate AI APIs more for your app, what would you do?

- **Smart Task Suggestions**: AI could suggest deadlines or priorities based on task description.  
- **Natural Language Input**: Add tasks by typing “Finish report tomorrow at 5pm” → auto-parse title, due date, and time.  
- **Task Summarization**: Summarize long descriptions into short actionable steps.  
- **Motivation Assistant**: AI chatbot to encourage productivity and suggest study/work tips.  

## ✅ Checklist
- [✅] Code runs without errors  
- [✅] All required features implemented (add/edit/delete/complete tasks)  
- [✅] All ✍️ sections are filled  
