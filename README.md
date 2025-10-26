# Task Management API
## Project Overview
This is a *backend REST API* for managing tasks (like a to-do list).  
It allows users to *create, read, update, and delete tasks* using HTTP requests.

## Technology Stack
- Node.js 
- Express.js
-JWT Authentication

## Features
- Create Task:POST /tasks  
- Read All Tasks:GET /tasks  
- Update Task:PUT /tasks/:id  
- Delete Task:DELETE /tasks/:id  

## How to Run
1. Go to the project folder
   cd task-management-api
2. Install dependencies:
   npm install
3. Start the server
   npm start
4. Open Thunder Client or Postman to test CRUD routes:
   - GET /tasks
   - POST /tasks
   - PUT /tasks/:id
   - DELETE /tasks/:id

## Notes
- It will reset when the server restarts.  
- Each task has a unique ID, title, and description.  