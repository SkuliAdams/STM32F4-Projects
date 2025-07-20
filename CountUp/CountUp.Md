A starter program which I used to learn about the IDE, the basic functions of the board and the associated hardware abstraction library, and how to string together some LED's on a breadboard.
Four LED's are connected to four output pins on the board, and will light up to count from 0 to 15 in binary.

Since there is a lot of boilerplate code, here is a list of my modifications:

main.c, line 104, the basic logic for incrementing the counter and a call to set pin values based on it.

gpio.c, line 34, the function I wrote to take a 4 bit number and set four output pins appropriately to light up the LED's.
