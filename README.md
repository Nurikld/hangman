# [Game Hangman](https://en.wikipedia.org/wiki/Hangman_(game))
___

This is version of the classic letter guessing game called Hangman.
___

## Game rules:

+ You are shown a set of blank letters that match a word or phrase and you have to guess what these letters are to reveal the hidden word.
+ If you enter the wrong letter twice, the program will not count it as an error.
+ If you enter letters (Е or Ё) or (И or Й) - the program will open both of those letters in the puzzled word or add them to the wrong answers.
+ Try to guess the word before you get 7 mistakes and win!
___

## The game is written in [Ruby](https://en.wikipedia.org/wiki/Ruby_(programming_language))

### Guide

+ Requirements: having a Ruby interpreter.
+ Download the program
```
git@github.com/Nurikld/hangman.git
```
+ To run it you have to go to the terminal directory with the program and run it with the following command:
```
$ ruby main.rb
```
+ Press Enter.
+ You can also change the game words in the file - words.txt ~hangman/blob/master/data/words.txt
___
