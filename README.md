# CRUD-Application

This is a simple **CRUD (Create, Read, Update, Delete)** application built using **Node.js** and **Express.js**. It allows users to perform basic CRUD operations on user data, such as adding, retrieving, and deleting user information, all stored in a JSON file.

## Features

- **Add User**: Create a new user by providing details such as User ID, Name, DOB, and Profession.
- **Get User Details**: Retrieve the details of a specific user by their User ID.
- **Delete User**: Remove a specific user by their User ID.
- **Show All Users**: View all users stored in the JSON database.

## Project Structure
/crud-application │ ├── /public # Front-end HTML and CSS files ├── /node_modules # Node.js dependencies ├── users.json # JSON file to store user data ├── server.js # Main Node.js/Express server file └── README.md # Project documentation


## Technologies Used

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for Node.js.
- **HTML & CSS**: Frontend form interface with basic styling.
- **JSON**: Used for storing and managing user data.

## Prerequisites

Before running the application, make sure you have the following installed:

- **Node.js** (v14 or higher)
- **npm** (Node package manager)

You can check if Node.js and npm are installed by running the following commands in your terminal:

```bash
node -v
npm -v

1.git clone https://github.com/your-username/crud-application.git
2.cd crud-application
3.npm install
4.node server.js
5.Open your browser and go to http://localhost:3000 to view the CRUD application.


