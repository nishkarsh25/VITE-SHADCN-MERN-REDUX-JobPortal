# VITE-SHADCN-MERN-REDUX-JobPortal Project

Welcome to the MERN (MongoDB, Express.js, React.js, Node.js) stack project! This comprehensive guide will walk you through every aspect of this project, including its structure, setup instructions, usage, API endpoints, backend, frontend, contributing guidelines, license information, and how to get in touch for support or inquiries.

## Introduction

The Job Portal Application is a modern web application designed to streamline the job search and recruitment process. This platform caters to both job seekers and recruiters, offering a range of features to enhance the job application and recruitment experience. Built with a React frontend and a Node.js backend, this application provides a robust and scalable solution for job management and applicant tracking.


## Features

### For Job Seekers
- **User Authentication**: Secure login and signup processes for job seekers to create and manage their accounts.
- **Browse Jobs**: View and filter job listings based on various criteria such as job title, company, location, and more.
- **Apply for Jobs**: Submit applications for jobs, including uploading resumes and providing necessary details.
- **View Job Descriptions**: Access detailed information about job postings, including role responsibilities, requirements, and company information.
- **Manage Profile**: Update personal information and view application history.

### For Recruiters
- **Admin Dashboard**: Access a comprehensive dashboard to manage job postings, companies, and applicants.
- **Job Management**: Create, edit, and delete job postings. View and manage job applications, including updating application statuses.
- **Company Management**: Add and update company profiles, including details about company locations and services.
- **Applicant Tracking**: Review and track job applicants, with options to view resumes, update application statuses, and more.

### For Administrators
- **Protected Routes**: Ensure that only authorized users can access certain features and functionalities.
- **Company and Job Post Management**: Full control over company and job postings, including creation, updating, and deletion.
- **Application Status Management**: Ability to update the status of job applications (e.g., accepted, rejected) and manage applicant interactions.


## Live Demo

You can try out the live demo of the app [here](https://vite-shadcn-mern-redux-jobportal-2.onrender.com).

## Folder Structure

```
project-root/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── admin/
│   │   │   ├── Applicants/
│   │   │   │   ├── ApplicantsTable.jsx
│   │   │   │   └── index.jsx
│   │   │   ├── CompanyCreate/
│   │   │   │   ├── CompanyCreate.jsx
│   │   │   │   └── index.jsx
│   │   │   ├── CompanySetup/
│   │   │   │   ├── CompanySetup.jsx
│   │   │   │   └── index.jsx
│   │   │   ├── Companies/
│   │   │   │   ├── Companies.jsx
│   │   │   │   └── index.jsx
│   │   │   ├── PostJob/
│   │   │   │   ├── PostJob.jsx
│   │   │   │   └── index.jsx
│   │   │   ├── ProtectedRoute/
│   │   │   │   ├── ProtectedRoute.jsx
│   │   │   │   └── index.jsx
│   │   │   └── AdminJobs/
│   │   │       ├── AdminJobs.jsx
│   │   │       └── index.jsx
│   │   ├── auth/
│   │   │   ├── Login/
│   │   │   │   ├── Login.jsx
│   │   │   │   └── index.jsx
│   │   │   ├── Signup/
│   │   │   │   ├── Signup.jsx
│   │   │   │   └── index.jsx
│   │   ├── Home/
│   │   │   ├── Home.jsx
│   │   │   └── index.jsx
│   │   ├── Jobs/
│   │   │   ├── Jobs.jsx
│   │   │   └── index.jsx
│   │   ├── Browse/
│   │   │   ├── Browse.jsx
│   │   │   └── index.jsx
│   │   ├── Profile/
│   │   │   ├── Profile.jsx
│   │   │   └── index.jsx
│   │   ├── JobDescription/
│   │   │   ├── JobDescription.jsx
│   │   │   └── index.jsx
│   │   ├── shared/
│   │   │   ├── Navbar/
│   │   │   │   ├── Navbar.jsx
│   │   │   │   └── index.jsx
│   │   │   └── index.jsx
│   │   └── ui/
│   │       ├── button/
│   │       │   ├── Button.jsx
│   │       │   └── index.jsx
│   │       ├── input/
│   │       │   ├── Input.jsx
│   │       │   └── index.jsx
│   │       ├── label/
│   │       │   ├── Label.jsx
│   │       │   └── index.jsx
│   │       ├── select/
│   │       │   ├── Select.jsx
│   │       │   └── index.jsx
│   │       ├── table/
│   │       │   ├── Table.jsx
│   │       │   └── index.jsx
│   │       └── avatar/
│   │           ├── Avatar.jsx
│   │           └── index.jsx
│   ├── hooks/
│   │   ├── useGetAllAdminJobs.js
│   │   └── index.js
│   ├── redux/
│   │   ├── applicationSlice.js
│   │   ├── jobSlice.js
│   │   └── store.js
│   ├── utils/
│   │   ├── constant.js
│   │   └── index.js
│   ├── App.jsx
│   ├── index.js
│   └── styles/
│       ├── global.css
│       └── index.css
├── .gitignore
├── package.json
├── README.md
└── yarn.lock

```

## Screenshots

<img src="https://github.com/nishkarsh25/VITE-SHADCN-MERN-REDUX-JobPortal/blob/main/Screenshots/ss1.png" alt="Screenshot 1" width="1000"> 
<img src="https://github.com/nishkarsh25/VITE-SHADCN-MERN-REDUX-JobPortal/blob/main/Screenshots/ss2.png" alt="Screenshot 1" width="1000"> 
<img src="https://github.com/nishkarsh25/VITE-SHADCN-MERN-REDUX-JobPortal/blob/main/Screenshots/ss3.png" alt="Screenshot 1" width="1000"> 
<img src="https://github.com/nishkarsh25/VITE-SHADCN-MERN-REDUX-JobPortal/blob/main/Screenshots/ss4.png" alt="Screenshot 1" width="1000"> 
<img src="https://github.com/nishkarsh25/VITE-SHADCN-MERN-REDUX-JobPortal/blob/main/Screenshots/ss5.png" alt="Screenshot 1" width="1000"> 
<img src="https://github.com/nishkarsh25/VITE-SHADCN-MERN-REDUX-JobPortal/blob/main/Screenshots/ss6.png" alt="Screenshot 1" width="1000"> 
<img src="https://github.com/nishkarsh25/VITE-SHADCN-MERN-REDUX-JobPortal/blob/main/Screenshots/ss7.png" alt="Screenshot 1" width="1000"> 


## GIF's

<img src="https://github.com/nishkarsh25/VITE-SHADCN-MERN-REDUX-JobPortal/blob/main/Screenshots/ss8.gif" alt="Screenshot 1" width="1000"> 

## Technologies Used

### Frontend
- **React**: A JavaScript library for building user interfaces. Utilized for creating reusable UI components and managing the application state.
- **Redux**: A state management library for JavaScript applications. Used to manage and centralize application state across the app.
- **React Router DOM**: A library for handling routing in React applications. Provides navigation capabilities between different pages and components.
- **Axios**: A promise-based HTTP client for making API requests. Used to interact with the backend server for data fetching and submission.
- **Tailwind CSS**: A utility-first CSS framework for creating custom designs without leaving your HTML. Used for styling and responsive design.
- **Shadcn UI**: A modern UI component library for React applications. Provides a set of components and design patterns for building sophisticated user interfaces with ease.

### Backend
- **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine. Used for building the server-side logic and API endpoints.
- **Express.js**: A web application framework for Node.js. Provides a robust set of features for building web and mobile applications, including middleware and routing.
- **MongoDB**: A NoSQL database for storing application data. Utilized for persisting user data, job postings, and application information.

### Authentication
- **JSON Web Tokens (JWT)**: A compact, URL-safe means of representing claims to be transferred between two parties. Used for secure authentication and authorization.

### Additional Libraries
- **Sonner**: A library for toast notifications. Provides a user-friendly way to display success and error messages.
- **Lucide React**: A collection of icons for React applications. Used for adding visual icons to the user interface.


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh



## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites

Before running the project, ensure you have the following installed:

- [Node.js](https://nodejs.org/en/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nishkarsh25/VITE-SHADCN-MERN-REDUX-JobPortal.git
   ```
2. Navigate to the project branch:

   ```bash
   git checkout <branch-name>
   ```
   Replace `<branch-name>` with the name of the branch you want to checkout.
   
3. Start the Backend Server: Launch the backend Node.js server.

   ```bash
   cd backend
   node index.js
   ```
4. Start the Frontend Development Server: Run the React development server for the frontend application.

   ```bash
   cd frontend
   npm start
   ```


## Usage

1. **Run the development server**:

   ```bash
   cd client
   npm start
   ```
2. **Open your browser** and navigate to http://localhost:5173 to view the app.

## How to Use

### Features

#### For Job Seekers
1. **Login and Signup**:
   - **Signup**: Create a new account by providing your email, password, and other required information.
   - **Login**: Access your account using your registered email and password.

2. **Browse Jobs**:
   - Navigate to the **Jobs** page to view available job listings.
   - Use the search and filter options to find jobs that match your preferences.

3. **Apply for Jobs**:
   - Click on a job listing to view the job details.
   - Submit your application by filling out the required fields and uploading your resume.

4. **View Job Descriptions**:
   - Click on a job title to view detailed information about the role, requirements, and the hiring company.

5. **Manage Profile**:
   - Update your personal information and review your application history from the **Profile** page.

#### For Recruiters
1. **Admin Dashboard**:
   - Access the admin dashboard to manage job postings, view applicants, and handle company profiles.

2. **Job Management**:
   - Create new job postings, edit existing ones, or delete them as needed.
   - Monitor job applications and update their status.

3. **Company Management**:
   - Add new companies and update existing company profiles.
   - Manage company details such as location and description.

4. **Applicant Tracking**:
   - Review job applicants and view their resumes.
   - Change the status of applications (e.g., accepted, rejected) and interact with applicants.

#### For Administrators
1. **Protected Routes**:
   - Ensure secure access to admin features. Only users with the role of 'recruiter' can access certain routes.

2. **Company and Job Post Management**:
   - Manage companies and job postings through a comprehensive admin interface.

3. **Application Status Management**:
   - Update the status of job applications and manage applicant interactions.

### API Endpoints

#### Authentication
- **POST /api/auth/login**
  - **Description**: Log in a user and return a JWT token.
  - **Body**: `{ "email": "string", "password": "string" }`
  - **Response**: `{ "token": "string", "user": { "id": "string", "role": "string" } }`

- **POST /api/auth/signup**
  - **Description**: Register a new user.
  - **Body**: `{ "email": "string", "password": "string", "role": "string" }`
  - **Response**: `{ "message": "User registered successfully" }`

#### Jobs
- **GET /api/jobs**
  - **Description**: Retrieve a list of all job postings.
  - **Response**: `{ "jobs": [ { "id": "string", "title": "string", "description": "string", "company": "string" } ] }`

- **POST /api/jobs/post**
  - **Description**: Create a new job posting.
  - **Body**: `{ "title": "string", "description": "string", "requirements": "string", "salary": "string", "location": "string", "jobType": "string", "experience": "string", "position": "number", "companyId": "string" }`
  - **Response**: `{ "success": true, "message": "Job posted successfully" }`

- **GET /api/jobs/:id**
  - **Description**: Retrieve details of a specific job posting by ID.
  - **Response**: `{ "job": { "id": "string", "title": "string", "description": "string", "company": "string", "requirements": "string", "salary": "string", "location": "string", "jobType": "string", "experience": "string", "position": "number" } }`

#### Applications
- **GET /api/applications/:id/applicants**
  - **Description**: Retrieve a list of applicants for a specific job posting.
  - **Response**: `{ "applications": [ { "id": "string", "applicant": { "fullname": "string", "email": "string", "phoneNumber": "string", "profile": { "resume": "string", "resumeOriginalName": "string" } }, "createdAt": "string" } ] }`

- **POST /api/applications/status/:id/update**
  - **Description**: Update the status of a job application.
  - **Body**: `{ "status": "string" }`
  - **Response**: `{ "success": true, "message": "Status updated successfully" }`

#### Companies
- **GET /api/companies**
  - **Description**: Retrieve a list of all companies.
  - **Response**: `{ "companies": [ { "id": "string", "name": "string", "description": "string", "location": "string" } ] }`

- **POST /api/companies/create**
  - **Description**: Create a new company profile.
  - **Body**: `{ "name": "string", "description": "string", "location": "string" }`
  - **Response**: `{ "success": true, "message": "Company created successfully" }`

- **GET /api/companies/:id**
  - **Description**: Retrieve details of a specific company by ID.
  - **Response**: `{ "company": { "id": "string", "name": "string", "description": "string", "location": "string" } }`




## Contributing

Contributions to this project are highly appreciated! Whether you discover bugs, have feature requests, or wish to contribute improvements, your input is valuable. Here's how you can contribute:

- **Report Issues:** If you encounter any bugs or issues while using MyCalculatorApp, please open an issue on the GitHub repository. Be sure to provide detailed information about the problem and steps to reproduce it.

- **Submit Pull Requests:** If you have enhancements or fixes to propose, feel free to submit a pull request. Contributions that improve the functionality, usability, or performance of this app are welcomed and encouraged.

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. **Fork the Repository**.
2. **Create a New Branch** (`git checkout -b feature/your-feature-name`).
3. **Make Your Changes**.
4. **Commit Your Changes** (`git commit -am 'Add some feature'`).
5. **Push to the Branch** (`git push origin feature/your-feature-name`).
6. **Create a New Pull Request**.

## License

This project is licensed under the [The 3-Clause BSD License](LICENSE).Feel free to explore, modify, and contribute to this project as you see fit. Your feedback and contributions are greatly appreciated! 🚀✨


## Acknowledgments

This project is made possible by the contributions and support of various individuals and communities. Special thanks to:

- **Tailwind CSS Team:** For developing Tailwind CSS, a versatile CSS framework that simplifies web development and enhances user interfaces.
  
- **Open Source Community:** For fostering collaboration, innovation, and the sharing of knowledge, which enriches projects like My Form Validation and makes them accessible to all.


## Credits

This project wouldn't be possible without the contributions of the following:

- **React**: A JavaScript library for building user interfaces. Visit [React](https://reactjs.org/) for more information.
  
- **Vite**: A fast build tool that serves your code via native ESM. Visit [Vite](https://vitejs.dev/) for more information.

- **Shadcn UI**: A component library providing a set of highly customizable UI components built for React. Visit [Shadcn UI](https://ui.shadcn.com/docs/installation/vite) for more information.
  
- **Tailwind CSS**: A utility-first CSS framework for creating custom designs rapidly. Visit [Tailwind CSS](https://tailwindcss.com/) for more information.

- **React Router**: React Router is a library for routing in React applications, allowing for navigation between different components. Visit [React Router](https://reactrouter.com/) for more information.

- **Redux**: Redux is a predictable state container for JavaScript applications, providing a centralized store for managing application state. Visit [Redux](https://redux.js.org/) for more information.

- **React Redux**: React Redux is the official React binding for Redux, enabling React components to interact with the Redux store. Visit [React Redux](https://react-redux.js.org/) for more information.

- **Axios**: Axios is a promise-based HTTP client for making asynchronous requests in JavaScript applications. Visit [Axios](https://axios-http.com/) for more information.

- **Express**: Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications. Visit [Express](https://expressjs.com/) for more information.

- **Mongoose**: Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node.js, providing a straightforward schema-based solution for modeling application data. Visit [Mongoose](https://mongoosejs.com/) for more information.

- **JSON Web Token (JWT)**: JSON Web Token is a compact, URL-safe means of representing claims to be transferred between two parties. It is commonly used for authentication and authorization in web applications. Visit [JWT](https://jwt.io/) for more information.

- **Netlify**: Netlify provides seamless deployment and hosting solutions, making it easy to deploy web applications and share them with the world. Visit [Netlify](https://www.netlify.com/) for more information.

- **Render**: Render offers a modern cloud platform for deploying and running web applications, databases, and other services. Visit [Render](https://render.com/) for more information.

- **MongoDB Atlas**: MongoDB Atlas is a fully managed cloud database service for modern applications. Visit [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for more information.



## Author

- **Nishkarsh Gupta**
  - GitHub: [nishkarsh25](https://github.com/nishkarsh25)
  - Email: bm21btech11016@gmail.com

