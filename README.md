MTM6302-capstone-liu00633
name:liu yang
student number:041051689
the steps for creating quiz site:
1. build  index.html/main.css/script.js files in capstone folder
2. in javascript  define the variables that should be used in use token generated form quizAPI to fetch dynamic quiz; then parse into object
3.creates functions:
startQuiz():Starts the quiz by displaying the first question and hiding the difficulty selection form.
displayQuestion():Populates the question and possible answers dynamically into the page.
Adds checkboxes for each possible answer by using 
getCorrectAnswers():
Returns an array of the correct answers for the current question.
selectAnswer():Handles the user's answer submission.
Compares the selected answers with the correct answers and updates the score.
Displays whether the selected answer is correct or incorrect.
reloadPage():Reloads the page after a short delay to prepare for the next question.
Reset and Restart Handlers:

Listens for button clicks to reset the score (resetScoreButton) or restart the quiz (restartQuizButton).
Local Storage
The quiz uses localStorage to persist the score data (correct and incorrect counts).

Buttons and Actions
Submit Answer Button: Submits the selected answers and evaluates whether they are correct or not.

Reset Score Button: Resets the correct and incorrect counts to 0.
Restart Quiz Button: Restarts the quiz, resetting scores and showing the difficulty selection form again.
