# concurrent-and-distributed-programming-Project

Resume of 1st part of the project:
Make a game that includes 2 snakes, 25 Obstacles and 9 different goals.
The snakes start with a size of 5. They're objective is to collect the goal number 9. They are automatic, and they should move towards the goal.
The goal starts with the number 1, which corresponds to the size that the snake will increment if they catch it. Once the first goal is taken, it appears the second with the number two
and so on until number 9. Once a snake eats the goal number 9 it all stops.
The obstacles move around randomly but only 3 at a time. They have only 3 possible moves. Example: The threads chosen were the number 5, 8 and 16. They will move only 3 times, all at the same time
to random positions. Once they move those 3 times, they stop, and other 3 thread will be chosen to move and so on.
