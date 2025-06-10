# Stage 7: Functions Fundamentals (Projects 69-86)

**Learning Goal**: Master function creation and usage

## TB37: **Simple Calculator Functions**

- **Description**: Create separate functions for add, subtract, multiply, and divide that take two parameters and return results. Call each function from main() with user input and display results with function names.
- **Prerequisites**: TB11, R30
- **New Concept**: Function definition and return values

## TB38: **Temperature Conversion Library**

- **Description**: Build a temperature conversion library with 6 functions: celsiusToFahrenheit, fahrenheitToCelsius, celsiusToKelvin, etc. Each function takes one parameter and returns converted value with proper precision.
- **Prerequisites**: TB37, R20
- **New Concept**: Single parameter functions

## TB39: **Mathematical Operations Suite**

- **Description**: Develop math functions for: maximum of 3 numbers, minimum of 3 numbers, average of 3 numbers, absolute value, and integer power. Show how return values can be used in expressions.
- **Prerequisites**: TB37, TB23
- **New Concept**: Multiple parameter functions

## TB40: **Display Formatting Functions**

- **Description**: Create void functions that display formatted output: printHeader(title), printSeparator(length), printCentered(text, width), and printBox(message). No return values, only display actions.
- **Prerequisites**: TB37, R5
- **New Concept**: Void functions

## TB41: **Validation Function Library**

- **Description**: Build validation functions that return 1 (true) or 0 (false): isPositive, isInRange, isEven, isPrime, isValidGrade. Use these in main() to validate user inputs with clear messages.
- **Prerequisites**: TB39, TB27
- **New Concept**: Boolean-style functions

## TB42: **Scope Demonstration Lab**

- **Description**: Create a program demonstrating variable scope with functions that: show local variables hiding globals, modify local copies without affecting originals, and use different variables with same names.
- **Prerequisites**: TB37, R14
- **New Concept**: Variable scope in functions

## TB43: **Function Prototype Explorer**

- **Description**: Develop a program with all function prototypes at top, main() in middle, and function definitions at bottom. Include 5 different functions showing proper prototype syntax and organization.
- **Prerequisites**: TB37
- **New Concept**: Function prototypes

## TB44: **Recursive Factorial Calculator**

- **Description**: Implement factorial using recursion, showing call stack with indentation. Display each recursive call and return value. Compare with iterative version for understanding.
- **Prerequisites**: TB22, TB43
- **New Concept**: Basic recursion

## TB45: **Geometry Function Library**

- **Description**: Create a geometry calculator with functions for: circle area/circumference, rectangle area/perimeter, triangle area, sphere volume, and cylinder volume. Properly organize with prototypes.
- **Prerequisites**: TB43, TB39
- **New Concept**: Function library design

## TB46: **String Operation Functions**

- **Description**: Build string functions without string.h: stringLength, stringCopy, stringCompare, and stringReverse. Use character arrays and loops inside functions to manipulate strings.
- **Prerequisites**: TB40, TB24
- **New Concept**: Array parameters in functions

## TB47: **Function Chain Calculator**

- **Description**: Create functions that call other functions: calculateTax calls getTaxRate, getDiscount calls getMembershipLevel, etc. Show function call hierarchy with 3 levels of nesting.
- **Prerequisites**: TB45, TB14
- **New Concept**: Functions calling functions

## TB48: **Parameter Validation System**

- **Description**: Develop functions that validate their parameters before processing: checkDivision (non-zero divisor), checkSquareRoot (non-negative), checkArrayBounds (valid index). Return error codes.
- **Prerequisites**: TB41, TB29
- **New Concept**: Defensive programming

## TB49: **Recursive Fibonacci Generator**

- **Description**: Implement Fibonacci using recursion with memoization concept (using static variables). Show recursive calls, compare performance with iterative version, and explain efficiency.
- **Prerequisites**: TB44, TB26
- **New Concept**: Advanced recursion

## TB50: **Function Pointer Basics**

- **Description**: Create a simple calculator using function pointers to select operations. Store add, subtract, multiply, divide functions in pointer array and call based on user choice.
- **Prerequisites**: TB37, TB11
- **New Concept**: Function pointers

## TB51: **Callback Function Demo**

- **Description**: Build a number processor that accepts a function pointer as parameter. Pass different functions (double, square, negate) to process array of numbers showing callback concept.
- **Prerequisites**: TB50
- **New Concept**: Callback functions

## TB52: **Modular Grade System**

- **Description**: Design a complete grading system with modules: input functions, validation functions, calculation functions, display functions. Show proper separation of concerns with 10+ functions working together.
- **Prerequisites**: TB45, TB47, R24
- **New Concept**: Modular design

## TB53: **Function Testing Framework**

- **Description**: Create a test framework that tests other functions with multiple inputs, compares expected vs actual results, reports pass/fail for each test, and summarizes test results. Test 5 mathematical functions.
- **Prerequisites**: TB41, TB52
- **New Concept**: Function testing

## TB54: **TEST: Scientific Function Library**

- **Description**: Build a comprehensive scientific calculator library with: trigonometric approximations (sine, cosine using Taylor series), logarithm approximation, statistical functions (mean, variance, standard deviation), combinatorics (permutation, combination), proper error handling for all functions, function pointer menu system, recursive and iterative options, and complete documentation for each function.
- **Prerequisites**: TB37-TB53
- **New Concept**: Integration of all function concepts
