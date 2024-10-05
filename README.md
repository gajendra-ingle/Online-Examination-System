# Online Examination System

## Overview

The Online Examination System is a Java application that simulates a basic examination platform. Users can log in, update their profile, start an exam, and log out. The exam is timed, and after completion or time expiry, results are displayed.

## Features

- User authentication (login/logout)
- Profile and password management (placeholder for future implementation)
- Timed examination with a fixed duration
- Basic multiple-choice questions (MCQs)
- Result display after exam completion

## Technologies Used

- **Java**: The primary programming language used for implementing the application.
- **Java Timer**: Utilized to manage the exam timer, allowing the system to auto-submit when time runs out.
- **Scanner**: To capture user input for login and answers during the exam.

## Key Concepts Learned

1. **Object-Oriented Programming (OOP)**:
   - The `User` class demonstrates encapsulation by storing user credentials and providing access through getter methods.

2. **Control Flow**:
   - The application uses loops and switch-case statements to handle user interactions and decisions, ensuring a user-friendly interface.

3. **Timer and TimerTask**:
   - The `Timer` and `TimerTask` classes are leveraged to manage the countdown for the exam, showcasing how to run scheduled tasks in Java.

4. **Input Handling**:
   - The `Scanner` class is employed for capturing user input, which is crucial for interactive applications.

5. **Error Handling**:
   - Basic error handling is implemented for user choices, prompting them for valid inputs when necessary.

## Structure

- **User Class**: Represents a user with a username and password.
- **OnlineExaminationSystem Class**: The main class containing methods for login, profile update, exam handling, and session management.

## How to Run

1. Ensure you have Java Development Kit (JDK) installed on your machine.
2. Copy the code into a file named `OnlineExaminationSystem.java`.
3. Open a terminal or command prompt and navigate to the directory containing the file.
4. Compile the program:
   ```bash
   javac OnlineExaminationSystem.java
