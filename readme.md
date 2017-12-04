# Hangman game

Hello! Your task is to create hangman game using **ONLY** HTML, CSS and JS (__no libraries, no frameworks__).

The data to use for the game is in __assets/data.js__ file.

The game should consist of 5 screens:

1. Welcome/Menu with 3 options to choose
    1. Start the game
    2. Show categories
    3. Show scoreboard 
2. Show categories should display all the unique categories listed in objects in data file

3. Show scoreboard should display 10 (or less if there's less) best times of users who played game and their names

4. Main game screen should consist of:
    1. The password to guess should be chosen randomly from the data file
      * if user fills the password completely he wins
    2. The cathegory of the password should be displayed
    3. There should be password guessing area with the letters that user have already guessed
    4. There should be amount of tries user has left, decrementing every time he won't guess the letter in a password. We don't draw the hangman, we just decrement the amount of tries user has, but you can of course draw some kind of hangman if you'd like.
        * if amount of the tries goes to 0 user loses
    5. There should be an input and the confirmation (OK) button to specify the letter (if the user inputs again the same letter it can be ignored or user can get a warning about that event)
    6. There should be an input to provide full answer and the confirmation button.
        * if user inputs wrong password he loses
        * if user fills the password correctly he wins
    7. There should be a button 'show hint' to show the hint provided for each password in data.js file

  5. The summary screen
      * user is shown his time and is asked for name if he wins
      * user is shown "You lost" sentence if he loses
    

### Please provide your code as link to github repository or (eventually ) zip file.

Hints:

* I will recommend taking a look at: https://invis.io/M6ESK3VDE which provides wireframes as possible looks of the app, don't hesitate to improve and change them, though
* I will recommend using [Visual Studio Code](https://code.visualstudio.com/) as Text Editor
* [LocalStorage](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API/Using_the_Web_Storage_API) can be used to hold and maintain the data about the scoreboard
* We don't expect you to implement all functionalities, just see how far you can go with that.
* I can be reached at https://discordapp.com/invite/reasonml room as wojciech.bilicki for further hints and explanation from 8 AM to 4 PM Monday-Friday or wojciech.bilicki@oke.pl


