This repository contains a blog application built using the MERN (MongoDB, Express, React, Node.js) stack. The application is enhanced with the bcrypt library for secure password hashing and React libraries for efficient frontend development. This blog application allows users to read, create, update, and delete blog posts.

Table of Contents -

Installation
Features
Technologies Used
Usage
Contributing
License
Installation
Follow these steps to set up the blog application locally:

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/mern-blog-app.git
cd mern-blog-app
Install server dependencies:
bash
Copy code
cd server
npm install
Install client dependencies:
bash
Copy code
cd ../client
npm install
Create a .env file in the server directory to store environment variables:
plaintext
Copy code
MONGO_URI=your_mongodb_connection_string
SECRET_KEY=your_secret_key_for_jwt
Run the application:
bash
Copy code
cd ../server
npm start
The server will start on http://localhost:5000, and the client will run on http://localhost:3000.

Features
User Authentication: Users can register, login, and logout securely using bcrypt for password hashing and JWT (JSON Web Tokens) for authentication.

Blog Posts: Users can create, edit, and delete their blog posts. They can also view posts created by other users.

Comments: Users can comment on blog posts and interact with each other through the comments section.

Categories and Tags: Users can categorize their blog posts and add tags to make them easily discoverable.

User Profiles: Each user has a profile page displaying their blog posts and other information.

Search Functionality: Users can search for blog posts using keywords, categories, or tags.

Responsive Design: The application is designed to be mobile-friendly and accessible on various devices.

Technologies Used
MongoDB: A NoSQL database for storing blog posts, user information, and comments.
Express.js: A backend framework for building the API and handling server-side operations.
React: A frontend library for building user interfaces and managing UI components efficiently.
Node.js: A JavaScript runtime environment to execute server-side code.
bcrypt: A library for securely hashing passwords.
React Libraries:
react-router: For handling routing in the React application.
axios: For making HTTP requests to the server.
react-bootstrap: For styling and UI components.
react-icons: For including icons in the application.
Usage
Register: Users can create a new account by providing their email and a secure password.

Login: Registered users can log in with their credentials.

View Blogs: Once logged in, users can browse and read blog posts from various authors.

Create a Blog: Logged-in users can create their own blog posts, add categories, and tags.

Edit and Delete: Users can edit or delete their own blog posts.

Comment: Users can leave comments on blog posts.

Search: Users can search for specific blog posts using keywords, categories, or tags.

User Profile: Each user has a profile page displaying their blog posts and other information.

Contributing
If you wish to contribute to this project, follow these steps:

Fork the repository.
Create a new branch: git checkout -b feature/your-feature-name.
Make your changes and commit them: git commit -m "Add some feature".
Push to the branch: git push origin feature/your-feature-name.
Submit a pull request describing your changes.
License
This project is licensed under the MIT License.

Thank you for using our MERN blog application! If you have any questions or feedback, please don't hesitate to contact us. Happy blogging! 🚀
