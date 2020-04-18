# BenG2020


# The Office Hangman 

======================================================
## Concept: 
=======================================================

A word guessing game for one player. It is based around the theme of the hit tv show the office. 
The computer selects a word from the array and the user has to pick letter by letter from the keyboard. When a correct letter is picked it will fill out the current word, when an incorrect letter is picked, the guesses counter logs is as a penalty and the letters function will log that word used, removing it from the array. If there are 10 penalties the game is over displaying the Lose image. If the user selects all correct words then the winning image is displayed. The user can continue the game by clicking any keys. 


## Technologies Used:
    - HTML
    - CSS
    - JAVASCRIPT


## Approach: 
I wanted to make a hangman game based around the Office as it's one of my favourite tv shows. Instead of building the hangman on each wrong word picked, i wanted the computer to log the words and then provide the user with an image as a reward for getting the word right or the same image over and over when getting the word wrong. 


## Challenges: 
Getting the CSS down was tricky as each image was of a different size. After speaking to Bruno i should have gone into Adobe and alter the dimensions of all the images and refactor the classes so that the CSS would be easier to manipulate. 

## Unsolved Problems
- Fixing the css so the code is cleaner. The way i did the positioning of the images is a temporary fix. 
- Add responsiveness to the pages. Right now if the windows is closed to little the grid will not display correctly. 
- Include more words to the array and improve the wordChoice so that it does show the same word twice in a row. 


## App Demo 
Please take a look at my project

https://glouton-2020.github.io/
