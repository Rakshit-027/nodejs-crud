User Management App
Welcome to the User Management App! 🚀 A sleek and modern web application built with Node.js, Express, MongoDB, and EJS to perform CRUD operations (Create, Read, Update, Delete) on user data. Whether you're managing a small team or just exploring, this app provides a clean interface and robust functionality.


📋 Table of Contents

Features
Tech Stack
Installation
Usage
Project Structure
Screenshots
Contributing
License


✨ Features

Create Users: Add new users with details like name, email, and more.
Read Users: View a responsive list of all users.
Update Users: Edit user details with ease.
Delete Users: Remove users securely.
Responsive Design: Clean and intuitive UI built with EJS and Bootstrap.
MongoDB Integration: Persistent storage for reliable data management.


🛠️ Tech Stack

Node.js: JavaScript runtime for server-side logic.
Express.js: Web framework for routing and middleware.
MongoDB: NoSQL database for storing user data.
EJS: Templating engine for dynamic HTML rendering.
Bootstrap: CSS framework for responsive design.


🚀 Installation
Follow these steps to get the app running locally:
Prerequisites

Node.js (v18.x or higher)
MongoDB (v6.x or higher, local or cloud like MongoDB Atlas)
Git

Steps

Clone the repository:
git clone https://github.com/Rakshit-027/nodejs-crud
cd user-management-app


Install dependencies:
npm install


Set up MongoDB:

Ensure MongoDB is running locally or provide a MongoDB Atlas connection string.
Create a .env file in the root directory and add:MONGODB_URI=mongodb://localhost:27017/user-management
PORT=3000




Start the server:
npm start


Access the app:Open your browser and navigate to http://localhost:3000.



📖 Usage

Home Page: View the user list or add a new user.
Add User: Click "Add User" to fill out a form for creating a new user.
Edit User: Click "Edit" next to a user to update their details.
Delete User: Click "Delete" to remove a user.
The app uses EJS templates for rendering views and MongoDB for data persistence.


📂 Project Structure
user-management-app/
models/
    └── user.js
public/
    └── styles/
        └── index.css
views/
    ├── edit.ejs
    ├── index.ejs
    └── read.ejs
.gitignore
app.js
package-lock.json
package.json
README.md


📸 Screenshots
User List

Add User Form


🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes.
Commit your changes (git commit -m "Add your message").
Push to the branch (git push origin feature/your-feature).
Open a Pull Request.

Please ensure your code follows the existing style and includes tests where applicable.

📜 License
This project is licensed under the MIT License.

Happy Coding! 🎉Built with ❤️ using Node.js](https://nodejs.org/), Express, MongoDB](https://www.mongodb.com/), and EJS.Have questions? Feel free to open an issue or reach out!
