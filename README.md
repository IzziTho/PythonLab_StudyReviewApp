# StudyReviewApp

## Python Fundamentals Lab
Create an app that allows users to create and manage review questions in preparation for an upcoming exam.

## Study Review

### User Stories
1. When I start up the application, I am given a choice between the following options:
	+ Begin a review session
	+ Add a new question to the list
2. If I choose to add a new question, I am asked to provide:
	+ The question text
	+ A list of possible responses separated by commas
	+ Designation of which response is correct
	+ A list of topic tags separated by commas
3. If I choose to start a review session:
	+ The program presents a random question from the question list
	+ I am provided the question text and all response options with labels 
	+ I am prompted to provide my response using the labels presented
	+ The program informs me of the correct answer
	+ I am prompted to choose whether to continue the session or quit

### Technical requirements
+ Store the list of created questions in a .csv file
+ Load the previously created questions when the user initializes the application

### Stretch goals
1. The program allows you to limit the session to questions from a specific topic
2. The program keeps track of your right and wrong answers to each question
3. The program uses some logical system for giving you questions you've answered wrong
4. The program allows you to load questions from different tests, tracked in different files
5. The program tracks the average time you've taken to answer each specific question
