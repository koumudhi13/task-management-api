# Task Management API

## Project Overview
This is a backend REST API for managing tasks (like a to-do list).  
It allows users to create, read, update, and delete tasks using HTTP requests.

## Technology Stack
- Node.js
- Express.js
- JWT Authentication

## Features
- Create Task: POST /tasks
- Read All Tasks: GET /tasks
- Update Task: PUT /tasks/:id
- Delete Task: DELETE /tasks/:id

## How to Run
Go to the project folder and run the following commands:
```
cd task-management-api
npm install
npm start
```
Then test CRUD routes using Postman or Thunder Client:

```
GET /tasks
POST /tasks
PUT /tasks/:id
DELETE /tasks/:id
```
