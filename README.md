# Simon

A browser memory game: repeat an expanding sequence of coloured buttons to advance through the levels.

## Tech stack

JavaScript · jQuery · HTML · CSS · Browser Audio API

## How to play

Open [index.html](index.html) in a browser with an internet connection for the jQuery CDN. Press any key to start, then click the buttons in the order shown. A mistake ends the game; press a key to restart.

## Implementation

[game.js](game.js) keeps the generated sequence separate from the player's input, checks each selection, and advances after a completed round. Sound and animation provide feedback for selections and game-over states.

A focused exercise in game state, sequence validation, timed interactions, and reset behaviour. No build tools or backend are required.
