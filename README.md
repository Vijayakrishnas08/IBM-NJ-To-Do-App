# IBM-NJ-To-Do-App  (React Hooks)

## Project Overview
IBM-NJ To-Do App is a lightweight task management application built using **React Hooks**.  
This repository documents the project development in **5 phases**:

1. Problem Understanding & Requirements
2. Solution Design & Architecture
3. MVP Implementation
4. Enhancements & Deployment
5. Demonstration & Documentation

---

## Phase 1 – Problem Understanding & Requirements

### Problem Statement
Managing tasks effectively is a common challenge.  
Users need a simple, responsive, and lightweight web-based To-Do App.  

### Scope
- Add, update, delete, complete tasks  
- Store tasks in React state (local only for now)  

### Deliverable
- Requirements document (PDF included in `/docs`)  

 [Phase 1 Document](./docs/Phase1-Problem-Requirements.pdf)

---

## Tech Stack (Planned)
- React (with Hooks)
- JavaScript (ES6)
- CSS for styling

---

## Roadmap
- **Phase 2:** Solution Design & Architecture
- **Phase 3:** Basic MVP implementation
- **Phase 4:** Enhancements & deployment
- **Phase 5:** Documentation & demo

- 	 PROBLEM STATEMENT:

Users today need simple, fast, and responsive tools to manage their tasks effectively.
While many apps exist, they often include bloated features or lack responsiveness on different devices.
The goal of the "Do App" is to provide users with a lightweight, intuitive task management tool that allows them to create, edit, complete, and delete tasks—quickly and efficiently.

	USER & STACKEHOLDERS:

Role	Description
User	Anyone who needs to track and manage tasks (students, professionals, etc.)
Product Owner	You or your client/instructor who defines features and priorities
Developers	Frontend and backend developers (could be just you)
Tester	Person responsible for validating features against criteria.




	USER STORIES:


ID	As a...	I want to...	So that...
US1	User	Create a new task	I can remember what I need to do
US2	User	View a list of my tasks	I can see what I need to complete
US3	User	Mark a task as completed	I know I’ve finished it
US4	User	Edit a task	I can correct or update task details
 US5	      User	Delete a task	     I can remove tasks I no longer need

	MVP FEATURES:
The following features define the Minimum Viable Product (MVP):
•	✅ Add new tasks
•	✅ View all tasks
•	✅ Mark tasks as completed/uncompleted
•	✅ Edit existing tasks
•	✅ Delete tasks
•	✅ Store data via REST API (Node.js backend with a database)


	WIREFRAMES / API ENDPOINT LIST:
A. Wireframes
Sketch simple screens (or describe layout):





1.	Main Screen:
o	Task Input (Text box + Add Button)
o	List of Tasks
	Task Text
	Checkbox for complete
	Edit & Delete icons.

2.	Edit Modal (optional):
o	Input field prefilled with task text o
Save button
You can use Figma, Balsamiq, or even hand-draw wireframes.

Method	Endpoint	Description
GET	/api/tasks	Get all tasks
POST	/api/tasks	Create a new task
PUT	/api/tasks/:id	Update a task
PATCH	/api/tasks/:id/complete	Mark as complete/incomplete
DELETE	/api/tasks/:id	Delete a task

	ACCEPTANCE CRITERIA:

Feature	Criteria
Create Task	When I type and click "Add", a new task appears in the list
View Tasks	On page load, I see all my tasks retrieved from the API
Edit Task	I can edit a task’s text and see the updated value
Delete Task	Clicking delete removes a task from the UI and DB
Complete Task	Clicking checkbox toggles completion visually and in DB
Responsive Design	The app works well on both mobile and desktop devices




