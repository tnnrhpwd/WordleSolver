# WordleSolver
## This is the **repository** for my _Wordle Solver_ page.
---
### Files
There are three primary files. The Js and CSS files are uploaded to Weebly, and the HTML is copy/pasted to the target Weebly section.

### The Goal
The main goal of this file is to output a list of words that matches the user's game criteria. This allows them to predict the answer to a high certainty.

The HTML page loads. The javscript file is executed. Initialize() creates the starting elements on the page, while also initializing the input collecting methods. 

The guess word is typed into the textbox. Either press the Run button or press your enter key. Enter the word results replacing green, orange, and black with 123 respectively. For example, if the guess was 'guess' and all the letters were correct, then the results input would be '11111'. If all the letters were wrong, the input would be '33333'.

Press run or your Enter key again. The list of potential words is printed. Type one of these words into the textbox and your game. 
Repeat these steps until you either win or lose your game.

The application works by filling an array with a list of potential words on the first button press. Then, on even even button press, passing words are added to a temporary array from the intial array. The initial array is emptied and filled with the temporary array data. Lastly, the initial array is outputed to the html, displaying the list of potential words.

[View website](https://sthopwood.weebly.com/wordlesolver.html)
