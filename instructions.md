# INSTRUCTIONS for FRACTURE


### Premise

Fracture is a simple turn-based strategy game for 3-6 playes. It was the first Blinks game created! 

### Setup

3-6 players. Each player gets 4-6 tiles of the same color. The game starts when all tiles are connected. At the start of the game, make sure all pieces are segregated by color. (ex. All Red pieces attached together, All Blue pieces attached together, etc.) 

### Goal

The win state of each team or player is to get all their Blinks to

**a)** touch at least two other Blinks **AND**

**b)** not be touching its own color. 

When a Blink satisfies both these conditions, it will start an animation that shows it ‘blinking’ continuously in happiness. In any other case, it will simply display its color and remain static. 

### Gameplay

At the beginning of the game, each player should choose a color. On their turn, a player should make a fracture by splitting the population of game pieces into two subpopulations, and then connecting them back together in any way they choose. The two subpopulations can be of any size; they do not have to be equal. You can choose to only move a single piece if you wish, and you can move any Blinks, not just the ones of your own color. 

Once a player has finished their move, turns proceed in a clockwise fashion. The game ends when a player has completely diversified their respective Blinks, and they are all ‘blinking’ in happiness.

One limitation a player has on their turn is that they cannot make a fracture that involves moving a single piece out from a piece that is ‘locked in’. A locked in piece is a Blink that has any pair of opposite sides connected to another Blink. 

### Animation States

Normal -- the Blink will display its color (either blue, yellow, green, red). This is the default state. 

Blinking -- the Blink repeatedly turns on/off. Getting all your Blinks in this state wins you the game. This occurs when the Blink is touching at least two other Blinks and none of the Blinks it is touching is of the same color. 

### Interactions

Triple-click -- Change the team/player color of the Blink to the next one in the list. (Red --> Blue --> Yellow -- > Green)

