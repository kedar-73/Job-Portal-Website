# Job Portal Application (MERN Stack)

A full-stack job portal application built using the MERN (MongoDB, Express, React.js, Node.js) stack. This project allows users to search, apply, and browse for jobs by various categories.

## Features

- **Job Search and Filter**: Users can search for jobs based on keywords and filter by roles like Frontend Developer, Backend Developer, and Data Engineer.
- **Responsive UI/UX**: The frontend is built with React.js to ensure a smooth user experience across all devices.
- **Backend API**: The backend is powered by Node.js and Express.js to handle requests and manage job postings.
- **MongoDB Database**: MongoDB is used for storing and retrieving job data dynamically.
- **User Authentication**: Secure user authentication for job application processes.

## Technologies Used

- **Frontend**: React.js, HTML, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Other Tools**: Git, GitHub

## Installation and Setup Instructions

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/job-portal.git
    ```

2. Navigate to the project directory:

    ```bash
    cd job-portal
    ```

3. Install the necessary dependencies for both the client and server:

    ```bash
    # Install dependencies for the backend
    cd backend
    npm install
    
    # Install dependencies for the frontend
    cd ../frontend
    npm install
    ```

4. Create a `.env` file in the `backend` directory and add your environment variables, such as the MongoDB URI and other sensitive information:

    ```env
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

5. Start the development server:

    ```bash
    # Start the backend server
    cd backend
    npm run dev
    
    # Start the frontend
    cd ../frontend
    npm start
    ```

6. Open the app in your browser:

    ```bash
    http://localhost:3000
    ```

## Made by-Kedar Singh
