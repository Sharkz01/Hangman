# Hangman

* To play this game, you first need to choose the category that you would want to play with
* choose the level
* Based on that you will have to guess the word that the game has selected for you
* when you win you name will be stored in the leaderboard based on long it took you to guess the word
* you can also view the leaderboard

### To Run

* `python3 -m venv env (you do it one - to create the environments)`
* `source env/bin/activate`
* `pip install -r requirements.txt`
* `python3 hangman.py`

### To Test

* To run all the unittests: `python3 -m unittest tests/test_main.py`
* To run a specific step's unittest, e.g step *1*: `python3 -m unittest tests.test_main.MyTestCase.test_step1`