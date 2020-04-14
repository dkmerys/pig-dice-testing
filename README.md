# _Pig Dice_

#### _Epicodus Project, Interactive Pig Dice Game April 14, 2020_

#### By _**Jessica Hvozdovich and Dan Merys**_
#### Version 1 Contributions by _**Khan Sahab**_

## Description

_This webpage allows a user to roll a die, amass points until they decide to "hold" or roll a one, causing them to forfeit all points accumulated, and then allow another player to do the same. Players accumulate points in between rounds, the highest score at the end of three rounds is the victor. This project is also being used to practice the Red Green Refactor testing workflow and configuring with Webpack._

## Setup/Installation Requirements

* Clone this repository.
* Navigate to index.html file.
* Right click and open in the browser of your choice.

## Known Bugs

There are currently issues linking functions between business logic and UI logic sections that prevent values from updating.
 
## Support and contact details

_Have a bug or an issue with this application? [Open a new issue](https://github.com/jhvozdovich/pig-dice-testing/issues) here on GitHub._

## Technologies Used

HTML
CSS
Bootstrap
Git and GitHub
JavaScript
jQuery
Jest
Babel
Webpack
ESLint

### Specs
| Spec | Input | Output |
| :------------- | :------------- | :------------- |
| **Initiate game** | User Input:"Click-Play" | Output: "Navigate from home screen to game page" |
| **Display initial totals** | User Input: "Click-Play" | Output: "Round 1, Player1 Total: 0, Player2 Total: 0, player1Playing : text, turnTotal"|
| **Click to roll die** | User Input: "Click-Roll" | Output: "5" |
| **Display player total** | User Input: "Click-Roll" | Output: "Roll: 5, Total: 10" |
| **Stops turn if roll 1** | User Input: "Click-Roll" | Output: "1, Player 2" |
| **Option to hold** | User Input: "Click-Hold" | Output: "player2Playing", turnTotal: 0 |
| **Count rounds after both players have had a turn** | User Input: "Player 2: Click-Hold" | Output: "Round 2" |
| **After round 3 display final score** | User Input: "Round 3: Player 2: Click-Hold" | Output: "Final Score Player 1: 12, Player 2: 21" |
| **Display option to play again** | User Input: "Click-Play Again" | Output: "Initial title screen" |


### License

This software is licensed under the MIT license.

Copyright (c) 2020 **_Jessica Hvozdovich and Dan Merys_**