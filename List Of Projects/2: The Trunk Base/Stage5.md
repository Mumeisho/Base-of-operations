# Stage 5: Conditional Logic (Projects 33-50)

**Learning Goal**: Master decision-making in programs

## TB1: **Simple Decision Maker**

- **Description**: Create a threshold checker that reads a number and makes a single decision: if the number is greater than 100, display a congratulations message with the amount over 100. This introduces the basic if statement structure.
- **Prerequisites**: R17, R22
- **New Concept**: Basic if statement

## TB2: **Two-Path Chooser**

- **Description**: Build a login simulator that reads a password (as integer) and uses if-else to either grant access or deny it. Show different messages for each path and track login attempt in a variable.
- **Prerequisites**: TB1
- **New Concept**: if-else statement

## TB3: **Number Relationship Analyzer**

- **Description**: Develop a program that reads two numbers and displays their complete relationship: which is larger, if they're equal, their difference, and percentage difference. Use multiple if-else statements for comprehensive analysis.
- **Prerequisites**: TB2, R19
- **New Concept**: Multiple if-else decisions

## TB4: **Grade Classification System**

- **Description**: Create an academic grade converter that transforms numeric scores (0-100) into letter grades (A, B, C, D, F) with plus/minus modifiers. Include grade point calculation and dean's list qualification check.
- **Prerequisites**: TB2, TB3
- **New Concept**: else-if chains

## TB5: **Number Property Detector**

- **Description**: Build a comprehensive number analyzer that determines: even/odd, positive/negative/zero, single/double/triple digit, prime (for small numbers), perfect square, and divisibility by 3, 5, and 7.
- **Prerequisites**: R26, TB4
- **New Concept**: Multiple independent conditions

## TB6: **Leap Year Calculator**

- **Description**: Implement the complete leap year algorithm: divisible by 4 but not by 100, unless also divisible by 400. Test with historical years and future years, showing the reasoning for each decision.
- **Prerequisites**: TB4, R29
- **New Concept**: Nested logical conditions

## TB7: **Age Category Classifier**

- **Description**: Create a life stage classifier that categorizes ages into: infant (0-2), child (3-12), teen (13-19), young adult (20-35), adult (36-60), senior (60+) with specific advice for each category.
- **Prerequisites**: TB4
- **New Concept**: Range-based conditions

## TB8: **Triangle Validator**

- **Description**: Build a triangle analyzer that reads three sides and determines: if they form a valid triangle, the type (equilateral, isosceles, scalene), if it's a right triangle, and calculates area using Heron's formula.
- **Prerequisites**: TB6, R25
- **New Concept**: Complex validation logic

## TB9: **Password Strength Analyzer**

- **Description**: Develop a password strength checker that evaluates based on length, presence of numbers (simulated), and special character count. Assign strength levels: weak, moderate, strong, very strong.
- **Prerequisites**: R18, TB5
- **New Concept**: Multi-criteria evaluation

## TB10: **Nested Decision Tree**

- **Description**: Create a technical support troubleshooter with nested if statements creating a decision tree. Guide users through 4 levels of questions to diagnose a computer problem, with at least 8 possible outcomes.
- **Prerequisites**: TB6, TB8
- **New Concept**: Deep nesting of conditions

## TB11: **Calculator Menu System**

- **Description**: Build a menu-driven calculator using switch statement. Support 8 operations: basic arithmetic, power, square root (approximation), percentage, and modulo. Include proper menu display and error handling.
- **Prerequisites**: R31, TB2
- **New Concept**: switch statement

## TB12: **Day of Week Processor**

- **Description**: Create a day scheduler using switch that converts day numbers (1-7) to names, suggests activities, shows if it's weekend/weekday, and calculates days until weekend.
- **Prerequisites**: TB11
- **New Concept**: switch with multiple actions

## TB13: **Character Type Identifier**

- **Description**: Develop a character classifier using switch and if statements that identifies: uppercase letter, lowercase letter, digit, arithmetic operator, comparison operator, whitespace, or special symbol with specific uses for each.
- **Prerequisites**: R12, TB11
- **New Concept**: Character classification logic

## TB14: **Tax Bracket Calculator**

- **Description**: Implement a progressive tax calculator with brackets: 0-10k (0%), 10-30k (10%), 30-60k (20%), 60-100k (30%), 100k+ (35%). Calculate tax for each bracket and total tax owed with detailed breakdown.
- **Prerequisites**: TB7, TB10
- **New Concept**: Progressive calculations

## TB15: **Discount Engine**

- **Description**: Build a shopping discount system with rules: 5% for $50+, 10% for $100+, 15% for $200+, plus extra 5% for members. Calculate savings and final price with detailed receipt.
- **Prerequisites**: TB14
- **New Concept**: Cumulative conditions

## TB16: **Time Zone Converter**

- **Description**: Create a world clock that converts between 8 time zones using switch and handles day changes. Input time in one zone and show corresponding times in all others with AM/PM notation.
- **Prerequisites**: TB11, TB7
- **New Concept**: Complex switch logic

## TB17: **Logic Gate Simulator**

- **Description**: Implement a digital logic simulator for AND, OR, NOT, NAND, NOR, XOR gates. Read two inputs (0/1) and show truth tables for all gates. Include compound gate expressions.
- **Prerequisites**: R29, TB13
- **New Concept**: Boolean logic implementation

## TB18: **TEST: Banking System**

- **Description**: Create a complete banking system with: account type selection (checking/savings), transaction menu (deposit/withdraw/transfer/balance), interest calculation for savings, overdraft protection for checking, transaction limits based on account type, fee calculation for various services, monthly statement generator, and input validation for all operations.
- **Prerequisites**: TB1-TB17
- **New Concept**: Integration of all conditional logic concepts
