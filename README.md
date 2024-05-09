* In the project I learned Quiz App how to change question and answer dynamically.
* click on option 
on "button" it triggers and automatically passes the next question 
by using 'currentquestion' variable and 'answeroptions' also
 And also about this map it takes the current value and it passed the value(answerOption) in map all the four options
will go and by condition it verifies the correct answer and count for the final score.
 {questions[currentQuestion].answerOptions.map((answerOption) =>(
                  <button onClick={()=> handleAnswerButtonClick(answerOption.isCorrect)}>{answerOption.answerText}</button>
               


![image](https://github.com/Vasanthkarri/Quiz-App-6/assets/95275323/b3e4150d-16d7-49f1-821e-40413305448e)
![image](https://github.com/Vasanthkarri/Quiz-App-6/assets/95275323/03e8f579-a68a-4716-b228-28c2d89ef204)
