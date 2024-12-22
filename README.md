# Card Matching Game

A **Java-based card-matching game** built using Swing and JavaFX. The game challenges players to match pairs of cards by remembering their positions.

## Features

- **Interactive Gameplay**: Flip cards to find pairs and match them.
- **Error Counter**: Tracks the number of incorrect matches.
- **Restart Game**: Option to restart the game at any time.
- **Customizable Board**: Adjustable grid size, card dimensions, and images.

## Technologies Used

- **Java**: Programming language.
- **Swing**: For GUI components and event handling.
- **JavaFX**: For enhanced graphical capabilities (optional).
- **Maven/Gradle** (optional): For dependency management.

## File Structure

The project is organized into the following directories:

- **src**: Contains the source code for the game.
- **images**: Stores the images used for the card faces.
- **out**: Contains the compiled Java classes.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/username/card-matching-game.git
   cd card-matching-game
   ```

2. Open the project in your IDE (e.g., VS Code, IntelliJ IDEA).
3. Make sure Java is installed on your machine.

To verify, run:

   ```bash
   java -version
   ```

 4. Compile and run the project:

   ```bash
   javac src/App.java
   java -cp src App
   ```

## How to Play

 1. Launch the game by running the App.java file.
 2. The game will display a grid of cards face down.
 3. Click on two cards to flip them:
    - If the cards match, they will remain face up.
    - If they don’t match, they will flip back face down.
 4. The game tracks your incorrect attempts as “Errors.”
 5. Use the Restart Game button to start over at any time.

## Screenshots

Here are some screenshots of the game:

![Card Matching Game](https://github.com/Nipuna-Lakruwan/card-matching-game-java/blob/3ab26a716cd7bec9b00f94ed762e1cade89b4a12/src/img/Demo1.png)

![Card Matching Game](https://github.com/Nipuna-Lakruwan/card-matching-game-java/blob/3ab26a716cd7bec9b00f94ed762e1cade89b4a12/src/img/Demo2.png)

![Card Matching Game](https://github.com/Nipuna-Lakruwan/card-matching-game-java/blob/3ab26a716cd7bec9b00f94ed762e1cade89b4a12/src/img/Demo3.png)

## Future Enhancements

- **Timer**: Add a timer to track the time taken to complete the game.
- **High Scores**: Store and display the best scores.
- **Sound Effects**: Add sound effects for card flips and matches.
- **Themes**: Include different themes and card designs.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
