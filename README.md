Flappy Bird

A simple Flappy Bird clone written in Java using Swing. The code in FlappyBird.java extends JPanel and manages game logic (bird movement, pipe generation, collision detection, etc.). Press the SPACE BAR to flap the bird's wings and avoid colliding with the pipes.

Key Points

Java Swing: Utilizes Swing components, timers (Timer), and keyboard events (KeyListener).
Game Logic: Implements gravity, collision detection, and a scoring system.
Keyboard Controls: Press SPACE BAR to flap the bird and restart the game after a game over.

Requirements

Java 8 (or higher) installed (JDK for compilation and JRE for running).
A Java compiler (e.g., javac) if you plan to compile on the command line.

Controls

SPACE BAR:
Makes the bird flap upward.
If the game is over, pressing SPACE BAR restarts the game (bird resets, pipes clear, score resets).

Gameplay

Pipes move from right to left at a constant speed.
Each pipe passes once it leaves the bird’s X-range. You earn 0.5 points per pipe (1 point per pipe pair).
If the bird collides with a pipe or falls off the screen, the game ends.
After game over, SPACE BAR restarts from the initial state.
