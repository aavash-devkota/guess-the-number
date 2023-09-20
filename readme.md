# Guess the Number Game

This is a simple console-based number guessing game written in Rust. The game generates a random secret number between 1 and 100, and the player's objective is to guess the secret number within a limited number of attempts.

## How to Play

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/aavash-devkota/guess-the-number.git
   ```

2. Make sure you have Rust and Cargo installed on your system.

   - To install Rust, visit [Rust's official website](https://www.rust-lang.org/tools/install) and follow the installation instructions.

3. Navigate to the project directory:

   ```bash
   cd guess-the-number
   ```

4. Build and run the game:

   ```bash
   cargo run
   ```

   This will compile and start the game. Follow the on-screen instructions to guess the secret number.

5. You can keep guessing until you correctly guess the secret number. When you guess correctly, you win the game and it will display a winning message.

## Rules

- The secret number is a random integer between 1 and 100.
- You can input your guess by typing a number and pressing Enter.
- The game will provide feedback after each guess, indicating whether your guess was too small or too big.
- You win the game if you guess the secret number correctly.

## Dependencies

This project uses the following external crates:

- `rand` - for generating random numbers.
- `colored` - for adding colors to the console output.

You can find more information about these crates and their usage in the official documentation of Rust.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. We welcome contributions and bug reports.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy playing the game, and happy coding! If you have any questions or suggestions, please feel free to open an issue or contact the project maintainers.
