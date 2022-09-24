# wordle-clone

Purpose of this project is to build a wordle clone.

Plan:
- Use an array of words in which we are going to pull a word to use as our answer. We are also going to the that array word list to validate the user's response so that just like Wordle it will reject the user's input if they decide to put in 'spaghetti' words (eg. asdfg).
- Create a basic skeleton/framework of how a round of the game will work.
- Create a 5 x 6 grid (similar to Wordle) using HTML. User should only be able to fill out one row at a time. Only until user fulfills the following conditions can they move onto next row/attempt (unless they get the answer):
    - Must be a valid word (must be included in our word bank array)
    - Must be 5 letters
- For our grid, need to ID each row so that letters are input in the correct row.
- Each letter input by user will be pushed into an array 
