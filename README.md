#Fracture#

A competitive game towards diversity.

##Sudo Code for Game Implementation##

```C
/*  Fracture (Game)
 *  
 *  Setup: For 3-6 players. Each player gets 5-6 tiles of a specific color.
 *         Game starts will all tiles connected, but completely segregated by color.
 *
 *  Goal: Get your tiles to be touching only other players tiles.
 *        Your tiles must be touching at least two other tiles to feel happily diverse.
 *
 *  Turns: Start from a player of choice and then go clockwise taking turns.
 *         A turn consists of fracturing the population into two sub populations,
 *         and then connecting them back together in any way you please.
 *  
 *  When a player has a tile fully diversified, it will blink in unison with other blinking Blinks of its color,
 *  first player to have all of their tiles blink wins. 
 *
 *  Game devopment by: Celia Pearce, Jeanie Choi, Isabella Carlson, Mike Lazer-Walker, Joshua Sloane
 *
 *  by Jonathan Bobrow
 *  9.28.2017
 */

// set teh 6 possible teams to be a part of
// red, yellow, blue, green, orange, magenta

// if button is triple clicked
	// change team to next color team in list

// if more than 1 neighbor present and none of the neighbors share my color
	// set flag to flash in happy state

// handle synchronous color flashing
// if neighbor flashes (i.e. state reflects a flash)
	// broadcast the flash on IR (maybe only broadcast if not your color)
	// if neighbor is my color
		// update urge accordingly

// display solid or flashing
// if flag for happy state satisfied
	// display flash when urge to flash
// else
	// display solid color
```