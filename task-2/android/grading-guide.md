## Grading Guide

### Feature 1: User has 3 chances to guess a random 4 letter word
**Total Possible Points: 4 points**

Examine student's GIF and make sure they can guess 3 different times

* Give half credit for any number of guesses (2 points)
* Give full credit for exactly 3 guesses (4 points)

For example, in this screenshot, you can see that the user guessed "star", "dogs", and "most"

<img src = "https://github.com/AlynMing/grader-hiring-task/blob/main/task-2/android/res/Wordle1.png" width="150" height="300">

-----

### Feature 2: After 3 guesses, user should no longer be able to submit another guess
**Total Possible Points: 4 points**

In student's GIF, after 3 guesses, it should be impossible to enter a 4th guess. Students may do this in a few different ways:

* Showing a Toast (pop-up message) that tells the user they've exceeded their number of guesses
* Graying out and disabling the 'Submit' button after 3 guesses have been made
* Showing a 'Reset' button instead of a 'Submit' button after 3 guesses have been made

If any of the above methods are implemented, score this feature complete  

----

### Feature 3: After each guess, user sees the "correctness" of the guess
**Total Possible Points: 4 points**

Examine student's GIF. After each guess, the app should display the "correctness" of that guess. This can be done in two ways:

* Option A: X's and O's
* Option B: Colored Letters

<img src = "https://github.com/AlynMing/grader-hiring-task/blob/main/task-2/android/res/Wordle2.png" width="300" height="300">

----

### Feature 4: After all guesses are taken, user can see the target word displayed
**Total Possible Points: 4 points**

Examine student's GIF and make sure that, after 3 guesses, the actual word is displayed. This should happen BOTH:

* When the user did not win the game (+2 pts)
* When the user did win the game (+2 pts)

In the example below, the word BOOK is displayed when the user losses the game. The word STAR is also shown when the user wins the game.

<img src = "https://github.com/AlynMing/grader-hiring-task/blob/main/task-2/android/res/Wordle3.png" width="350" height="300">


----
### Feature 5: User can toggle betweeen different word lists
**Total Possible Points:1 point**

To complete this feature, there should be a way for the user to change what words the game is using.</p>
Note: The programmer changing the word list outside of the app does not count. It must be done from within the app, and should be demonstrated in the GIF.</p>

---
### Feature 6: User can see the 'correctness' of their guess through colors on the word
**Total Possible Points:1 point**

This stretch feature is completed if they used color to show correctness. See Feature 3, Option B.

---
### Feature 7: User sees a visual change after guessing the correct word
**Total Possible Points:1 point**

To complete this feature, the app should show a new visual element when the game is won.

Examples:

* Confetti animation
* Displaying a star icon
* Screen changes color

----
### Feature 8: User can tap a 'Reset' button to get a new word and clear previous guesses
**Total Possible Points:1 point**

To complete this feature, the game should show a "Reset" button that restarts the game to its initial blank state. It does not matter if the reset button is always visible, or only appears after the game ends.

----
### Feature 9: User will get an error message if they input an invalid guess
**Total Possible Points:1 point**

To complete this feature, an error message should display if either:

* A guess is not exactly 4 letters
* A guess contains characters that are not alphabetical (A-Z)
  
Students should show the error message for BOTH cases above in their GIF.

--- 
### Feature 10: User can see a 'streak' record of how many words they've guessed correctly
**Total Possible Points:1 point**

The screen displays a "streak" of how many games have been won in a row. It should:
* Start at zero
* Go up by 1 when a game is won
* Reset to zero if a game is lost







