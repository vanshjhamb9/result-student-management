# GradeBook
GradeBook is a MERN Stack application designed to help teachers and educators manage their students' grades and percentage. It provides a user-friendly interface for recording, calculating, and analyzing student grades. This documentation will guide you through the installation process, usage instructions, and provide an overview of the features and functionalities of GradeBook.

## Features
### 1. User Authentication

- Secure user registration and login functionality.
- Password hashing with passport JWT for enhanced security.

### 2. Class Management

- Create, edit, and delete classes.
- Define the exams for each class.

### 3. Student Management

- Add, edit, and remove students.
- Store student information, including name, email, and additional details.

### 4. Grade Recording and Calculation

- Record student grades for exams.
- Automatic calculation of overall grades based on weightage.
- View and update student grades as necessary.

### 5. Report Generation

- Generate detailed reports for individual students.
- Include information such as percentage with verdicts.

## Installation

To set up GradeBook locally, follow these steps:

- Clone the repository:

      git clone https://github.com/OviSarkar62/GradeBook.git
      
- Navigate to the project directory:

      cd GradeBook

- Install the required dependencies for backend:

      npm i express dotenv colors bcryptjs joi jsonwebtoken mongoose nodemon zxcvbn
     
- Navigate to the client directory: 

       cd client
    
- Install the dependencies for the client: 

       npm i react-router-dom redux react-redux axios antd @reduxjs/toolkit react-hot-toast
    
- Create a .env file in the root directory with the following environment variables:

       DB_URL = mongodb+srv://<user>:<pass>@cluster0.l17quyr.mongodb.net/database

       JWT_SECRET = A_Secret_Value

- Start the server: 

       npm start
    
- In a new terminal window, navigate to the client directory:

       cd client
    
- Start the client: 

       npm start
    
- Access the application. Open your web browser and visit http://localhost:3000 to access the GradeBook application.

## Live Link

The live project: [GradeBook](https://grade-book-pi.vercel.app/)
