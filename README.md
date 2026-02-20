# 📌 Kanban Board — Project Management System

## 1.1 Overview

This is a project management system which uses Kanban board.  
The system is a web application built using React and Node.js.

---

## 2. Features

### 2.1 Registration

- Non-authenticated users can register
- Client-side and server-side validation is used
- Check user already exists

### 2.2 Login

- Kanban board can be accessed only for authenticated users
- Backend validation is used when authentication

### 2.3 Authorization

- JWT (JSON Web Token) authorization is used

### 2.4 Add/Remove Columns

- Authenticated users can Add/Remove columns of their own board

### 2.5 Add/Remove Cards

- Authenticated users can Add/Remove cards of their own board

### 2.6 Logout

---

## 3. Technology Choices

### 3.1 Front End

| Technology      | Description                                                                                             |
| --------------- | ------------------------------------------------------------------------------------------------------- |
| React with Vite | React is JavaScript framework and Vite is a tool that can be used for client-side applications          |
| Tailwind CSS    | Tailwind CSS is a CSS framework                                                                         |
| TypeScript      | Using TypeScript, you can apply types to JavaScript and thus enable you to create which has less errors |
| daisyUI         | daisyUI is the Tailwind CSS plugin                                                                      |
| Axios           | Axios is a promise-based HTTP Client for node.js and the browser                                        |
| React Router    | Does client-side routing in a React app                                                                 |
| validator.js    | Used to validate user input                                                                             |

### 3.2 Back End

| Technology        | Description                                                                                             |
| ----------------- | ------------------------------------------------------------------------------------------------------- |
| Node.js           | Using Node.js you can run JavaScript on the server                                                      |
| TypeScript        | Using TypeScript, you can apply types to JavaScript and thus enable you to create which has less errors |
| Express           | Express is a Node.js framework                                                                          |
| Mongoose          | Mongoose is an ODM (Object Data Modeling) library for MongoDB and Node.js                               |
| express validator | Helps to validate and sanitize user inputs                                                              |
| Bcrypt            | Bcrypt is used to hash passwords with a salt                                                            |

---

## 4. Installation

1. Get the source from GitHub (https://github.com/nuwaninfo/kanban-board) by cloning or downloading
2. Go to the root folder
3. Run `npm install` — this will download all node modules inside root, client, and server folders
4. Run `npm run dev` — this will start both the client and the server concurrently
   - Server runs on port **8000**
   - Client runs on port **3000**
5. Open a browser and go to:  
   **http://localhost:3000/**
6. Note: **MongoDB should be already installed** on the same machine
