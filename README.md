# Introduction:
The Wordle game is a word-guessing game where players try to guess a word based on its category and length. The game challenges the player's vocabulary and deductive reasoning skills, making it an engaging and enjoyable experience. In this project, we have implemented the Wordle game using Prolog programming language.
# Functionality and Features:
The Wordle game offers the following features:
 - Category Selection: The player can choose from a list of available categories. This allows for customization and variety in the game.
 - Length Specification: The player can specify the desired length of the word to be guessed. This adds an additional challenge to the game.
 - Guessing and Feedback: The player can enter their word guesses, and the program provides feedback on correct letters and their positions in the word. This feedback helps the player make informed guesses.
 - Limited Attempts: The player has a limited number of attempts to guess the word correctly. This adds suspense and encourages strategic thinking.
The code ensures that the guessed word meets the specified length criteria and provides appropriate feedback based on the correctness of the letters and positions. This enhances the accuracy and fairness of the game.
# Usage Instructions and Data Base Creation:
To add words and categories to database, add them as facts of the form word(X,Y) where X is word and Y is category as shown in below figure.
# Playing instructions:
Run the program using a Prolog interpreter or environment. Enter “play.” as a query and follow the instructions printed. The program will display an introductory message. Choose a category from the provided list. Specify the desired length of the word. The program will randomly select a word from the chosen category and prompt you to enter your guess. Enter your guess as a word composed of the specified length. Based on your guess, the program will provide feedback on correct letters and their positions, and update the remaining guess count. Continue guessing until you either guess the word correctly or run out of attempts. The program will display a victory message if you guess the word correctly or a loss message if you exhaust all your attempts.
