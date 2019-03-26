# pig-dice

* Behavior: Generate random number between 1 and 6.
* **Example input:** "Roll"
* **Example output:** 5
* Behavior: Each random number is added to a turn total
* **Example input:** "Roll", "Roll"
* **Example output:** Each roll is a 5 an the turn total is 10
* Behavior: If player rolls a 1 their turn total is reset to 0
* **Example input:** "Roll"
* **Example output:** 1, turn total is 0
* Behavior: If player selects "hold", their turn total is added to their total score.
* **Example input:** 3, 4, 5, hold
* **Example output:** 12 is added to their total score.
* Behavior: When total score reaches 100, player wins and game ends.
* **Example input:** Total Score = 100
* **Example output:** "You win!"
