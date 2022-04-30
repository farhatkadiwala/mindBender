_**Mind Bender**_

coded in: _python_ 
modules used:   _Random_ , _Tkinter_
contributed by: **Tech Ninjas**
***
description:
This is a simple word guessing game that intends for you to kill boredom and learn/revise some general knowledge while at it.
---
how it works (user-end):
* A homepage allows you to select thew subject around which you want to be guessing words.
* Once you select the module that you want to be working with, a new window will pop up.
* A _hidden word_ will be put up by showcasing only the first letter and hiding the rest of the letters.
* A hint will be displayed that will help you guess it better
* The number of blanks will be appropriate so as to signify the length of the word.
* You can guess your word in an input box (rectangle really, but that's just how we roll :) ) 
* Press the 'Lock this' button to check whether the guess is correct
* If the guess is correct, you move onto another guess, but **wait**, before this, you get a link to _read_ and _learn_ facts about the chosen module.
* Then the game goes on for 10 times
* You get 3 tries for each word
---
how it works (programmer-end):
* The logic that goes on the backend is: 
    * the words are all stored in a list. 
    * the hints are stored in a nested list and the number of nested lists is equal to the number of words. 
    * each iteration figures out the index of the word in question and iterates through its nested loop to print the hints.
    * the above logic is supported by conditional statements.
