# Quizzer

This ReactJS web application, built with Vite, is designed to take user input, present 15 quiz questions, collect user responses, and generate a report at the end.

## Demo

![](https://github.com/Pushpendra766/codelab/blob/main/client/src/assets/codelab.gif)

## Live Preview

You can see live preview here - [Quizzer](https://quizzer766.netlify.app/)

## Getting Started 

To get started with this project, clone the repository and install the dependencies:
```
1. git clone https://github.com/Pushpendra766/quiz-app.git
2. cd quiz-app
3. npm install
```

## Development

To run the development server:

 `npm run dev`

This will start the development server at `http://127.0.0.1:5173/`

## Approach to the Problem

The Quiz App was created with the goal of providing an interactive and user-friendly platform for users to test their knowledge. Here's an overview of the application's components:

**Front Page:** The app begins by welcoming the user and prompting them to enter their name and email before starting the quiz.

**Quiz Questions:** After entering their details, users are presented with 15 quiz questions one by one. They can select their answers for each question.

**Report Generation:** Once all questions have been answered, the app calculates the user's score and generates a report, displaying their name, email, and the percentage of correct answers.

## Components
The major components of this application include:

**App:** The main component that handles user data input, quiz logic, and report generation.
**Question:** A component responsible for rendering individual quiz questions.
**Timer:** Displays the timer and handle submit if timer ends.
**Report:** Displays the user's report at the end of the quiz.

