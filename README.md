# Task Manager App (Frontend)

## Overview

This project is a full-stack Task Management Application developed independently by me as part of a remote Web Development Internship at Codveda Technologies.

The frontend is built with React and provides a clean, responsive user interface for managing daily tasks. The application communicates with a REST API backend to perform full CRUD operations and persist data in a database.

## Project Scope

This project was fully designed and implemented by me, without working in a team. I was responsible for the frontend user interface, API integration, application logic, and deployment.

## Features

- Create new tasks
- Update existing tasks
- Mark tasks as completed
- Delete tasks
- Client-side input validation with modal feedback
- Responsive UI with custom CSS styling
- Persistent task data via backend API

## Frontend Implementation

- React components for task creation, listing and updates
- State management for tasks and UI interactions
- REST API integration using Axios
- Responsive layout and custom styling using CSS
- Clean and user-friendly interface focused on usability

## Tech Stack

### Frontend
- React
- Axios
- CSS3 (custom styling & responsiveness)

## Live Demo

Frontend:  
https://d00055a.github.io/task-manager-app/

Backend API:  
https://task-api-4e4u.onrender.com

> Note: The backend is hosted on Render (free tier), so the first request may take up to one minute to respond.


  
## Run Locally

### Frontend Setup

```bash
git clone https://github.com/d00055a/task-manager-app.git
cd task-manager-app
npm install
``` 

- Create a **.env** file:

```Env
REACT_APP_API_URL=http://localhost:5000
```
- Run the application:

```bash
npm start
```

## Deployment

To deploy to GitHub Pages:


1. Update **.env** with the production backend URL:

```Env
VITE_API_URL=https://user-authentication-backend-3dvc.onrender.com
```

2. Build and deploy:


```bash
npm run deploy
```


## Purpose

This project was built to demonstrate:

- Independent frontend development with React

- CRUD operations through API integration

- Building responsive and user-friendly interfaces

- Real-world frontend ↔ backend communication

