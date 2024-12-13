# Wordle
A simple Wordle-like game in Python.

This project aims to create a simple version of the popular Wordle game in Russian.

The project contains several scripts (in this case, I did not combine them into one, for greater clarity):
  - The first script `GetSlovarOzhegova.ipynb` collects words from an online dictionary [slovarozhegova.ru] and writes them to an excel file;
  - The second script `GetFiveLetterWords.ipynb` processes all words received earlier (removes extra spaces, numbers, and extra characters from words) and writes only words consisting of 5 letters to the file;
  - The file `Wordle.ipynb` is a Wordle game for guessing words in Russian.

All data in excel files is located in the data folder.
If necessary, you can change the length of the guessed words and the number of attempts in the code.

If there is no need to collect words for the game (all words from the dictionary are recorded in the file `Wordle/data/slovarozhegova.xlsx`, and the words for the game in the file `Wordle/data/df_5_letters.xlsx`), then you don't need to run the `GetSlovarOzhegova` and `GetFiveLetterWords` files.

To change the length of the guessed words in the game, you need to change the code `GetFiveLetterWords.ipynb`\
To change the number of attempts - `Wordle.ipynb`
