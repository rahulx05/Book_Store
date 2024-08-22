# Book_Store


BookStore is a full-stack web application where users can browse, review, and purchase books. To review or purchase books, users must have an account.

The project is built using Node.js, Express, MongoDB, and React, with Tailwind CSS and DaisyUI handling the frontend design, and Passport.js handling authentication.

## Functionalities

- **Browse Books:** Everyone can browse the books and read reviews without signing up or logging in.
- **User Authentication:** Users must log in to add or edit book reviews.
- **Book Purchase:** Logged-in users can purchase books directly from the platform.
- **Ownership:** Users can only edit or delete the reviews that they have written.
- **Responsive Design:** The application is fully responsive and adapts to various screen sizes.
- **Persistent Data:** All data is stored persistently using MongoDB Atlas.

## Technologies Used

- **React:** JavaScript library for building user interfaces.
- **Tailwind CSS:** Utility-first CSS framework for styling.
- **DaisyUI:** Tailwind CSS component library for easy UI design.
- **Node.js:** JavaScript runtime for executing server-side code.
- **Express.js:** Web framework for building APIs and handling routing.
- **MongoDB:** NoSQL database used to store user info, book details, and reviews.
- **Mongoose:** ODM library for MongoDB and Node.js.
- **PassportJS:** Authentication middleware for Node.js, managing user login and registration.
- **Axios:** Promise-based HTTP client for the browser and Node.js, used for making API requests.
- **React Router:** Library for managing routing in React applications.
- **Nodemon:** Utility that monitors changes in the source code and automatically restarts the server.
- **Bcrypt:** Library to hash passwords, enhancing security.
- **Postman:** API testing tool used during development.
- **Heroku:** Cloud platform used for deploying the web application.

## Features

### Frontend
- **Responsive Design:** The application is fully responsive and adapts to various screen sizes.
- **Dynamic Routing:** Managed by React Router, enabling navigation between different pages.
- **Tailwind CSS & DaisyUI:** Used for styling components like the navigation bar, cards, and forms.
- **React Hooks:** Used for managing state and side effects throughout the application.

### Backend
- **Express API:** Serves as the backend for handling data requests.
- **Mongoose ODM:** Manages data schemas and interactions with MongoDB.
- **User Authentication:** Implemented using JWT tokens, with secure password hashing via bcrypt.

### Additional Features
- **Slick Slider:** Used for creating responsive carousels within the application.
- **API Testing:** Conducted using Postman for verifying routes and data handling.
- **Environment Variables:** Managed using dotenv for enhanced security and flexibility.

## Installation and Setup

### Prerequisites

Ensure you have the following installed:

- **Node.js** (LTS version recommended)
- **MongoDB Compass** (for local database management)
- **Git** (for version control)

### Steps to Run the Project Locally

1. **Clone the Repository**
   ```bash
   git clone <repository-url>


### Steps to Run the Project Locally

1. **Clone the Repository**

   ```bash
   git clone <repository-url>

2. **Frontend**
cd frontend
npm install

3. **Backend**
cd ../backend
npm install

4. **Run**
   
Frontend: npm run dev

Backend: npm start


