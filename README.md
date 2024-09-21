This program uses the turtle graphics module to simulate a simple turtle race. The user is prompted to place a bet on which turtle will win the race. Turtles of different colors race across the screen, and the first one to cross the finish line wins. The result of the race is printed, telling the user if they won or lost based on their bet.

Randomized race: Each turtle moves a random distance in each step, creating an unpredictable outcome.
Result announcement: The program announces whether the user's chosen turtle won or not.

Screen Setup:
The turtle graphics screen is set up with a width of 500 and height of 500 pixels.
The user is prompted to input a color (from the available colors) to place their bet.

Turtle Initialization:
Six turtles are created, each with a distinct color (red, orange, yellow, green, blue, purple).
Each turtle is positioned at the starting line with coordinates based on a loop, ensuring they're spread vertically.

Race Logic:
The race begins if the user places a bet.
In each iteration of the race, each turtle moves a random distance between 0 and 10 pixels.
The race continues until one turtle crosses the finish line (at x-coordinate > 230).

Result Handling:
Once a turtle crosses the finish line, the race stops, and the color of the winning turtle is compared to the user's bet.
A message is printed indicating whether the user won or lost.
