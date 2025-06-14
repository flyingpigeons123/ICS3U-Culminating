Overview
This project is a user input based Jeopardy game written in Java. Players take turns answering questions from different categories to earn points. The game includes features such as adding questions, player turns, and determining a winner, etc. 

Java Concepts Used and What They Were Used For

  1. Scanner (User Input)
- Used for reading inputs from the player, such as names, menu choices, categories, answers, etc.
- `Scanner input = new Scanner(System.in);`

2. Arrays (Storing Game and Player Data)
- `String[] categories` – stores categories for each question.
- `int[] points` – stores point values for questions.
- `String[] questions` – holds all question texts.
- `String[] answers` – stores correct answers.
- `boolean[] questionAdded` – tracks whether a question slot is filled.
- `boolean[] questionAnswered` – tracks whether a question has already been used.
- `String[] playerNames` – stores player names.
- `int[] playerScores` – holds scores for each player.

 3. Loops (`while`, `for`) Used for:
  - Repeating the main game menu.
  - Looping through questions and players.
  - Validating user input like player count and category choices.
  - Displaying scores and game board.
- Examples: `while (running)`, `for (int i = 0; i < playerCount; i++)`

 4. Conditionals (`if`, `else if`, `else`) Used for:
  - Checking menu selection.
  - Validating user input.
  - Matching category and point values to find the right question.
  - Checking for correct answers.
  - Declaring the winner or tie.

 5. Variables and Data Types
- `boolean running` – controls the main game loop.
- `int choice` – stores the player's menu selection.
- `int playerCount` – stores the number of players (between 2 and 4).
- `int currentPlayer` – tracks whose turn it is.
- `int totalQuestions` – keeps count of available questions.
- `int questionsLeft` – how many unanswered questions remain.
- `int index` – temporary variable used to track question positions.
- `String selectedCategory`, `int chosenPoint`, `String userAnswer` – store current turn's input.

 6. Console Output
Used `System.out.println()` and `System.out.print()
- To display:
  - Menus
  - Game board
  - Player scores
  - Questions and feedback (correct/incorrect)

Summary
-  All code is written inside `main()`, using no custom methods or advanced features.
-  No classes, file I/O, or object-oriented features used.
-  Project relies entirely on beginner-level Java knowledge.
- Focuses on logic, input validation, array handling, and turn-based gameplay.

 Notes:
- You can add up to 20 questions.
- The game works for 2 to 4 players.
- There is no scoring penalty for incorrect answers (you can modify this for added difficulty).
- Questions and game data are stored temporarily (not saved between runs).
