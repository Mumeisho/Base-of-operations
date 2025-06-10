# Stage 6: Repetition and Loops (Projects 51-68)

**Learning Goal**: Master iteration and repetitive tasks

## TB19: **Counting Demonstrator**

- **Description**: Create a counting program using for loops that counts: forward 1-20, backward 20-1, by twos to 30, by fives to 100, and shows the loop variable at each step with formatted output.
- **Prerequisites**: TB1
- **New Concept**: Basic for loop

## TB20: **Arithmetic Series Calculator**

- **Description**: Build a summation calculator that computes: sum of 1 to N, sum of squares, sum of cubes, alternating sum (1-2+3-4...), and harmonic series approximation. Display running totals at each step.
- **Prerequisites**: TB19, R25
- **New Concept**: Accumulation in loops

## TB21: **Multiplication Table Generator**

- **Description**: Create a formatted multiplication table generator that produces tables for any number, shows tables from 1-10 in a grid format, and includes row/column headers with proper alignment.
- **Prerequisites**: TB19, R4
- **New Concept**: Loop-based formatting

## TB22: **Factorial Calculator**

- **Description**: Implement factorial calculation showing each multiplication step. Handle factorials up to 20 (using long long), display the calculation process (5! = 5 × 4 × 3 × 2 × 1 = 120), and check for overflow.
- **Prerequisites**: TB20
- **New Concept**: Progressive multiplication

## TB23: **Power Calculator Engine**

- **Description**: Build a power calculator using loops (no pow function) that handles positive/negative exponents, shows the multiplication process, handles base cases (x^0, 0^x), and validates inputs.
- **Prerequisites**: TB22, TB15
- **New Concept**: Conditional loop logic

## TB24: **Digit Manipulator**

- **Description**: Create a digit processor that: reverses a number, sums all digits, finds largest/smallest digit, counts occurrences of each digit, and checks for palindromes. Show digit extraction process.
- **Prerequisites**: R26, TB20
- **New Concept**: Digit extraction loops

## TB25: **Pattern Printer Suite**

- **Description**: Generate 5 different patterns using nested loops: right triangle of stars, inverted triangle, diamond shape, hollow rectangle, and number pyramid. Allow user to specify size.
- **Prerequisites**: TB21
- **New Concept**: Nested for loops

## TB26: **Fibonacci Sequence Generator**

- **Description**: Implement Fibonacci generator that: shows first N terms, finds Fibonacci numbers below a limit, calculates golden ratio approximation, and identifies which term exceeds user input.
- **Prerequisites**: TB20, TB19
- **New Concept**: Sequential calculation

## TB27: **Prime Number Detector**

- **Description**: Build a prime checker using trial division that shows all divisor tests, optimizes by checking only up to square root, and explains why each number is/isn't prime with factor listing.
- **Prerequisites**: TB19, TB8
- **New Concept**: Early loop termination

## TB28: **While Loop Counter**

- **Description**: Create a countdown timer using while loop that: counts seconds with delay simulation, shows time in MM:SS format, allows user to set duration, and includes pause/resume simulation.
- **Prerequisites**: TB19, TB16
- **New Concept**: while loop

## TB29: **Input Validation Loop**

- **Description**: Develop a robust input system using while loops that keeps requesting until valid input received. Validate: number in range, positive values, non-zero for division, and specific character choices.
- **Prerequisites**: TB28, R22
- **New Concept**: Validation loops

## TB30: **Menu System Navigator**

- **Description**: Build a complete menu system using do-while that continues until user exits. Include main menu, submenus, action confirmation, and return to previous menu options with clear navigation.
- **Prerequisites**: TB11, TB29
- **New Concept**: do-while loop

## TB31: **Number Guessing Game**

- **Description**: Create a guess-the-number game that: generates random number (using time-based seed), gives hints (higher/lower), counts attempts, calculates score based on attempts, and offers replay option.
- **Prerequisites**: TB30, TB2
- **New Concept**: Game loop design

## TB32: **Nested Pattern Generator**

- **Description**: Build an advanced pattern creator with nested loops producing: Pascal's triangle (first 10 rows), multiplication grid, chess board pattern, and spiral number pattern. Use proper formatting.
- **Prerequisites**: TB25, TB21
- **New Concept**: Complex nested loops

## TB33: **Prime Number Lister**

- **Description**: Create a prime number suite that lists all primes up to N using Sieve of Eratosthenes, shows twin primes, calculates prime density, and finds the Nth prime number.
- **Prerequisites**: TB27, TB32
- **New Concept**: Algorithm optimization

## TB34: **Perfect Number Finder**

- **Description**: Implement a perfect number detector that finds all perfect numbers up to 10,000, shows their divisors, calculates abundancy index, and classifies numbers as perfect/abundant/deficient.
- **Prerequisites**: TB20, TB33
- **New Concept**: Mathematical sequences

## TB35: **Loop Control Demonstrator**

- **Description**: Create a program showing break and continue usage: skip even numbers, exit on sentinel value, continue until condition met, and break from nested loops with clear demonstrations.
- **Prerequisites**: TB29, TB32
- **New Concept**: break and continue

## TB36: **TEST: Statistical Analysis Engine**

- **Description**: Build a statistics calculator that: reads numbers until sentinel value, calculates mean/median/mode, finds minimum/maximum, computes standard deviation, generates frequency distribution, handles invalid inputs gracefully, displays histogram of values, and shows all calculations step-by-step.
- **Prerequisites**: TB19-TB35
- **New Concept**: Integration of all loop concepts
