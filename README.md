Hangman Wiki:

The origins of Hangman are obscure meaning not discovered, but it seems to have arisen in Victorian times, ” says Tony Augarde, author of The Oxford Guide to Word Games. The game is mentioned in Alice Bertha Gomme’s “Traditional Games” in 1894 under the name “Birds, Beasts and Fishes.” The rules are simple; a player writes down the first and last letters of a word and another player guesses the letters in between. In other sources, [where?] the game is called “Gallows”, “The Game of Hangin”, or “Hanger”. 

Implementation:

This is a simple Hangman game using Python programming language. Beginners can use this as a small project to boost their programming skills and understanding logic.  

The Hangman program randomly selects a secret word from a list of secret words. The random module will provide this ability, so line 1 in program imports it.
The Game: Here, a random word (a fruit name) is picked up from our collection and the player gets limited chances to win the game.
When a letter in that word is guessed correctly, that letter position in the word is made visible. In this way, all letters of the word are to be guessed before all the chances are over. 
For convenience, we have given length of word + 2 chances. For example, word to be guessed is mango, then user gets 5 + 2 = 7 chances, as mango is a five-letter word.
Code Explanation:

The code starts by importing the random module.
This module provides a way to generate random numbers.
Next, the code creates someWords, which is a list of fruit names.
The list is split into spaces using the string ‘ ‘, and then each space is replaced with a letter.
Next, the code randomly selects a secret word from our someWords list.
This word will be used as the input for the game later on.
The next part of the code checks to see if the user has entered an alpha character (a letter that appears in front of other letters).
If not, then they are asked to enter only a letter.
If they enter an alpha character, then it’s assumed that they want to guess at another letter in word .
So, this part of the code checks to see if guess matches one of the letters in word .
If it does, then chances is updated and flag is set to 1 .
Otherwise, chances is decreased by 1 and flag remains at 0 .
The next part of the code tries to guess at another letter in word .
If guess isn’t valid (i.e., it doesn’t match any of the letters in word ), then print() prints out all empty spaces for letters in word , and
The code starts by importing the random module.
This module provides us with a number of useful functions, one of which is the choice function.
This function allows us to randomly choose a secret word from our list of words.
Next, we create some variables which will be used throughout the program.
These include someWords , word and letterGuessed .
letterGuessed will store the letter guessed by the player, while chances will store the number of times that the player has correctly guessed the word so far.
correct will keep track of how many letters have been guessed so far and flag will indicate whether or not the player has guessed the word correctly.
We then start looping through our list of words and randomly choosing a secret word from it.
