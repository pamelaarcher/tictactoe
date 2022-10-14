# TicTacToe

## Table of content

- [Description](#description)
- [How to Run the Application](#about)
- [Future Improvements](#future-mprovement)
- [License](#license)
- [Demo](#demo)

## Description
This is a simple React application which displays a Tic Tac Toe board with nine squares and info about the next player and resulting winner.

## Setting Up and Running The Application

### About
This application is made up of 3 main files
  - <b>styles.css</b> which includes the styles for the board, squares and player info
  - <b>index.html</b> which includes the linked css and js source libraries as well as the React component tictactoe.jsx
  - <b>tictactoe.jsx</b> contains the Game, Board and Square components.

### Running the Application
 1. You can download these 3 files to a directory on your local drive.  
 2. Once installed in a directory, run an http-server from the directory and identify the ip/port number used 
 3. Open your browser and enter *ip:port*/index.html from input line
 
### Future Improvements
*	Include a button to play another game - I would create a new const "Games" that includes a button that when clicked unmounts current game if one exists and renders "Game".   If no game exists it will render one.   This new component will also track additional information including how many times the game has been played as well as who won each game (X or O) or if no one won the game (e.g.   all squares filled but no X or Os in row/column/diag).  This would be tracked in an array within the Games component.   At the end of game, the Game component would return the winner (or none) to the parent component Games.
*	Track Total Times Played and Total Times Won for each Player - Within the Games component,  would have a new info component that shows 4 new attributes,  total games,  total wins for X, for Y and for none.    These would be re-rendered at the end of each game (button is clicked to start a new game or when all squares are clicked within the game.

## License

MIT License

Copyright (c) 2022
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## Demo

* [TicTacToe Demo](https://pamelaarcher.github.io/tictactoe)
