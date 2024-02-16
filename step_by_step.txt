## Step-by-step process

1. write an input function that gives you 2 options and a way to select one

2. for the first option, have an input function that lets you enter the question, then askes for 4 options for a multiple choice
answer, then asks for topic tags. 
	+ the text inputted needs to be written as a string
	+ put the multiple choices into a list. Specify which answer is correct.
	+ put the topic tags into a list
	+ all of this data needs to be entered into a dictionary and saved to a CSV file.

3. for the review option, write a function that picks a random question from the CSV file (should each question have a number 
assigned?)
	+ there needs to be a function that generates a random number with a range stipulated by the number of questions in the CSV file. 
	+ read the dictionary, print the question with all 4 options, with labels a, b, c and d. 
	+ an input box that asks for your answer to the current question
	+ a message that tells you if you are correct or incorrect, and displays the correct answer if answered incorrectly.
	+ a prompt that asks if you would like another question or to quit the current session. 

+ *the CSV needs to be loaded with the user starts the application*