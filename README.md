# Random Word Generator
Objectives:
* Practice setting up a Django project
* Practice passing data to a template
* Practice using Django session
* If you don't feel comfortable with multiple apps yet, start a new project with a single app for this assignment. Otherwise, add an app to your previous project called 'random_word'. This app will render a template with a random 14-character "word" that also display a counter for the number of words generated. The first time you use this app, it should say 'attempt #1'. Each time you generate a new random keyword, it should increment the attempt figure. The purpose of this assignment is to reinforce your use of session. Don't spend too much time on the random word generator portion--it's okay if your random word is not a real word.
* Add functionality so that a request to localhost:8000/random_word/reset resets the counter and redirects back to localhost:8000/random_word.