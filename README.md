# Day 23: Turtle Crossing Game 🐢🚗

For this capstone project, I built a **Turtle Crossing game** inspired by arcade-style road-crossing challenges. The turtle begins at the bottom of the screen, and a stream of cars moves horizontally across the road.  
The goal is to guide the turtle safely across the street while dodging cars. Each successful crossing levels up the game and with each level, the cars get faster, making the challenge even more exciting and intense.

This project really brought together everything I've learned with the Turtle module and class design so far. I loved that the capstone was a game because it made debugging and problem-solving feel exciting instead of tiring. There were moments when logic got tricky, but knowing I was building something fun and interactive kept me motivated. Finishing this project genuinely felt like leveling up as a programmer. Since it was a capstone project nothing was necesarily taught but we were given step by step instructions to guide us.

# The key skills used:

- Object-Oriented Programming
- Creating and initializing classes (`__init__`)
- Managing multiple objects on screen
- Event listeners for keyboard movement
- Game loop logic & screen refresh control
- Collision detection between turtle and cars
- Level progression system (car speed increases)
- Displaying scoreboard and "Game Over" message


## 🛠️ How the Code in eaxh class works:
 **Player.py (Turtle)**  
  - Moves upward with key presses  
  - Resets to start position after each successful crossing  

 **Car_manager.py**  
  - Spawn at random positions  
  - Move horizontally across the screen  
  - Speed increases with each level  
  - If a car touches the turtle → game over  

  **Scoreboard.py**  
  - Each successful crossing increases the level  
  - Level determines car speed  
  - Scoreboard updates and displays a game over message when needed  


