## Step-by-step process

1. write an input function that gives you 2 options and a way to select one

2. for the first option, have an input function that lets you enter the question, then asks for 4 options for a multiple choice
answer (separated by commas), then asks for topic tags (separated by commas). 
	+ the text inputted needs to be written as a string
	+ ask for correct answer (assign this to its own key)
	+ ask for 3 incorrect answers, put them into a list
	+ ask for topic tags, put into a list
	+ all of this data needs to be entered into a dictionary and saved to a CSV file.

```
dict = {
	"question number": integer, # incremental 
	"question" : "string", 
	"correct answer" : "string"
	"incorrect answers" : ["wrong answer", "wrong answer", "wrong answer"],
	"topic tags": ["tag1", "tag2", "tag3"]
}
```

3. for the review option, write a function that picks a random question from the CSV file (should each question have a number assigned?)
	+ open the CSV, count the number of dictionaries.
	+ there needs to be a function that generates a random number with a range stipulated by the number of questions in the CSV file. 
	+ read the dictionary, print the question with all 4 options in random order, with labels a, b, c and d. 
	+ an input box that asks for your answer to the current question. a, b, c and d 
	+ a message that tells you if you are correct or incorrect, and displays the correct answer if answered incorrectly.
	+ a prompt that asks if you would like another question or to quit the current session. 

+ *the CSV needs to be loaded when the user starts the application*