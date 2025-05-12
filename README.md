# Snake Game

🎮 A fun and simple Snake Game project written in Java. This project demonstrates the use of object-oriented programming concepts like classes, objects, queues, and recursion.

## 🐍 Features

- **Dynamic Gameplay**: The snake moves in different directions and consumes food.
- **Interactive Input**: Users can control the snake using input commands (`U`, `D`, `L`, `R` for Up, Down, Left, Right).
- **Food Generation**: Food (`X`) is displayed on the grid for the snake to eat.
- **Game Over Conditions**: The game ends if:
  - The snake moves outside the grid.
  - The snake bites itself.
  - All food is consumed.

## 🛠️ How It Works

1. **Main Class**:
   - Starts the game by creating a `Snake` object and initiating the movement.

2. **Node Class**:
   - Represents a single point (row and column) on the game grid.

3. **Snake Class**:
   - Manages the snake's movement, food generation, and grid updates.
   - Uses a `Queue` to represent the snake's body.
   - Checks for collisions and game over conditions.

## 📂 Project Structure

- `Main.java`: Entry point of the game.
- `Node.java`: Represents each cell on the grid.
- `Snake.java`: Contains the game logic and handles interactions.

## 🖥️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/snake-game.git
   ```

2. Navigate to the project directory:
   ```bash
   cd snake-game
   ```

3. Compile the Java files:
   ```bash
   javac Main.java Node.java Snake.java
   ```

4. Run the program:
   ```bash
   java snakeGame.Main
   ```

## 🕹️ Controls

- Enter one of the following commands to control the snake:
  - `U` for moving up.
  - `D` for moving down.
  - `L` for moving left.
  - `R` for moving right.

## 📝 Example Output

```
. . . . . .
X . . . . .
. . X . . .
. . . . X .
. . . . . X
. . X . . .

Enter a position: U
Invalid move
Game Over!!!
```

## 🚀 Future Improvements

- Add a graphical interface for a more engaging experience.
- Implement levels with increasing difficulty.
- Allow saving and resuming the game.

## 🤝 Contributions

Feel free to fork this repository, make changes, and submit pull requests. Suggestions and feedback are always welcome!

## 📜 License

This project is licensed under the MIT License.
