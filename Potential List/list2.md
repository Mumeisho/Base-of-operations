# The C Language Odyssey: A Project-Based Learning Roadmap (200-500 Projects, Standard Library Only) 🚀

## Foundational C: Mastering the Core

### Fundamentals & Memory Layout

#### Project 1: Basic Arithmetic Calculator ➕➖✖️➗

- Description: Develop a console-based calculator supporting addition, subtraction, multiplication, and division.
- Goal: Master stdio.h for I/O and basic control flow (if-else, switch).

#### Project 2: Calculator with Exponentiation

- Description: Extend the basic calculator to include exponentiation.
- Goal: Implement mathematical operations using loops or custom functions.

#### Project 3: Calculator with Modulo and Integer Division

- Description: Further extend the calculator to support modulo and integer division.
- Goal: Understand integer arithmetic and handle related edge cases.

#### Project 4: Robust Calculator Input Validation

- Description: Add robust error handling to the calculator, specifically for division by zero and non-numeric input.
- Goal: Implement input validation and error reporting using printf.

#### Project 5: Modular Calculator Design

- Description: Refactor the calculator into separate functions for each operation and input handling.
- Goal: Design modular functions for better code organization and reusability.

#### Project 6: Decimal to Binary Converter 🔢

- Description: Create a program that converts a decimal integer to its binary representation.
- Goal: Understand integer representation and apply bitwise operations or division/modulo logic.

#### Project 7: Binary to Decimal Converter

- Description: Develop a program to convert a binary string (e.g., "1011") to its decimal equivalent.
- Goal: Practice string parsing and power calculations.

#### Project 8: Decimal to Octal/Hexadecimal Converter

- Description: Extend the number system converter to handle conversions from decimal to octal and hexadecimal.
- Goal: Deepen understanding of different number bases and their conversion algorithms.

#### Project 9: Octal/Hexadecimal to Decimal Converter

- Description: Implement conversion from octal and hexadecimal strings to decimal.
- Goal: Enhance string parsing and base conversion logic.

#### Project 10: Universal Number System Converter

- Description: Create a program that can convert numbers between any two of the four bases (Decimal, Binary, Octal, Hexadecimal) based on user input.
- Goal: Integrate multiple conversion functions and handle diverse input/output formats.

#### Project 11: Global Variable Memory Explorer 🗺️

- Description: Write a program to print the memory addresses of global variables.
- Goal: Understand the data segment and static memory allocation.

#### Project 12: Stack and Heap Growth Observer

- Description: Develop a program to observe and document how the stack and heap segments grow during function calls and dynamic allocations.
- Goal: Gain practical insight into C's dynamic memory behavior and memory segments.

#### Project 13: Array Manipulation with Indexing 📍

- Description: Implement functions to manipulate arrays using traditional array indexing (e.g., arr[i]).
- Goal: Solidify understanding of array access and basic array operations.

#### Project 14: Array Manipulation with Pointer Arithmetic

- Description: Re-implement the array manipulation functions using direct pointer arithmetic (e.g., *(ptr + i)).
- Goal: Deepen understanding of pointers and their relationship with arrays.

#### Project 15: Generic Sort with Function Pointers 📞

- Description: Design a generic sorting function that accepts a comparison function as an argument via a function pointer.
- Goal: Master function pointers for creating flexible and reusable code.

B. Data Structures from Scratch

#### Project 16: Fixed-Size Dynamic Array 📏

- Description: Implement a dynamic array with a fixed initial capacity, handling basic add/remove operations.
- Goal: Understand array-based data storage and basic memory management.

#### Project 17: Resizing Dynamic Array (Growth)

- Description: Enhance the dynamic array to automatically grow its capacity when full using realloc.
- Goal: Master dynamic memory resizing and understand its performance implications.

#### Project 18: Resizing Dynamic Array (Shrinkage)

- Description: Add functionality to the dynamic array to shrink its capacity when elements are removed and space is excessive.
- Goal: Optimize memory usage by dynamically adjusting array size.

#### Project 19: Generic Dynamic Array (void pointers)

- Description: Modify the dynamic array to store void pointers, allowing it to hold elements of any type (requiring client-side type casting).
- Goal: Implement generic data structures using void pointers and function pointers for operations.

#### Project 20: Singly Linked List - Insertion 🔗

- Description: Implement functions for inserting nodes at the head, tail, and specific positions in a singly linked list.
- Goal: Understand linked list node structure and dynamic memory allocation for nodes.

#### Project 21: Singly Linked List - Deletion

- Description: Implement functions for deleting nodes by value or position from a singly linked list.
- Goal: Master pointer manipulation for removing nodes and freeing memory.

#### Project 22: Singly Linked List - Search and Traversal

- Description: Implement functions to search for an element and traverse/print all elements in a singly linked list.
- Goal: Practice iterating through linked structures.

#### Project 23: Singly Linked List - Reverse

- Description: Implement a function to reverse a singly linked list in place.
- Goal: Develop advanced pointer manipulation skills.

#### Project 24: Doubly Linked List - Insertion ↔️🔗

- Description: Implement functions for inserting nodes at various positions in a doubly linked list.
- Goal: Understand the dual-pointer structure and maintain next and prev links.

#### Project 25: Doubly Linked List - Deletion

- Description: Implement functions for deleting nodes from a doubly linked list.
- Goal: Master deletion in a bidirectional list, ensuring all pointers are correctly updated.

#### Project 26: Doubly Linked List - Search and Traversal

- Description: Implement functions to search for an element and traverse the list in both forward and reverse directions.
- Goal: Utilize the bidirectional nature of the doubly linked list.

#### Project 27: Doubly Linked List - Circular

- Description: Extend the doubly linked list to make it circular, where the tail points to the head and vice-versa.
- Goal: Understand circular data structures and their boundary conditions.

#### Project 28: Array-Based Stack 🥞

- Description: Implement a stack using a fixed-size array, including push, pop, peek, and isEmpty operations with overflow/underflow checks.
- Goal: Understand the LIFO principle and array-based implementation.

#### Project 29: Linked List-Based Stack

- Description: Implement a stack using a singly linked list, providing push, pop, peek, and isEmpty operations.
- Goal: Compare array vs. linked list implementations for stacks.

#### Project 30: Circular Array-Based Queue 🚶‍♀️🚶‍♂️🚶‍♀️

- Description: Implement a queue using a circular array to efficiently manage space, including enqueue, dequeue, peek, and isEmpty operations.
- Goal: Understand the FIFO principle and circular buffer management.

#### Project 31: Linked List-Based Queue

- Description: Implement a queue using a singly linked list, providing enqueue, dequeue, peek, and isEmpty operations.
- Goal: Compare array vs. linked list implementations for queues.

#### Project 32: Basic Hash Table with Separate Chaining #️⃣

- Description: Implement a simple hash table using an array of linked lists (separate chaining) to resolve collisions.
- Goal: Learn fundamental hashing concepts and collision resolution.

#### Project 33: Custom Hash Function Implementation

- Description: Design and implement a basic hash function (e.g., sum of ASCII values modulo table size) for the hash table.
- Goal: Understand the role of hash functions in data distribution.

#### Project 34: Binary Search Tree - Insertion and Search 🌳

- Description: Implement functions for inserting nodes and searching for values in a Binary Search Tree (BST).
- Goal: Understand hierarchical tree structures and recursive insertion/search.

#### Project 35: Binary Search Tree - Traversal and Deletion

- Description: Implement in-order, pre-order, and post-order traversal methods, and node deletion from a BST.
- Goal: Master recursive tree traversal and complex node removal logic.

C. File I/O and Persistence

#### Project 36: Basic Text File Reader ✍️

- Description: Create a program to open a text file and print its entire content to the console.
- Goal: Master fopen, fclose, and fgetc or fgets for basic file reading.

#### Project 37: Text File Writer

- Description: Develop a program that takes user input and writes it to a new text file.
- Goal: Practice fprintf or fputs for writing data to files.

#### Project 38: Text File Appender

- Description: Implement a program that appends new lines of text to an existing file.
- Goal: Understand file modes for appending ("a").

#### Project 39: Simple Text File Overwriter

- Description: Create a program that overwrites the content of an existing text file with new user input.
- Goal: Understand file modes for writing ("w") and its destructive nature.

#### Project 40: CSV File Reader (Basic) 📊

- Description: Create a program to read a simple CSV file (e.g., "name,age,city") line by line and print each field separately.
- Goal: Learn basic string tokenization (using strtok or custom parsing) for delimited data.

#### Project 41: CSV File Writer

- Description: Develop a program that takes structured user input (e.g., name, age) and writes it to a CSV file.
- Goal: Practice formatted output and handling comma separation.

#### Project 42: CSV Data Structure Loader

- Description: Read data from a CSV file into an in-memory array of structs.
- Goal: Integrate file I/O with data structures for structured data handling.

#### Project 43: Contact Management - Add/View 🧑‍🤝‍🧑

- Description: Build a system to add new contact information (name, phone, email) and view all stored contacts. Data is stored in a text file.
- Goal: Combine structs, basic file I/O, and input handling.

#### Project 44: Contact Management - Search

- Description: Add functionality to search for contacts by name or phone number.
- Goal: Implement search algorithms on file-based data.

#### Project 45: Contact Management - Update

- Description: Implement the ability to update existing contact information.
- Goal: Practice reading, modifying, and rewriting file data.

#### Project 46: Contact Management - Delete

- Description: Add functionality to delete contacts from the system.
- Goal: Master file manipulation for record removal (e.g., rewriting the file without the deleted record).

#### Project 47: Contact Management - Binary Storage

- Description: Modify the contact system to store data in a custom binary format for efficiency.
- Goal: Understand binary file I/O (fread, fwrite) and data serialization.

#### Project 48: Basic Log Appender 📜

- Description: Implement a simple logging utility that appends messages to a designated log file.
- Goal: Practice appending data to files and basic string formatting.

#### Project 49: Timestamped Logger

- Description: Enhance the logger to include a timestamp with each log message.
- Goal: Utilize time.h for generating accurate timestamps.

#### Project 50: Log Level Filter

- Description: Add support for different log levels (e.g., INFO, WARNING, ERROR) and allow filtering messages based on level.
- Goal: Design a simple, extensible logging API and implement conditional output.

II. Intermediate C: Systems and Logic
A. Command-Line Utilities

#### Project 51: Custom cat (Single File) 📄

- Description: Implement a program that prints the content of a single specified file to standard output.
- Goal: Master basic file reading and stdout redirection.

#### Project 52: Custom cat (Multiple Files)

- Description: Extend cat to concatenate and print the content of multiple files provided as command-line arguments.
- Goal: Handle multiple file inputs and command-line argument parsing (argc, argv).

#### Project 53: Custom cat (Standard Input)

- Description: Modify cat to read from standard input if no file arguments are provided.
- Goal: Understand reading from stdin and conditional input sources.

#### Project 54: Custom cat (Line Numbering)

- Description: Add an option (e.g., -n) to cat to display line numbers for each line.
- Goal: Implement command-line options and line-by-line processing.

#### Project 55: Custom cat (Error Handling)

- Description: Implement robust error handling for cat, such as file not found or permission denied, using errno.h and perror().
- Goal: Develop robust error reporting for command-line tools.

#### Project 56: Simple grep (Fixed String) 🔍

- Description: Develop a simplified version of grep that searches for a fixed string pattern within a single text file and prints matching lines.
- Goal: Learn line-by-line file reading and basic string searching (strstr or custom).

#### Project 57: Simple grep (Case-Insensitive)

- Description: Add an option (e.g., -i) to grep for case-insensitive pattern matching.
- Goal: Practice character conversion (tolower, toupper from ctype.h) for string comparison.

#### Project 58: Simple grep (Multiple Files)

- Description: Extend grep to search for a pattern across multiple specified files.
- Goal: Manage multiple file inputs and output formatting for matches from different files.

#### Project 59: Simple grep (Line Numbering)

- Description: Add an option (e.g., -n) to grep to display line numbers along with matching lines.
- Goal: Combine line numbering with pattern matching.

#### Project 60: Simple grep (Invert Match)

- Description: Add an option (e.g., -v) to grep to print lines that do not contain the pattern.
- Goal: Implement inverted matching logic.

#### Project 61: Simple wc (Line Count) 📊

- Description: Implement a program to count the number of lines in a given text file or from standard input.
- Goal: Practice character-by-character input processing and line detection.

#### Project 62: Simple wc (Word Count)

- Description: Extend wc to count the number of words in a file.
- Goal: Implement a basic state machine for accurate word detection (e.g., transitioning between whitespace and non-whitespace).

#### Project 63: Simple wc (Character Count)

- Description: Further extend wc to count the number of characters (bytes) in a file.
- Goal: Understand character-level file processing.

#### Project 64: Simple wc (All Counts)

- Description: Combine line, word, and character counting into a single wc utility.
- Goal: Integrate multiple counting functionalities.

#### Project 65: Simple wc (Multiple Files)

- Description: Allow wc to process multiple files and display counts for each, plus a total.
- Goal: Handle multiple file inputs and aggregate results.

#### Project 66: Basic diff (Line Comparison) ↔️

- Description: Create a program that compares two text files line by line and reports if lines differ.
- Goal: Develop logic for file comparison and line-by-line reading.

#### Project 67: Basic diff (Show Differing Lines)

- Description: Enhance diff to print the actual differing lines from both files.
- Goal: Implement detailed line comparison and output.

#### Project 68: Basic diff (Line Numbers)

- Description: Add line numbers to the output of differing lines in diff.
- Goal: Combine comparison with line tracking.

#### Project 69: Basic diff (Ignore Whitespace)

- Description: Add an option to diff to ignore leading/trailing whitespace when comparing lines.
- Goal: Practice string trimming and normalized comparison.

#### Project 70: Basic diff (Ignore Case)

- Description: Add an option to diff to perform case-insensitive comparison.
- Goal: Apply character conversion for comparison.

#### Project 71: Custom head (First N Lines) ✂️

- Description: Implement a utility that prints the first N lines of a specified file.
- Goal: Practice buffered file reading and line counting.

#### Project 72: Custom head (Default 10 Lines)

- Description: Set the default behavior of head to print the first 10 lines if N is not specified.
- Goal: Implement default arguments and conditional logic.

#### Project 73: Custom tail (Last N Lines - Simple)

- Description: Implement a basic tail utility that reads the entire file into memory and then prints the last N lines.
- Goal: Understand reading entire files and managing in-memory buffers.

#### Project 74: Custom tail (Last N Lines - Efficient)

- Description: Implement a more efficient tail that seeks to the end of the file and reads backward to find the last N lines, suitable for large files.
- Goal: Leverage fseek and ftell for efficient file navigation.

#### Project 75: Custom tail (Standard Input)

- Description: Allow tail to read from standard input if no file is provided.
- Goal: Handle input from stdin for tail functionality.

B. Core Algorithms

#### Project 76: Bubble Sort Implementation 🔀

- Description: Implement the Bubble Sort algorithm to sort an array of integers.
- Goal: Understand basic comparison sorting and iterative array manipulation.

#### Project 77: Selection Sort Implementation

- Description: Implement the Selection Sort algorithm.
- Goal: Understand finding minimum/maximum elements and swapping.

#### Project 78: Insertion Sort Implementation

- Description: Implement the Insertion Sort algorithm.
- Goal: Understand incremental sorting and shifting elements.

#### Project 79: Quick Sort Implementation (Recursive)

- Description: Implement the Quick Sort algorithm using recursion.
- Goal: Master divide and conquer paradigm and recursive function calls.

#### Project 80: Merge Sort Implementation (Recursive)

- Description: Implement the Merge Sort algorithm using recursion.
- Goal: Understand divide and conquer, and merging sorted sub-arrays.

#### Project 81: Heap Sort (Conceptual)

- Description: Implement the Heap Sort algorithm, building a max-heap (using an array) and then sorting.
- Goal: Understand heap data structure properties and their application in sorting.

#### Project 82: Counting Sort (for limited range)

- Description: Implement Counting Sort for integers within a limited range.
- Goal: Learn about non-comparison sorting algorithms and their constraints.

#### Project 83: Radix Sort (for integers)

- Description: Implement Radix Sort for sorting integers.
- Goal: Understand digit-by-digit sorting and its efficiency.

#### Project 84: Sorting Algorithm Performance Comparison

- Description: Write a program to compare the execution time of different sorting algorithms on various data sets (e.g., sorted, random, reverse-sorted).
- Goal: Analyze algorithmic complexity empirically using time.h.

#### Project 85: Generic Sorting Function (void pointers)

- Description: Create a single generic sorting function (e.g., Quick Sort) that can sort arrays of any data type using void pointers and a comparison function pointer.
- Goal: Apply void pointers and function pointers for generic algorithms.

#### Project 86: Linear Search 🔎

- Description: Implement a linear search function to find an element in an unsorted array.
- Goal: Understand basic sequential search.

#### Project 87: Binary Search (Iterative)

- Description: Implement the binary search algorithm iteratively on a sorted array.
- Goal: Master efficient search on sorted data.

#### Project 88: Binary Search (Recursive)

- Description: Implement the binary search algorithm recursively on a sorted array.
- Goal: Practice recursion for search problems.

#### Project 89: Find Min/Max in Array

- Description: Implement functions to find the minimum and maximum elements in an array.
- Goal: Practice basic array traversal and comparison.

#### Project 90: Find Kth Smallest/Largest Element

- Description: Implement an algorithm (e.g., using partitioning ideas from Quick Sort) to find the Kth smallest or largest element in an unsorted array.
- Goal: Understand selection algorithms.

#### Project 91: Graph Representation (Adjacency Matrix) 🌐

- Description: Implement a graph data structure using an adjacency matrix.
- Goal: Understand graph representation for dense graphs.

#### Project 92: Graph Representation (Adjacency List)

- Description: Implement a graph data structure using an adjacency list (using linked lists or dynamic arrays).
- Goal: Understand graph representation for sparse graphs.

#### Project 93: Depth-First Search (DFS)

- Description: Implement the Depth-First Search (DFS) algorithm for graph traversal.
- Goal: Master recursive graph traversal.

#### Project 94: Breadth-First Search (BFS)

- Description: Implement the Breadth-First Search (BFS) algorithm for graph traversal.
- Goal: Master iterative graph traversal using a queue.

#### Project 95: Connected Components (DFS/BFS Application)

- Description: Use DFS or BFS to find and count the connected components in an undirected graph.
- Goal: Apply graph traversal algorithms to solve connectivity problems.

#### Project 96: Naive String Matching 🧵

- Description: Implement a brute-force algorithm to find all occurrences of a substring within a larger text.
- Goal: Practice nested loop structures and character comparisons for pattern finding.

#### Project 97: String Reversal

- Description: Implement a function to reverse a given string in place.
- Goal: Practice in-place string manipulation.

#### Project 98: Anagram Checker

- Description: Develop a program to determine if two strings are anagrams of each other.
- Goal: Practice character counting and array manipulation for string analysis.

#### Project 99: Palindrome Checker (Iterative) 🔄

- Description: Implement an iterative function to check if a string is a palindrome.
- Goal: Practice string traversal from both ends.

#### Project 100: Palindrome Checker (Recursive)

- Description: Implement a recursive function to check if a string is a palindrome.
- Goal: Practice recursion for string problems.

C. Console Games and Interactive Programs

#### Project 101: Hangman Game - Basic Logic Gallows

- Description: Develop the core logic for Hangman: word selection, guessing letters, and tracking correct/incorrect guesses.
- Goal: Implement string manipulation, character comparison, and basic game state management.

#### Project 102: Hangman Game - ASCII Art Display

- Description: Add ASCII art representations for the hangman figure based on incorrect guesses.
- Goal: Practice printf for console graphics and conditional display.

#### Project 103: Hangman Game - Word List from File

- Description: Load the word list for Hangman dynamically from an external text file.
- Goal: Master file reading for game data and random word selection.

#### Project 104: Hangman Game - Input Validation

- Description: Implement robust input validation for user guesses (e.g., single letter, not already guessed).
- Goal: Enhance defensive programming for interactive applications.

#### Project 105: Hangman Game - Score Tracking

- Description: Add score tracking and a win/loss counter for multiple rounds of Hangman.
- Goal: Manage persistent game statistics.

#### Project 106: Tic-Tac-Toe - Player vs. Player ❌⭕

- Description: Implement the classic Tic-Tac-Toe game for two human players on a 3x3 grid.
- Goal: Master 2D array manipulation for game board representation and win condition checking.

#### Project 107: Tic-Tac-Toe - Basic AI (Random Moves)

- Description: Introduce a simple AI opponent that makes random valid moves.
- Goal: Implement random number generation (rand, srand) and basic AI decision-making.

#### Project 108: Tic-Tac-Toe - AI (Blocking Wins)

- Description: Enhance the AI to block immediate winning moves by the human player.
- Goal: Develop more sophisticated AI logic for defensive play.

#### Project 109: Tic-Tac-Toe - AI (Offensive Moves)

- Description: Further enhance the AI to attempt to win if a winning move is available.
- Goal: Implement offensive AI strategies.

#### Project 110: Tic-Tac-Toe - AI (Prioritize Center/Corners)

- Description: Improve the AI's strategy by prioritizing center or corner squares when no immediate win/block is available.
- Goal: Refine AI decision-making with heuristic rules.

#### Project 111: Console Snake Game - Movement 🐍

- Description: Implement basic snake movement (up, down, left, right) on a console grid.
- Goal: Understand continuous game loops and updating character positions.

#### Project 112: Console Snake Game - Food Generation

- Description: Add random food generation on the game board.
- Goal: Implement random positioning and collision detection with food.

#### Project 113: Console Snake Game - Growth and Score

- Description: Make the snake grow when it eats food and track the score.
- Goal: Manage dynamic snake length and score updates.

#### Project 114: Console Snake Game - Collision Detection

- Description: Implement collision detection with console boundaries and the snake's own body.
- Goal: Define game over conditions and boundary checks.

#### Project 115: Console Snake Game - Speed Control

- Description: Allow the game speed to increase as the snake grows or based on user input.
- Goal: Control game timing and difficulty.

#### Project 116: Console 2048 Game - Board Setup 🔢🧩

- Description: Set up the 4x4 game board and initialize with two random tiles.
- Goal: Master 2D array initialization and random number generation.

#### Project 117: Console 2048 Game - Tile Movement (Left/Right)

- Description: Implement the logic for sliding and merging tiles when the user moves left or right.
- Goal: Develop complex 2D array manipulation algorithms.

#### Project 118: Console 2048 Game - Tile Movement (Up/Down)

- Description: Implement the logic for sliding and merging tiles when the user moves up or down.
- Goal: Extend 2D array manipulation to all directions.

#### Project 119: Console 2048 Game - Score and New Tile Generation

- Description: Track the score and generate new random tiles after each valid move.
- Goal: Manage game state, score updates, and random element placement.

#### Project 120: Console 2048 Game - Game Over Detection

- Description: Implement logic to detect when no more moves are possible, signaling game over.
- Goal: Define complex game termination conditions.

#### Project 121: Text Adventure - Room Navigation 🗺️📖

- Description: Create a simple text adventure with interconnected rooms and allow the player to move between them (e.g., "go north").
- Goal: Implement basic state machine for location tracking and command parsing.

#### Project 122: Text Adventure - Item Interaction (Take/Drop)

- Description: Add items to rooms and allow the player to take and drop them, managing inventory.
- Goal: Implement inventory management and object interaction.

#### Project 123: Text Adventure - Item Interaction (Use)

- Description: Implement the ability to "use" items, triggering specific events or unlocking new paths.
- Goal: Develop conditional logic based on item possession and context.

#### Project 124: Text Adventure - Simple Puzzles

- Description: Introduce simple puzzles that require specific items or actions to solve.
- Goal: Design basic puzzle mechanics and state changes.

#### Project 125: Text Adventure - NPC Interaction (Dialogue)

- Description: Add non-player characters (NPCs) with simple dialogue options.
- Goal: Implement basic dialogue trees and character interaction.

#### Project 126: Text Adventure - NPC Interaction (Quests)

- Description: Introduce simple quests given by NPCs, requiring the player to find items or reach locations.
- Goal: Develop quest tracking and reward systems.

#### Project 127: Text Adventure - Save/Load Game (Text File)

- Description: Implement functionality to save and load game progress to/from a text file.
- Goal: Practice structured data persistence using file I/O.

#### Project 128: Text Adventure - Save/Load Game (Binary File)

- Description: Optimize save/load functionality by using a custom binary file format.
- Goal: Understand binary serialization for game state.

#### Project 129: Text Adventure - Command Aliases

- Description: Allow players to use aliases for common commands (e.g., "n" for "go north").
- Goal: Implement command mapping and flexible input parsing.

#### Project 130: Text Adventure - Basic Combat System

- Description: Introduce a simple turn-based combat system with basic stats (health, attack).
- Goal: Develop combat logic and random damage calculation.

#### Project 131: Quiz Game - Basic Multiple Choice ❓

- Description: Create a multiple-choice quiz with hardcoded questions and answers.
- Goal: Implement basic question display, input, and answer checking.

#### Project 132: Quiz Game - Score Tracking

- Description: Track the player's score throughout the quiz.
- Goal: Manage numerical game statistics.

#### Project 133: Quiz Game - Questions from File (Simple Format)

- Description: Load quiz questions and answers from a simple text file (e.g., one question per line, answer on next line).
- Goal: Practice file reading for dynamic content.

#### Project 134: Quiz Game - Questions from File (Structured Format)

- Description: Load questions from a more structured file format (e.g., CSV with question, options, correct answer).
- Goal: Implement advanced string parsing for structured data.

#### Project 135: Quiz Game - Timer per Question

- Description: Add a time limit for answering each question.
- Goal: Utilize time.h for timing and conditional logic.

#### Project 136: Quiz Game - Random Question Order

- Description: Randomize the order of questions presented to the user.
- Goal: Implement array shuffling and random selection.

#### Project 137: Quiz Game - Category Selection

- Description: Allow the user to select a quiz category, loading questions from a specific file.
- Goal: Implement menu-driven selection and conditional file loading.

#### Project 138: Quiz Game - True/False Questions

- Description: Add support for true/false questions alongside multiple choice.
- Goal: Extend question types and answer validation.

#### Project 139: Quiz Game - High Score Persistence

- Description: Save the highest score achieved to a file and display it.
- Goal: Implement simple high score persistence.

#### Project 140: Quiz Game - User Profiles

- Description: Allow multiple users to have profiles and track their individual high scores.
- Goal: Manage multiple user data records and file I/O.

#### Project 141: Quiz Game - Question Bank Management (Add)

- Description: Implement a separate utility to add new questions to the quiz question bank file.
- Goal: Practice file appending and structured input.

#### Project 142: Quiz Game - Question Bank Management (Edit)

- Description: Implement a utility to edit existing questions in the question bank.
- Goal: Practice file reading, modification, and rewriting.

#### Project 143: Quiz Game - Question Bank Management (Delete)

- Description: Implement a utility to delete questions from the question bank.
- Goal: Practice file record deletion.

#### Project 144: Quiz Game - Feedback on Answers

- Description: Provide immediate feedback after each question, indicating if the answer was correct and showing the correct answer.
- Goal: Enhance user interaction and learning experience.

#### Project 145: Quiz Game - Progress Bar (Conceptual)

- Description: Implement a conceptual progress bar using ASCII characters to show quiz completion.
- Goal: Practice console UI elements and dynamic display.

#### Project 146: Quiz Game - Review Incorrect Answers

- Description: At the end of the quiz, allow the user to review the questions they answered incorrectly.
- Goal: Store and retrieve specific quiz data for review.

#### Project 147: Quiz Game - Difficulty Levels

- Description: Implement different difficulty levels, potentially by selecting questions from different files or applying scoring modifiers.
- Goal: Introduce game difficulty scaling.

#### Project 148: Quiz Game - Command-Line Options

- Description: Allow quiz configuration via command-line arguments (e.g., -c category, -n number_of_questions).
- Goal: Enhance command-line argument parsing for application configuration.

#### Project 149: Quiz Game - ASCII Art Title Screen

- Description: Create an engaging ASCII art title screen for the quiz game.
- Goal: Practice creative console output and string manipulation.

#### Project 150: Quiz Game - Basic Statistics

- Description: Display basic statistics at the end of the quiz, such as percentage correct, time taken, etc.
- Goal: Calculate and present performance metrics.

III. Advanced C: Low-Level and Specialized Domains
A. Advanced Memory Management & System Concepts

#### Project 151: Simple Fixed-Size Memory Pool 📦

- Description: Implement a memory allocator using a fixed-size array as a memory pool, allocating blocks of a single, fixed size.
- Goal: Understand basic memory pool concepts and direct memory manipulation.

#### Project 152: First-Fit Memory Allocator

- Description: Implement a malloc-like function using a linked list of free blocks and the first-fit strategy.
- Goal: Understand dynamic memory allocation algorithms and managing free lists.

#### Project 153: Best-Fit Memory Allocator

- Description: Implement a malloc-like function using the best-fit strategy.
- Goal: Compare different allocation strategies and their impact on fragmentation.

#### Project 154: Custom free Implementation

- Description: Implement a free-like function that coalesces adjacent free blocks to reduce fragmentation.
- Goal: Master memory deallocation and fragmentation management.

#### Project 155: Memory Block Header Management

- Description: Design and implement metadata (headers) for allocated and free memory blocks within a custom allocator.
- Goal: Understand how memory allocators track block status and size.

#### Project 156: Simple realloc Implementation

- Description: Implement a basic version of realloc using custom malloc and free.
- Goal: Understand memory block resizing and data copying.

#### Project 157: calloc Implementation

- Description: Implement calloc using custom malloc and zero-initialization.
- Goal: Understand memory allocation with initialization.

#### Project 158: Memory Allocation Statistics

- Description: Add functionality to the custom allocator to track and report statistics (e.g., total allocated, free space, number of blocks).
- Goal: Analyze memory usage patterns and allocator performance.

#### Project 159: Memory Allocation Error Handling

- Description: Implement robust error handling for custom malloc/free (e.g., out of memory, double free).
- Goal: Develop defensive programming for memory management.

#### Project 160: Memory Allocation Debugging Hooks

- Description: Add hooks to the custom allocator to print allocation/deallocation events for debugging.
- Goal: Create custom debugging tools for memory issues.

#### Project 161: Buddy System Allocator - Allocation 🧱

- Description: Implement the allocation part of a buddy system memory allocator.
- Goal: Understand power-of-two allocation and splitting blocks.

#### Project 162: Buddy System Allocator - Deallocation

- Description: Implement the deallocation part of a buddy system, including coalescing.
- Goal: Master merging free blocks in a buddy system.

#### Project 163: Slab Allocator - Object Allocation

- Description: Implement a simple slab allocator for fixed-size objects.
- Goal: Understand object caching and efficient allocation for frequently used small objects.

#### Project 164: Slab Allocator - Object Deallocation

- Description: Implement deallocation for the slab allocator.
- Goal: Manage free lists within slabs.

#### Project 165: Memory Protection (Conceptual)

- Description: Simulate memory protection by marking certain memory regions as read-only or non-executable (conceptually, using flags in metadata).
- Goal: Understand memory access control principles.

#### Project 166: Virtual Memory (Conceptual Paging)

- Description: Simulate a simple virtual memory system with paging, mapping virtual addresses to physical frames (using arrays for page tables).
- Goal: Understand virtual memory concepts and address translation.

#### Project 167: Page Fault Simulation

- Description: Extend the virtual memory simulator to trigger and handle "page faults" when a non-resident page is accessed.
- Goal: Simulate memory management unit (MMU) behavior.

#### Project 168: Copy-on-Write (Conceptual)

- Description: Simulate copy-on-write behavior for memory pages when a "forked" process modifies shared memory.
- Goal: Understand memory optimization techniques for process creation.

#### Project 169: Memory-Mapped Files (Conceptual)

- Description: Simulate memory-mapped files by loading a file's content into a memory region and allowing direct access.
- Goal: Understand how files can be treated as memory.

#### Project 170: Custom memcpy and memset

- Description: Implement your own versions of memcpy and memset for various data types.
- Goal: Understand byte-level memory operations and optimization for data transfer.

#### Project 171: Basic Memory Leak Detector (Simple) 🐛

- Description: Create a wrapper around malloc/free to log allocations and deallocations, then report any un-freed memory at program exit.
- Goal: Learn about memory leak detection and tracking allocated blocks.

#### Project 172: Double Free Detector

- Description: Enhance the memory debugger to detect attempts to free the same memory block twice.
- Goal: Identify common memory errors.

#### Project 173: Use-After-Free Detector (Simple)

- Description: Implement a basic mechanism to detect access to memory after it has been freed (e.g., by poisoning freed memory).
- Goal: Understand use-after-free vulnerabilities.

#### Project 174: Buffer Overflow Detector (Simple)

- Description: Add canary values (sentinels) before and after allocated buffers to detect simple buffer overflows.
- Goal: Implement basic buffer overflow detection techniques.

#### Project 175: Memory Corruption Detector (Basic)

- Description: Periodically check the integrity of memory block headers/footers to detect general memory corruption.
- Goal: Understand how to verify memory integrity.

#### Project 176: Custom Assertion Library

- Description: Build a custom assertion library similar to assert.h, providing more detailed error messages.
- Goal: Master defensive programming and debugging aids.

#### Project 177: Stack Overflow Detector (Conceptual)

- Description: Simulate stack overflow detection by monitoring stack pointer movement or setting a stack limit.
- Goal: Understand stack limits and overflow conditions.

#### Project 178: Heap Corruption Detector (Basic)

- Description: Implement checks within malloc/free to detect common heap corruption patterns (e.g., invalid size, corrupted pointers).
- Goal: Deepen understanding of heap management integrity.

#### Project 179: Debugging with volatile Keyword

- Description: Write programs demonstrating the use of the volatile keyword to prevent compiler optimizations that might hide bugs in concurrent or hardware-interacting code.
- Goal: Understand volatile and its role in low-level programming.

#### Project 180: Custom Error Reporting System

- Description: Develop a centralized error reporting system that can log errors to a file or console with severity levels and timestamps.
- Goal: Design a robust and flexible error handling framework.

#### Project 181: Conceptual Process ID Generator 🆔

- Description: Write a program that simulates generating unique process IDs for conceptual "processes."
- Goal: Understand the concept of process identification.

#### Project 182: Conceptual Thread ID Generator

- Description: Simulate generating unique thread IDs for conceptual "threads" within a process.
- Goal: Understand the concept of thread identification.

#### Project 183: Process State Machine (Conceptual)

- Description: Implement a state machine for a conceptual process (e.g., New, Ready, Running, Waiting, Terminated).
- Goal: Understand process lifecycle and state transitions.

#### Project 184: Thread State Machine (Conceptual)

- Description: Implement a state machine for a conceptual thread (e.g., New, Runnable, Blocked, Terminated).
- Goal: Understand thread lifecycle and state transitions.

#### Project 185: Simple Process Table (Conceptual)

- Description: Implement a conceptual process table (array of structs) to store information about active processes.
- Goal: Understand how operating systems manage process information.

#### Project 186: Simple Thread Table (Conceptual)

- Description: Implement a conceptual thread table to store information about active threads.
- Goal: Understand how operating systems manage thread information.

#### Project 187: Process Context Switch (Conceptual)

- Description: Simulate a process context switch by saving and restoring conceptual CPU registers for different "processes."
- Goal: Understand the mechanics of context switching.

#### Project 188: Thread Context Switch (Conceptual)

- Description: Simulate a thread context switch.
- Goal: Understand the difference between process and thread context switching.

#### Project 189: Process Creation (Conceptual fork)

- Description: Simulate the fork system call by conceptually duplicating process state.
- Goal: Understand process creation mechanisms.

#### Project 190: Process Termination (Conceptual exit)

- Description: Simulate process termination, including resource cleanup.
- Goal: Understand process termination and resource management.

#### Project 191: struct Padding Explorer 📐

- Description: Create structs with different member orderings and use sizeof to observe how compiler padding affects their total size.
- Goal: Understand data structure padding and its impact on memory usage.

#### Project 192: Array Alignment Observation

- Description: Observe the memory alignment of elements within arrays of different data types.
- Goal: Understand how array elements are stored contiguously in memory.

#### Project 193: Custom alignof Implementation (Conceptual)

- Description: Implement a conceptual version of _Alignof (or alignof in C11) to determine the alignment requirement of types.
- Goal: Understand memory alignment requirements.

#### Project 194: Manual Memory Alignment

- Description: Write code to manually align memory allocations to a specific boundary (e.g., 16-byte alignment).
- Goal: Practice manual memory alignment techniques.

#### Project 195: Cache Line Awareness (Conceptual)

- Description: Write programs to conceptually demonstrate the impact of cache line alignment on performance (e.g., by accessing elements in a stride that crosses cache lines).
- Goal: Understand CPU cache behavior and its impact on performance.

#### Project 196: False Sharing Simulation (Conceptual)

- Description: Simulate false sharing in a multi-threaded context by having threads modify variables that reside on the same cache line but are logically independent.
- Goal: Understand a common concurrency performance pitfall.

#### Project 197: Data Packing in structs

- Description: Experiment with struct member ordering and bit fields to minimize memory usage (data packing).
- Goal: Learn techniques for optimizing memory footprint of data structures.

#### Project 198: Endianness Detector

- Description: Write a program to detect the endianness (byte order) of the system it's running on.
- Goal: Understand byte order and its importance in data serialization/networking.

#### Project 199: Byte Swapping Functions

- Description: Implement functions to swap bytes for different integer sizes (e.g., swap_endian_16, swap_endian_32).
- Goal: Practice bitwise operations for byte manipulation.

#### Project 200: Memory Barrier (Conceptual)

- Description: Simulate the effect of memory barriers (e.g., atomic_thread_fence) by observing instruction reordering (conceptually, through print statements).
- Goal: Understand memory ordering and its importance in concurrent programming.

B. Concurrency and Parallelism (C11 threads.h)

#### Project 201: Simple Thread Creation 🧵

- Description: Create a single thread that prints a message and then exits.
- Goal: Understand the basic thrd_create function.

#### Project 202: Multiple Thread Creation

- Description: Create multiple threads, each printing a unique message or performing a simple independent task.
- Goal: Practice creating and managing multiple threads.

#### Project 203: Thread Joining

- Description: Ensure proper termination of threads by using thrd_join to wait for their completion.
- Goal: Understand thread synchronization and waiting for thread termination.

#### Project 204: Thread Arguments

- Description: Pass arguments to threads and retrieve return values from them.
- Goal: Learn how to pass data to and from threads.

#### Project 205: Thread Detaching

- Description: Experiment with detaching threads and observe their independent execution.
- Goal: Understand detached threads and when to use them.

#### Project 206: Shared Counter (Data Race) 🏭🛒

- Description: Implement a shared counter incremented by multiple threads without synchronization, demonstrating a data race.
- Goal: Understand the concept of data races and their unpredictable outcomes.

#### Project 207: Shared Counter (Mutex Protected)

- Description: Protect the shared counter using a mutex (mtx_t) to prevent data races.
- Goal: Master mutual exclusion with mutexes.

#### Project 208: Producer-Consumer (Fixed Buffer, Mutex Only)

- Description: Implement a producer-consumer problem with a fixed-size buffer, using only mutexes for synchronization (demonstrating busy-waiting).
- Goal: Understand basic producer-consumer patterns and limitations of mutex-only solutions.

#### Project 209: Producer-Consumer (Condition Variables)

- Description: Enhance the producer-consumer solution using condition variables (cnd_t) to avoid busy-waiting.
- Goal: Master condition variables for efficient thread signaling.

#### Project 210: Producer-Consumer (Multiple Producers)

- Description: Extend the producer-consumer problem to include multiple producer threads.
- Goal: Handle contention from multiple producers.

#### Project 211: Producer-Consumer (Multiple Consumers)

- Description: Extend the producer-consumer problem to include multiple consumer threads.
- Goal: Handle contention from multiple consumers.

#### Project 212: Producer-Consumer (Bounded Buffer)

- Description: Implement a bounded buffer for the producer-consumer problem, ensuring producers wait if the buffer is full and consumers wait if it's empty.
- Goal: Implement robust buffer management in concurrent systems.

#### Project 213: Deadlock Scenario

- Description: Create a program that intentionally demonstrates a simple deadlock scenario between two threads.
- Goal: Understand the conditions that lead to deadlocks.

#### Project 214: Deadlock Prevention (Mutex Ordering)

- Description: Modify the deadlock scenario to prevent it by enforcing a consistent mutex locking order.
- Goal: Apply deadlock prevention techniques.

#### Project 215: Dining Philosophers Problem (Conceptual)

- Description: Implement a conceptual solution to the Dining Philosophers problem using mutexes and condition variables.
- Goal: Tackle a classic concurrency problem involving resource contention.

#### Project 216: Reader-Writer Problem (Basic) 📖✍️

- Description: Implement a basic reader-writer solution allowing multiple readers but only one writer at a time, using mutexes.
- Goal: Understand the fundamental reader-writer synchronization challenge.

#### Project 217: Reader-Writer Problem (Writer Priority)

- Description: Implement a reader-writer solution that gives priority to writers.
- Goal: Explore different priority schemes in concurrent access.

#### Project 218: Reader-Writer Problem (Reader Priority)

- Description: Implement a reader-writer solution that gives priority to readers.
- Goal: Understand trade-offs in reader-writer solutions.

#### Project 219: Reader-Writer Problem (Fair Solution)

- Description: Implement a fair reader-writer solution that prevents starvation of either readers or writers.
- Goal: Develop more complex synchronization logic for fairness.

#### Project 220: Shared Data Structure (Concurrent Linked List)

- Description: Implement a thread-safe linked list using mutexes for all operations (insertion, deletion, search).
- Goal: Apply synchronization primitives to protect shared data structures.

#### Project 221: Shared Data Structure (Concurrent Queue)

- Description: Implement a thread-safe queue using mutexes and condition variables.
- Goal: Build robust concurrent queues.

#### Project 222: Shared Data Structure (Concurrent Stack)

- Description: Implement a thread-safe stack using mutexes.
- Goal: Build robust concurrent stacks.

#### Project 223: Thread-Safe Logger

- Description: Make the simple log file system from the foundational phase thread-safe using mutexes.
- Goal: Apply concurrency principles to practical utilities.

#### Project 224: Thread-Local Storage (Conceptual)

- Description: Simulate thread-local storage by using an array indexed by thread ID (conceptually) or by passing unique data to each thread.
- Goal: Understand thread-specific data.

#### Project 225: Thread Cancellation (Conceptual)

- Description: Simulate thread cancellation using a shared flag and periodic checks within thread functions.
- Goal: Understand cooperative thread termination.

#### Project 226: Atomic Counter ⚛️

- Description: Implement a shared counter using atomic_fetch_add from <stdatomic.h> and compare its safety and performance with mutex-protected and unprotected versions.
- Goal: Understand atomic operations for lock-free programming.

#### Project 227: Atomic Flag

- Description: Use atomic_flag for simple spinlocks or synchronization.
- Goal: Master basic atomic synchronization primitives.

#### Project 228: Compare-and-Swap (CAS) Example

- Description: Implement a simple lock-free operation (e.g., a single-producer, single-consumer queue node update) using atomic_compare_exchange_weak/strong.
- Goal: Understand the Compare-and-Swap (CAS) primitive.

#### Project 229: Atomic Load/Store

- Description: Demonstrate atomic_load and atomic_store for safe reading and writing of shared variables.
- Goal: Understand atomic memory access.

#### Project 230: Memory Order (Conceptual)

- Description: Write programs to conceptually demonstrate different memory orders (e.g., memory_order_relaxed, memory_order_acquire, memory_order_release) and their effects on visibility.
- Goal: Deepen understanding of memory consistency models.

#### Project 231: Lock-Free Stack (Conceptual)

- Description: Implement a conceptual lock-free stack using atomic operations and CAS.
- Goal: Explore advanced lock-free data structures.

#### Project 232: Lock-Free Queue (Conceptual)

- Description: Implement a conceptual lock-free queue using atomic operations and CAS.
- Goal: Explore advanced lock-free data structures.

#### Project 233: Atomic Bit Manipulation

- Description: Implement atomic bitwise operations (e.g., atomic_fetch_or, atomic_fetch_and) for flags.
- Goal: Apply atomic operations to bit manipulation.

#### Project 234: Atomic Pointer Operations

- Description: Demonstrate atomic operations on pointers (e.g., atomic_fetch_add for pointer arithmetic).
- Goal: Understand atomic manipulation of addresses.

#### Project 235: Atomic Initialization (call_once)

- Description: Use call_once to ensure a function is executed exactly once in a multi-threaded environment.
- Goal: Master one-time initialization in concurrent programs.

#### Project 236: Simple Thread Pool - Task Queue 🏊

- Description: Implement a thread-safe queue to hold tasks for a thread pool.
- Goal: Build the core component of a thread pool.

#### Project 237: Simple Thread Pool - Worker Threads

- Description: Create a fixed number of worker threads that continuously pull tasks from the queue and execute them.
- Goal: Implement the worker logic for a thread pool.

#### Project 238: Simple Thread Pool - Task Submission

- Description: Implement a function to submit tasks (function pointers) to the thread pool's queue.
- Goal: Design the API for task submission.

#### Project 239: Simple Thread Pool - Shutdown Mechanism

- Description: Implement a graceful shutdown mechanism for the thread pool, ensuring all tasks are completed and threads exit cleanly.
- Goal: Manage the lifecycle of a thread pool.

#### Project 240: Thread Pool - Task with Arguments

- Description: Modify the thread pool to accept tasks that take arguments.
- Goal: Enhance task flexibility.

#### Project 241: Thread Pool - Task with Return Values (Conceptual)

- Description: Implement a conceptual mechanism for tasks to return values to the submitting thread (e.g., via a shared result queue).
- Goal: Understand how to retrieve results from asynchronous tasks.

#### Project 242: Thread Pool - Dynamic Sizing (Conceptual)

- Description: Simulate dynamic resizing of the thread pool based on load.
- Goal: Explore adaptive resource management.

#### Project 243: Thread Pool - Priority Queue (Conceptual)

- Description: Implement the task queue as a priority queue (conceptually) to execute high-priority tasks first.
- Goal: Understand task prioritization in concurrent systems.

#### Project 244: Thread Pool - Error Handling

- Description: Add robust error handling to the thread pool (e.g., failed thread creation, queue full).
- Goal: Ensure reliability of concurrent systems.

#### Project 245: Thread Pool - Task Cancellation (Conceptual)

- Description: Implement a conceptual mechanism to cancel pending tasks in the queue.
- Goal: Understand task cancellation in concurrent environments.

#### Project 246: Thread Pool - Thread Affinity (Conceptual)

- Description: Simulate thread affinity by conceptually assigning tasks to specific "CPU cores" or threads.
- Goal: Understand performance optimization through CPU core assignment.

#### Project 247: Thread Pool - Work Stealing (Conceptual)

- Description: Simulate a work-stealing mechanism where idle threads can "steal" tasks from busy threads' queues.
- Goal: Explore advanced load balancing techniques.

#### Project 248: Thread Pool - Futures/Promises (Conceptual)

- Description: Implement a conceptual "future" or "promise" mechanism to represent the eventual result of a submitted task.
- Goal: Understand asynchronous programming patterns.

#### Project 249: Thread Pool - Benchmarking

- Description: Benchmark the performance of the thread pool with varying numbers of threads and tasks.
- Goal: Analyze the performance characteristics of concurrent designs.

#### Project 250: Thread Pool - Integration with Console App

- Description: Integrate the thread pool into a console application to perform background tasks (e.g., file processing).
- Goal: Apply thread pools to real-world (simulated) scenarios.

C. Networking Fundamentals (Logic & Simulation)

#### Project 251: Simple Message Format Definition 💬

- Description: Define a simple text-based message format for conceptual client-server communication (e.g., TYPE:MESSAGE_BODY).
- Goal: Understand basic message structuring.

#### Project 252: Message Sender (File-based)

- Description: Implement a "client" program that writes a formatted message to a designated "outbox" file.
- Goal: Simulate sending messages via file I/O.

#### Project 253: Message Receiver (File-based)

- Description: Implement a "server" program that reads and parses messages from a designated "inbox" file.
- Goal: Simulate receiving messages via file I/O.

#### Project 254: Basic Chat Protocol (Text-based)

- Description: Define a simple text-based chat protocol including message types (e.g., JOIN, MSG, LEAVE).
- Goal: Understand protocol design for chat applications.

#### Project 255: Simulated Chat Client

- Description: Implement a "chat client" that generates and parses chat protocol messages, interacting via files.
- Goal: Simulate client-side protocol handling.

#### Project 256: Simulated Chat Server

- Description: Implement a "chat server" that processes messages from multiple simulated clients (via files) and broadcasts them.
- Goal: Simulate server-side message routing and broadcasting.

#### Project 257: Message Queue (File-based)

- Description: Implement a simple message queue using a file to store messages for asynchronous processing.
- Goal: Understand message queuing for decoupled communication.

#### Project 258: Message Serialization (Binary)

- Description: Serialize a C struct into a raw byte array for conceptual transmission.
- Goal: Understand binary data serialization.

#### Project 259: Message Deserialization (Binary)

- Description: Deserialize a raw byte array back into a C struct.
- Goal: Understand binary data deserialization.

#### Project 260: Simple Checksum Calculation

- Description: Implement a basic checksum algorithm (e.g., sum of bytes) for message integrity verification.
- Goal: Understand data integrity checks in communication.

#### Project 261: HTTP Request Line Parser 🌐➡️📄

- Description: Parse the request line (e.g., GET /index.html HTTP/1.1) from an HTTP request string.
- Goal: Learn string parsing for specific patterns.

#### Project 262: HTTP Header Parser (Single Header)

- Description: Parse a single HTTP header (e.g., Host: example.com) into key-value pairs.
- Goal: Practice string splitting and key-value extraction.

#### Project 263: HTTP Header Parser (Multiple Headers)

- Description: Parse multiple HTTP headers from a request string into a data structure.
- Goal: Handle iterative parsing of multiple lines.

#### Project 264: Full HTTP Request Parser

- Description: Parse a complete raw HTTP request string (including request line, headers, and body) into a structured C struct.
- Goal: Integrate various parsing components into a comprehensive parser.

#### Project 265: URL Path and Query Parser

- Description: Extract the path and query parameters from a URL string (e.g., /path?param=value).
- Goal: Master parsing URL components.

#### Project 266: HTTP Method Validator

- Description: Validate if a given string is a standard HTTP method (GET, POST, etc.).
- Goal: Implement string comparison for validation.

#### Project 267: HTTP Version Parser

- Description: Parse the HTTP version string (e.g., HTTP/1.1).
- Goal: Extract numerical components from a string.

#### Project 268: HTTP Request Line Generator

- Description: Generate an HTTP request line from structured data (method, path, version).
- Goal: Practice formatted string output for protocol generation.

#### Project 269: HTTP Header Generator

- Description: Generate a single HTTP header string from a key-value pair.
- Goal: Practice formatted string output for headers.

#### Project 270: Full HTTP Request Generator

- Description: Generate a complete HTTP request string from a structured C struct.
- Goal: Integrate components for full request generation.

#### Project 271: HTTP Response Status Line Generator 📄➡️🌐

- Description: Generate an HTTP response status line (e.g., HTTP/1.1 200 OK) from status code and message.
- Goal: Practice formatted string output for response headers.

#### Project 272: HTTP Response Header Generator

- Description: Generate common HTTP response headers (e.g., Content-Type, Content-Length).
- Goal: Understand standard response headers.

#### Project 273: Simple HTTP Response Generator

- Description: Generate a complete, simple HTTP response (status line, basic headers, and a "Hello World" body).
- Goal: Combine response components.

#### Project 274: HTTP Response Parser (Status Line)

- Description: Parse the status line from a raw HTTP response string.
- Goal: Extract status code and message.

#### Project 275: HTTP Response Parser (Headers)

- Description: Parse all headers from an HTTP response string.
- Goal: Handle multiple header parsing.

#### Project 276: Full HTTP Response Parser

- Description: Parse a complete raw HTTP response string (including status line, headers, and body) into a structured C struct.
- Goal: Integrate various parsing components for a comprehensive response parser.

#### Project 277: Basic HTTP Server Logic (Conceptual)

- Description: Implement the conceptual logic of a simple HTTP server that receives a request, parses it, and generates a static response.
- Goal: Understand the request-response cycle of a web server.

#### Project 278: HTTP Error Response Generator

- Description: Generate standard HTTP error responses (e.g., 404 Not Found, 500 Internal Server Error).
- Goal: Implement error handling for web protocols.

#### Project 279: HTTP Content Type Detector (Simple)

- Description: Based on a file extension, determine a simple Content-Type header (e.g., .html -> text/html, .txt -> text/plain).
- Goal: Understand MIME types and file-based content negotiation.

#### Project 280: HTTP Request Router (Conceptual)

- Description: Implement a conceptual HTTP request router that maps incoming request paths to specific handler functions.
- Goal: Understand URL routing in web applications.

#### Project 281: Basic DNS Header Parser 🗺️

- Description: Parse the fixed-size header section of a simplified DNS query packet from a byte array.
- Goal: Understand binary data parsing and bit manipulation for protocol fields.

#### Project 282: DNS Question Section Parser

- Description: Parse the question section (QNAME, QTYPE, QCLASS) from a DNS query packet.
- Goal: Handle variable-length fields and domain name compression (conceptually).

#### Project 283: Simple DNS Query Generator

- Description: Generate a basic DNS A-record query packet from a domain name.
- Goal: Practice binary data packing for protocol generation.

#### Project 284: DNS Answer Section Parser (Conceptual)

- Description: Parse a simplified DNS answer section (NAME, TYPE, CLASS, TTL, RDLENGTH, RDATA) from a response packet.
- Goal: Understand parsing of resource records.

#### Project 285: Network Byte Order Conversion Functions

- Description: Implement functions to convert between host byte order and network byte order for 16-bit and 32-bit integers.
- Goal: Master byte order conversion for network communication.

#### Project 286: IP Address Parser (IPv4)

- Description: Parse an IPv4 address string (e.g., "192.168.1.1") into its numerical components.
- Goal: Practice string parsing for IP addresses.

#### Project 287: IP Address Formatter (IPv4)

- Description: Format numerical IPv4 components back into a dotted-decimal string.
- Goal: Practice formatted string output for IP addresses.

#### Project 288: MAC Address Parser

- Description: Parse a MAC address string (e.g., "00:1A:2B:3C:4D:5E") into a byte array.
- Goal: Practice string parsing for hexadecimal values.

#### Project 289: MAC Address Formatter

- Description: Format a MAC address byte array into a colon-separated hexadecimal string.
- Goal: Practice formatted string output for MAC addresses.

#### Project 290: Simple Packet Sniffer (Conceptual)

- Description: Simulate a packet sniffer by reading raw byte data from a file and attempting to identify common protocol headers (e.g., Ethernet, IP, TCP/UDP - conceptually).
- Goal: Understand network packet structure at a low level.

#### Project 291: URL Scheme Parser 🔗

- Description: Extract the scheme (e.g., "http", "https") from a URL string.
- Goal: Practice string searching for delimiters.

#### Project 292: URL Host Parser

- Description: Extract the host (domain name or IP address) from a URL string.
- Goal: Practice string manipulation for host extraction.

#### Project 293: URL Port Parser

- Description: Extract the port number from a URL string, handling default ports if not specified.
- Goal: Practice string-to-integer conversion and conditional logic.

#### Project 294: URL Query Parameter Parser

- Description: Parse query parameters from a URL string into key-value pairs.
- Goal: Handle complex string parsing for multiple parameters.

#### Project 295: URL Fragment Parser

- Description: Extract the fragment identifier from a URL string.
- Goal: Practice string searching for specific delimiters.

#### Project 296: Full URL Parser

- Description: Implement a robust URL parser that breaks down a given URL string into all its constituent components.
- Goal: Integrate all URL parsing components into a comprehensive parser.

#### Project 297: URL Encoder (Percent-Encoding)

- Description: Implement URL percent-encoding for special characters.
- Goal: Understand URL encoding rules.

#### Project 298: URL Decoder (Percent-Decoding)

- Description: Implement URL percent-decoding.
- Goal: Understand URL decoding rules.

#### Project 299: Path Normalizer

- Description: Normalize a URL path (e.g., resolve . and .. segments).
- Goal: Implement path manipulation logic.

#### Project 300: URL Builder

- Description: Construct a URL string from its individual components.
- Goal: Practice formatted string output for URL construction.

D. Bare Metal and Embedded Concepts (Simulation)

#### Project 301: Set Bit Function 🧮

- Description: Create a function set_bit(value, bit_pos) that sets a specific bit in an integer.
- Goal: Master the bitwise OR operator (|).

#### Project 302: Clear Bit Function

- Description: Create a function clear_bit(value, bit_pos) that clears a specific bit in an integer.
- Goal: Master the bitwise AND and NOT operators (&, ~).

#### Project 303: Toggle Bit Function

- Description: Create a function toggle_bit(value, bit_pos) that flips a specific bit.
- Goal: Master the bitwise XOR operator (^).

#### Project 304: Check Bit Function

- Description: Create a function is_bit_set(value, bit_pos) that checks if a specific bit is set.
- Goal: Master bitwise AND for checking bit status.

#### Project 305: Extract Bit Field

- Description: Implement a function to extract a range of bits (a bit field) from an integer.
- Goal: Practice bit shifting and masking.

#### Project 306: Insert Bit Field

- Description: Implement a function to insert a value into a specific bit field of an integer.
- Goal: Practice complex bit manipulation for register-like operations.

#### Project 307: Rotate Left/Right (Circular Shift)

- Description: Implement functions for circular bit shifts (rotate left/right).
- Goal: Understand bit rotation for cryptographic or data manipulation tasks.

#### Project 308: Count Set Bits (Population Count)

- Description: Implement a function to count the number of set bits (1s) in an integer.
- Goal: Practice various bit counting algorithms.

#### Project 309: Find First Set Bit

- Description: Implement a function to find the position of the least significant set bit.
- Goal: Understand bit scanning techniques.

#### Project 310: Bitwise Swap (XOR Swap)

- Description: Implement a function to swap two integers without using a temporary variable, using XOR.
- Goal: Understand advanced bitwise tricks.

#### Project 311: Simulated GPIO Register (Output) 🔌

- Description: Use a volatile global integer variable to simulate a GPIO output data register. Implement functions to set/clear individual "pins" (bits).
- Goal: Understand memory-mapped I/O and volatile keyword.

#### Project 312: Simulated GPIO Register (Input)

- Description: Use another volatile global integer to simulate a GPIO input data register. Implement functions to "read" the state of individual "pins."
- Goal: Simulate reading from hardware registers.

#### Project 313: Simulated GPIO Direction Register

- Description: Use a volatile global integer to simulate a GPIO direction register. Implement functions to set "pins" as input or output.
- Goal: Understand configuring hardware peripherals.

#### Project 314: Simulated GPIO Port (Full)

- Description: Combine simulated data and direction registers to create a full simulated GPIO port with functions for setting direction and reading/writing pin states.
- Goal: Integrate multiple register concepts for a simulated peripheral.

#### Project 315: Simulated LED Array Control

- Description: Use the simulated GPIO to control a conceptual array of LEDs (represented by bits in a variable), making them light up in patterns.
- Goal: Apply simulated I/O to a practical embedded scenario.

#### Project 316: Simulated Button Input

- Description: Simulate button presses by manually changing bits in the simulated input register and having the program detect these changes.
- Goal: Simulate reading digital input from hardware.

#### Project 317: Simulated 7-Segment Display Driver

- Description: Implement a function that takes a digit (0-9) and outputs the corresponding bit pattern to a simulated 7-segment display (using a GPIO register).
- Goal: Understand driving common display hardware.

#### Project 318: Simulated LCD Character Driver (Conceptual)

- Description: Simulate sending characters to a conceptual LCD display by manipulating simulated data and control registers.
- Goal: Understand basic LCD interfacing principles.

#### Project 319: Simulated Analog-to-Digital Converter (ADC)

- Description: Simulate an ADC by having a function return a scaled integer value based on a conceptual analog input.
- Goal: Understand analog input conversion.

#### Project 320: Simulated Digital-to-Analog Converter (DAC)

- Description: Simulate a DAC by having a function take an integer and conceptually "output" an analog value.
- Goal: Understand analog output conversion.

#### Project 321: Simple Polling-Based Interrupt Simulation ⚡

- Description: Use a volatile flag variable to simulate an interrupt. The main loop continuously polls this flag, and when set, calls a registered "ISR" function pointer.
- Goal: Understand polling for events and function pointers for callbacks.

#### Project 322: Interrupt Enable/Disable Simulation

- Description: Simulate global interrupt enable/disable by using a flag that controls whether the polling loop checks the interrupt flag.
- Goal: Understand interrupt masking.

#### Project 323: Multiple Interrupt Sources Simulation

- Description: Simulate multiple interrupt sources, each with its own flag and ISR, and implement a basic priority scheme.
- Goal: Understand handling multiple interrupt events.

#### Project 324: Nested Interrupt Simulation (Conceptual)

- Description: Simulate nested interrupts where an ISR can be interrupted by a higher-priority interrupt.
- Goal: Understand interrupt priority and re-entrancy.

#### Project 325: Timer Interrupt Simulation

- Description: Simulate a timer interrupt that triggers periodically, calling an ISR.
- Goal: Understand timer-based events.

#### Project 326: External Interrupt Simulation (Button)

- Description: Simulate an external interrupt triggered by a button press, calling an ISR.
- Goal: Understand event-driven interrupts.

#### Project 327: Interrupt Vector Table (Conceptual)

- Description: Use an array of function pointers to simulate an interrupt vector table, mapping interrupt numbers to ISRs.
- Goal: Understand how ISRs are dispatched.

#### Project 328: Critical Section Protection (Conceptual)

- Description: Demonstrate protecting critical sections within an ISR or main loop using simulated interrupt enable/disable.
- Goal: Understand atomic operations in bare-metal.

#### Project 329: Interrupt Latency Measurement (Conceptual)

- Description: Conceptually measure the "latency" of an interrupt by tracking time from flag set to ISR entry.
- Goal: Understand performance metrics in real-time systems.

#### Project 330: Debouncing (Conceptual)

- Description: Implement a conceptual software debouncing algorithm for a simulated button input to prevent multiple triggers from a single press.
- Goal: Understand input signal conditioning.

#### Project 331: Simple Busy-Wait Delay (Milliseconds) ⏳

- Description: Implement a delay_ms(ms) function using a calibrated empty loop for millisecond delays.
- Goal: Understand basic software delays and their limitations.

#### Project 332: Simple Busy-Wait Delay (Microseconds)

- Description: Implement a delay_us(us) function for microsecond delays.
- Goal: Refine delay calibration for finer granularity.

#### Project 333: Timer Counter Simulation

- Description: Simulate a hardware timer that increments a counter at a fixed rate.
- Goal: Understand timer hardware principles.

#### Project 334: Pulse Width Modulation (PWM) Simulation (Conceptual)

- Description: Simulate PWM by toggling a bit in a simulated GPIO register with varying on/off times based on a duty cycle.
- Goal: Understand PWM for motor control or dimming LEDs.

#### Project 335: Watchdog Timer Simulation (Conceptual)

- Description: Simulate a watchdog timer that resets the system (e.g., prints a reset message) if not "fed" periodically.
- Goal: Understand system reliability mechanisms.

#### Project 336: UART Transmitter Logic (Bit-Banging) 📡

- Description: Implement the logic to "transmit" a character bit by bit over a simulated serial line (e.g., a single bit in a GPIO register), including start/stop bits.
- Goal: Understand serial communication protocols at a low level.

#### Project 337: UART Receiver Logic (Bit-Banging)

- Description: Implement the logic to "receive" a character bit by bit from a simulated serial line.
- Goal: Understand serial data reception and sampling.

#### Project 338: UART Full Duplex Simulation

- Description: Combine transmitter and receiver logic for simulated full-duplex UART communication.
- Goal: Simulate bidirectional serial communication.

#### Project 339: SPI Master Logic (Bit-Banging)

- Description: Implement the logic for a simulated SPI master to send data to a conceptual slave device.
- Goal: Understand SPI protocol for synchronous communication.

#### Project 340: SPI Slave Logic (Bit-Banging)

- Description: Implement the logic for a simulated SPI slave to receive data from a master.
- Goal: Understand SPI slave behavior.

#### Project 341: I2C Master Logic (Bit-Banging)

- Description: Implement the logic for a simulated I2C master to send/receive data to/from a conceptual slave device.
- Goal: Understand I2C protocol for two-wire communication.

#### Project 342: CRC Calculation (Cyclic Redundancy Check)

- Description: Implement a simple CRC algorithm (e.g., CRC-8 or CRC-16) for data integrity checking in communication protocols.
- Goal: Understand error detection codes.

#### Project 343: Packet Framing (Start/Stop Bytes)

- Description: Implement a function to frame data packets with start and stop bytes for reliable transmission.
- Goal: Understand data packetization.

#### Project 344: Escape Sequences in Protocols

- Description: Implement logic to handle escape sequences within a simulated protocol to prevent data bytes from being misinterpreted as control bytes.
- Goal: Understand byte stuffing in protocols.

#### Project 345: Simple State Machine for Protocol Parsing

- Description: Implement a state machine to parse incoming bytes according to a simple custom protocol.
- Goal: Apply state machines to protocol decoding.

#### Project 346: Simulated LED Blinker (GPIO + Delay) 💡

- Description: Combine simulated GPIO output and custom delay functions to make a conceptual LED blink.
- Goal: Integrate basic bare-metal concepts.

#### Project 347: Simulated Traffic Light Controller

- Description: Use simulated GPIOs and timers to control a conceptual traffic light sequence.
- Goal: Implement state machines for real-time control.

#### Project 348: Simulated Keypad Input

- Description: Simulate a 4x4 keypad by mapping key presses to specific bit patterns on simulated GPIO input pins.
- Goal: Understand matrix keypad scanning.

#### Project 349: Simulated Motor Control (Direction)

- Description: Use simulated GPIOs to control the direction of a conceptual motor.
- Goal: Understand basic motor interfacing.

#### Project 350: Simulated Motor Control (Speed - PWM)

- Description: Extend simulated motor control to include speed adjustment using conceptual PWM.
- Goal: Apply PWM to motor speed control.

E. Security and Cryptography (Algorithm Implementation)

#### Project 351: Simple XOR Cipher (Fixed Key) 🔑

- Description: Implement a basic symmetric encryption and decryption scheme using the XOR bitwise operation with a fixed, hardcoded key.
- Goal: Understand fundamental bitwise encryption principles.

#### Project 352: Simple XOR Cipher (Repeating Key)

- Description: Implement the XOR cipher with a repeating key (e.g., "KEY" encrypts "HELLO" as H^K, E^E, L^Y, L^K, O^E).
- Goal: Understand key repetition in stream ciphers.

#### Project 353: Caesar Cipher (Encryption)

- Description: Implement the Caesar cipher for text encryption, shifting each letter by a fixed amount.
- Goal: Learn about simple substitution ciphers.

#### Project 354: Caesar Cipher (Decryption)

- Description: Implement decryption for the Caesar cipher.
- Goal: Understand the inverse operation of a substitution cipher.

#### Project 355: Caesar Cipher (Brute-Force Decryptor)

- Description: Write a program to attempt to brute-force decrypt a Caesar cipher by trying all possible shift values.
- Goal: Understand basic cryptanalysis and frequency analysis (conceptually).

#### Project 356: Vigenere Cipher (Encryption) 🔐

- Description: Implement the Vigenere cipher for text encryption using a keyword.
- Goal: Understand polyalphabetic substitution ciphers.

#### Project 357: Vigenere Cipher (Decryption)

- Description: Implement decryption for the Vigenere cipher.
- Goal: Master the inverse operation of a Vigenere cipher.

#### Project 358: Rail Fence Cipher (Encryption) 🔠

- Description: Implement the Rail Fence cipher, a simple transposition cipher.
- Goal: Explore permutation-based encryption techniques.

#### Project 359: Rail Fence Cipher (Decryption)

- Description: Implement decryption for the Rail Fence cipher.
- Goal: Understand the inverse operation of a transposition cipher.

#### Project 360: Columnar Transposition Cipher (Encryption)

- Description: Implement a basic columnar transposition cipher using a keyword to reorder columns.
- Goal: Understand more complex transposition ciphers.

#### Project 361: Simple Checksum (Sum of Bytes) #️⃣

- Description: Implement a basic checksum algorithm by summing the ASCII values of characters in a string.
- Goal: Understand basic data integrity checks.

#### Project 362: Polynomial Rolling Hash

- Description: Implement a polynomial rolling hash function for strings.
- Goal: Understand a common non-cryptographic hash used in string matching.

#### Project 363: FNV-1a Hash Function

- Description: Implement the FNV-1a non-cryptographic hash function.
- Goal: Learn about a simple, fast hash algorithm.

#### Project 364: Simple Message Digest (Conceptual)

- Description: Create a conceptual "message digest" by combining a simple hash with a fixed-size output.
- Goal: Understand the concept of a message digest.

#### Project 365: Password Hashing (Simple Iteration)

- Description: Implement a simple password hashing scheme by repeatedly applying a basic hash function (e.g., FNV-1a) to a password.
- Goal: Understand the concept of stretching a hash for password security (without salt).

#### Project 366: Linear Congruential Generator (LCG) 🎲

- Description: Implement a Linear Congruential Generator (LCG) for pseudo-random number generation.
- Goal: Understand the principles of pseudo-randomness.

#### Project 367: Seedable PRNG

- Description: Make the LCG seedable using time(NULL) for different sequences.
- Goal: Understand the importance of seeding PRNGs.

#### Project 368: PRNG Statistical Test (Frequency)

- Description: Perform a simple statistical test (e.g., frequency distribution of generated numbers) on the PRNG output.
- Goal: Understand basic PRNG quality assessment.

#### Project 369: PRNG Statistical Test (Runs Test)

- Description: Perform a simple runs test on the PRNG output to check for patterns.
- Goal: Further PRNG quality assessment.

#### Project 370: True Randomness (Conceptual)

- Description: Discuss and conceptually simulate sources of true randomness (e.g., user input timing, environmental noise) versus pseudo-randomness.
- Goal: Understand the difference between true and pseudo-randomness.

#### Project 371: Safe String Copy (strncpy usage) 🛡️

- Description: Write functions that safely copy strings using strncpy and ensure null termination, preventing buffer overflows.
- Goal: Master safe string handling to prevent vulnerabilities.

#### Project 372: Safe String Concatenation (strncat usage)

- Description: Write functions that safely concatenate strings using strncat.
- Goal: Prevent buffer overflows during string concatenation.

#### Project 373: Input Buffer Overflow Prevention (fgets)

- Description: Implement a function to read user input using fgets and correctly handle newline characters and buffer limits.
- Goal: Securely read user input from stdin.

#### Project 374: Integer Overflow Detection (Addition)

- Description: Write functions to perform addition on integers and detect potential integer overflows.
- Goal: Understand integer overflow vulnerabilities.

#### Project 375: Integer Overflow Detection (Multiplication)

- Description: Write functions to perform multiplication on integers and detect potential integer overflows.
- Goal: Understand integer overflow in multiplication.

#### Project 376: Format String Vulnerability (Conceptual)

- Description: Write a program that conceptually demonstrates a format string vulnerability (without exploiting it).
- Goal: Understand format string vulnerabilities and how to avoid them.

#### Project 377: Secure Memory Zeroing

- Description: Implement a function to securely zero out memory regions (e.g., after sensitive data is no longer needed) to prevent data remnants.
- Goal: Understand secure memory practices.

#### Project 378: Input Sanitization (Basic)

- Description: Implement a function to sanitize user input by removing or escaping potentially harmful characters (e.g., shell metacharacters).
- Goal: Prevent command injection or cross-site scripting (conceptual).

#### Project 379: Privilege Separation (Conceptual)

- Description: Simulate privilege separation by having different parts of a program operate with different conceptual "privilege levels."
- Goal: Understand security principle of least privilege.

#### Project 380: Secure Random Number Generation (Conceptual)

- Description: Discuss and conceptually outline how cryptographically secure pseudo-random number generators (CSPRNGs) differ from simple PRNGs.
- Goal: Understand the requirements for secure randomness.

#### Project 381: Simple Substitution Cipher (Advanced)

- Description: Implement a more complex substitution cipher (e.g., using a shuffled alphabet).
- Goal: Deepen understanding of substitution ciphers.

#### Project 382: Polybius Square Cipher

- Description: Implement the Polybius Square cipher for encryption and decryption.
- Goal: Explore grid-based ciphers.

#### Project 383: Playfair Cipher (Conceptual)

- Description: Implement the Playfair cipher, a digraphic substitution cipher.
- Goal: Understand multi-letter substitution.

#### Project 384: Hill Cipher (2x2 Matrix, Conceptual)

- Description: Implement a conceptual Hill cipher using 2x2 matrices and modular arithmetic (without external linear algebra libraries).
- Goal: Understand matrix-based encryption.

#### Project 385: One-Time Pad (Conceptual)

- Description: Implement a conceptual one-time pad cipher, demonstrating its perfect secrecy if the key is truly random and used only once.
- Goal: Understand the theoretical limits of cryptography.

#### Project 386: Simple Stream Cipher (LFSR-based, Conceptual)

- Description: Implement a conceptual stream cipher based on a Linear Feedback Shift Register (LFSR).
- Goal: Understand basic stream cipher principles.

#### Project 387: Block Cipher Mode (ECB, Conceptual)

- Description: Implement a conceptual Electronic Codebook (ECB) mode for a simple block cipher.
- Goal: Understand basic block cipher modes and their weaknesses.

#### Project 388: Block Cipher Mode (CBC, Conceptual)

- Description: Implement a conceptual Cipher Block Chaining (CBC) mode for a simple block cipher.
- Goal: Understand chaining modes and initialization vectors.

#### Project 389: Diffie-Hellman Key Exchange (Conceptual)

- Description: Implement a conceptual Diffie-Hellman key exchange to demonstrate shared secret generation over an insecure channel.
- Goal: Understand public-key cryptography principles.

#### Project 390: RSA Algorithm (Conceptual, Small Numbers)

- Description: Implement a conceptual RSA algorithm for encryption/decryption with very small prime numbers to demonstrate the math.
- Goal: Understand asymmetric cryptography principles.

#### Project 391: Digital Signature (Conceptual)

- Description: Simulate a digital signature process using a conceptual private key for signing and public key for verification.
- Goal: Understand digital signature concepts.

#### Project 392: Certificate Authority (Conceptual)

- Description: Simulate a simple Certificate Authority (CA) that issues and verifies conceptual digital certificates.
- Goal: Understand PKI (Public Key Infrastructure) basics.

#### Project 393: Secure Hash Algorithm (SHA-1/SHA-256 Conceptual)

- Description: Implement a simplified version of a secure hash algorithm (e.g., a few rounds of SHA-1/SHA-256) to understand its internal workings.
- Goal: Understand cryptographic hash functions.

#### Project 394: Message Authentication Code (MAC, Conceptual)

- Description: Implement a conceptual MAC using a shared secret key and a hash function.
- Goal: Understand message integrity and authenticity.

#### Project 395: Key Derivation Function (KDF, Conceptual)

- Description: Implement a simple KDF to derive cryptographic keys from a master secret.
- Goal: Understand key management.

#### Project 396: Password Salting (Conceptual)

- Description: Implement password salting by adding a unique random string to each password before hashing.
- Goal: Understand defense against rainbow table attacks.

#### Project 397: Password Stretching (Conceptual)

- Description: Implement password stretching by repeatedly hashing a password and salt combination.
- Goal: Understand defense against brute-force attacks.

#### Project 398: Secure Communication Channel (Conceptual)

- Description: Simulate a secure communication channel by encrypting and decrypting messages exchanged between two conceptual parties.
- Goal: Integrate cryptographic primitives for secure communication.

#### Project 399: Side-Channel Attack (Conceptual)

- Description: Conceptually demonstrate a simple side-channel attack (e.g., timing attack on a comparison function).
- Goal: Understand non-cryptographic attack vectors.

#### Project 400: Threat Modeling (Conceptual)

- Description: For a simple application, conceptually identify potential threats and vulnerabilities.
- Goal: Understand basic threat modeling principles.
