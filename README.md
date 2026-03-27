🎯 Number Guessing Game (C Language)

- A simple and interactive command-line game built using C, where the player tries to guess a randomly generated number within the range of 1 to 100.

🚀 Features
-  Random number generation using rand()
-   User input-based guessing system
-  art hints:
"Higher number please!"

"Lower number please!"

📊 Tracks number of attempts

🧠 Beginner-friendly logic implementation

🛠️ Tech Stack

Language: C

Concepts Used:

- Loops (do-while)
- Conditional statements (if-else)
- Functions: rand(), srand(), time()
- User input/output

📂 How It Works

- The program generates a random number between 1 and 100.
- The user is asked to guess the number.

Based on the guess:

- If too high → prompts to guess lower
- If too low → prompts to guess higher
- The game continues until the correct number is guessed.
- Total number of attempts is displayed at the end.

▶️ How to Run


Step 1: Compile the code

gcc game.c -o game

Step 2: Run the program

./game

💡 Example Output

- guess the number: 50
- higher number please!

- guess the number: 75
- lower number please!

- guess the number: 63
- congrats!

you guessed the number in 3 guesses

📸 Code Preview

int randomNumber = (rand() % 100) + 1;

🎯 Learning Outcome

This project helps in understanding:



Basics of random number generation

Handling user input

Writing loop-based logic

Building simple interactive CLI programs

🔮 Future Improvements

Add difficulty levels (Easy, Medium, Hard)

Limit number of attempts

Add replay option

Improve UI with colors (using libraries)

👩‍💻 Author



Jhanvi Gupta



🔗 GitHub: https://github.com/JhanviGupta03

🔗 LinkedIn: linkedin.com/in/jhanvi-gupta-73392b398

⭐ Show Some Love

If you like this project, consider giving it a ⭐ on GitHub!
