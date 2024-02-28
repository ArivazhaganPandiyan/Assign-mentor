# Mentor-Student Relationship Management API

This repository contains the backend code for an API designed to manage mentors and students and facilitate the assignment of students to mentors.

## Quick Start Guide

Our API server is conveniently hosted at: `https://assigning-mentor-and-student.onrender.com`

## Key API Endpoints

1. **Create Mentor (POST)**: Establish a new mentor profile.
   - Endpoint: `/mentor/createMentor`

2. **Create Student (POST)**: Register a new student.
   - Endpoint: `/student/createStudent`

3. **Assign Student to Mentor (POST)**: Link a student to a mentor, fostering a learning relationship.
   - Endpoint: `/assignment/assignStudent/:mentorId/:studentId`

4. **Assign or Change Mentor for Student (PUT)**: Assign a new mentor to a student or modify an existing mentor-student relationship.
   - Endpoint: `/assignment/assignOrChangeMentor/:studentId/:newMentorId`

5. **Get All Students for a Mentor (GET)**: Retrieve a comprehensive list of all students under the guidance of a specific mentor.
   - Endpoint: `/mentor/getAllStudents/:mentorId`

6. **Get Previously Assigned Mentor for a Student (GET)**: Access the historical data of a student's previously assigned mentor.
   - Endpoint: `/student/getPreviousMentor/:studentId`

# Technologies Used
Node.js: Backend server environment
Express.js: Web framework for Node.js
Mongoose: MongoDB object modeling tool for Node.js
dotenv: Environment variable management
Postman: API development and testing

## Detailed Documentation

# Postman API Test
Screenshots of Postman API test requests and responses have been included in the repository. You can find them in the **postman-tests** directory.

# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.


