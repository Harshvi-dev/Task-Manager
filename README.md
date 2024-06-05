Task Manager Application : 

Welcome to the Task Manager Application! This is a full-stack web application built with ReactJS and NestJS, using MySQL as the database. It provides functionality for both admin and customer users to manage tasks.

Features:

1> User Authentication: Implemented user authentication and registration for both admin and customer users.
2> Email Verification: Upon user registration, an email verification link is sent to the user's email using Mailtrap.
3> JWT Security: JWT (JSON Web Tokens) are used for secure authentication and authorization.

Task Management:

1> Add Task: Users can add new tasks with a title, description, assignee, and assigner.
2> Display Tasks: Tasks are displayed in a table format showing task details including task name, description, assignee, and assigner.
3> Update Task: Users can update existing tasks, modifying task details such as title, description, assignee, or assigner.
4> Delete Task: Users can delete tasks they no longer need.
5> API Integration: Axios is used for making API calls from the frontend to interact with the backend endpoints.

Technologies Used: 

Frontend:

ReactJS
HTML
JavaScript
TypeScript
Axios for API calls
Backend:

NestJS
TypeScript
MySQL
JWT for security
Mailtrap for email verification
Getting Started
Clone the repository: git clone <repository-url>
Navigate to the project directory: cd task-manager

Install dependencies:
Backend: cd backend && npm install
Frontend: cd frontend && npm install
Configure the MySQL database connection in the backend.
Run the backend server: cd backend && npm run start:dev
Run the frontend: cd frontend && npm start
Now, you should be able to access the Task Manager Application at http://localhost:3000 in your web browser.

Contributing : 
Contributions are welcome! If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request.

License : 
This project is licensed under the MIT License.

Feel free to customize this README template to better fit your project's specific details and requirements. If you have any questions or need further assistance, please let me know!
