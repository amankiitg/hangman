# Hangman Game Challenge

This repository contains Python code for a Hangman Game challenge. The Hangman game is a classic word guessing game where one player thinks of a word and the other player tries to guess it by suggesting letters within a certain number of attempts.

## Features

The Hangman Game in this repository includes the following features:

1. **Frequency of Vowels**: The game analyzes the frequency of vowels in the dictionary to make informed guesses.

2. **Smart Guessing**: It chooses the next guess letter based on the highest frequency letter in the dictionary.

3. **Avoidance of High Vowel Proportions**: If the proportion of vowels in the obscured word is high, it avoids predicting vowels again to increase the chances of guessing the word correctly.

4. **N-Gram Analysis**: For longer words, the game breaks down the words into N/2 or N/3 gram words and tries to guess the word using information from words of similar length in the N-Gram dictionary.

5. **Smart N-Gram Guessing**: When using the N-Gram dictionary, it employs the highest frequency approach to guess the next letter.

6. **N-Gram Example**: Example of N-Gram calculation: P(blank = ‘o’| pe_ple) = [count(peo) + count(eop) + count(opl) ]/ total trigrams (all trigrams possible)

7. **Training Success Rate**: The training success rate during practice is more than 50%.

