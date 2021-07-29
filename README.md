# Project_Pomodoro_Timer_Qualified_1
Learning objectives
This project is designed to test your ability to work with rendering and state management using React. Before taking on this project, you should be comfortable with the learning objectives listed below:

Installing packages via NPM
Running tests from the command line
Writing React function components
Using hooks like useState()
Debugging React code through console output
Steps to complete
To complete this project, you must do the following:

Write code that passes all the tests in the Qualified assessment in this checkpoint.
Write code that passes all of the requirements in the project rubric below, and submit your GitHub repo link to the Thinkful team in the next checkpoint.
Remember to sync this Qualified project with your local machine so that you can commit it to GitHub in the next checkpoint.

Project rubric
For your project to pass, all of the following statements must be true.

All tests are passing in Qualified.
All props are treated as read-only.
Audio plays when the focus timer expires.
Audio plays when the break timer expires.
All state is updated using callbacks to avoid race conditions. Allowable exceptions are cases where the next state is not determined by the current state. For example, when disabling the timer, it is okay to just call setIsTimerRunning(false).
There are at least three components.
Each component has a single responsibility.
The main Pomodoro is free of any conditional display logic. This means that there aren't any if statements in the render function; each component determines its own visibility.
