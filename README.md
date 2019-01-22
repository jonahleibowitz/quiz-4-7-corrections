# quiz-4-7-corrections

## Quiz 4
Question 1: When you console.log strings and variables seperated by a comma, the comma will not be logged. I selected the option with the comma. 

Question 6: This question had multiple correct ways to print to a paragraph using javascript. I only chose one of them.

Question 10: I chose two correct answers for this problem but it graded one of them wrong.*


## Quiz 5
Question 2: This question asked me to choose all of the valid logical operators. Instead, I selected the comparison operators. The correct answers were &&, ||, and !. These are the actual logical operators.

Question 4: A string is set to variable a. There are then two console.logs. One is set to print "(!a)" and the other is set to print "(!!a)" . The two !s in the second statement should cancel out to log true to the console while. The first one has only one ! so it should still log false.

Question 7: This question asked me to select a list of cases from a few possibilites that has the correct syntax. I simply chose the wrong one. The list I chose was almost entirely correct but the case numbers had quotation marks around them when they shouldn't have.

Question 9: This question asked for the simplest way to determine someone's letter grade. I chose a properly coded set of cases. However, the correct answer was an if statement that did the same thing. The If statements were the simpler method of writing the code so I got the question wrong.

Question 12: For this question, rather than get answers wrong, I only selected one of 2 correct answers. I was supposed so select all do...while loops that would work properly. For whatever reason, I felt that one of the loops (which would decrease variable x by 1 until it was less than or equal to 100) wouldn't work when it certainly would.

Question 13: This question asked me to choose the correct sequence of events for a for loop. I got two of the steps reversed. The loop body occurs before the update but I said the opposite.

Question 14: I said that anything written in a while loop couldn't be achieved by a for loop. This is false. The two are basically interchangeable and more about personal preference and meaning than actual functional difference.



## Quiz 6
Question 1: When fewer arguments are passed in than there are parameters, only the parameters that haven't recieved an argument will be undefined. Only the parameters that recieve arguments will be able to work so any parameters that don't recieve an argument simply can't do anything than return as undefined.

Question 2:   ```function power(base, exponent) {/* implementation not shown */ }``` would be a better code than                              ```function raise(x, y) {/* implementation not shown */ }``` because the variables and function name are much more descriptive. It will be easier to understand how the function works and what its purpose is.

Question 3: I said that the mystery function was designed to accept parameters while in fact, it was not. There were no variables inside of the parentheses so no arguments could be given. Without these arguments there would be no way to return a value either which I also said it would.

Question 6: Prompt was the only of the four built-in function that is designed to return a value. Console.log, alert, and math.random all transmit information for the developer or user to see, but don't return values that can then be used in the code for a purpose. Prompt allows the user to input information which can then be used by the code to carry out a task.


## Quiz 7
Question 4: This question asks you to identify which set of numbers in an array would prove that a function doesn't always work. The function is used to identify the largest number in the array. It does this by setting a variable equal to 0 and then assessing each number in order to see if it is larger than the value the variable is currently set to. The number after the whole array has been cycled through should be the largest. However, the correct answer has an array with only negative numbers (which are all less than 0) so the variable would never get assigned a new number. This proves that the function won't always work.

Question 6: This question asked me to select the proper content of an array after a function was applied that populates it. The function multiplies each integer from 0 by 2 and pushes it to the array. The function uses a for loop which is set to terminate when i is equal to 9. This means the last number in the array should be 18. I chose the option that cycled through one more time and had a last value of 20 (10*2).

Question 7: I answered this question correctly and was awarded the point but the answer key says that I chose the wrong answer.*

Question 13: I was supposed to choose all methods that would determine that a value was or wasn't in the array. I said ```cars.lastIndexOf(car) !== -1```wouldn't work. I didn't know that this method returned -1 if the value wasn't there. Since this is looking to see if the index isn't -1, it would properly determine if the value was there or not.

*= questions I got right but was marked wrong
