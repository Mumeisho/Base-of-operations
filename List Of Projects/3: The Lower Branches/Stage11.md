# Stage 11: Structures and User-Defined Types (Projects 153-176)

**Learning Goal**: Master structured data and custom types

## LB49: **Structure Definition Basics**

- **Description**: Create a person structure with name, age, height, and weight. Declare variables of this type, initialize them using different methods, and display all fields with proper formatting.
- **Prerequisites**: R9, LB25
- **New Concept**: Structure definition and declaration

## LB50: **Structure Initialization Patterns**

- **Description**: Build examples showing 5 initialization methods: member-by-member assignment, initializer list, designated initializers, copying from another structure, and default initialization. Compare each approach.
- **Prerequisites**: LB49, R10
- **New Concept**: Structure initialization

## LB51: **Student Record System**

- **Description**: Develop a student management system with structure containing: ID, name, grades array, GPA. Implement functions to calculate GPA, display records, and find top student from array of structures.
- **Prerequisites**: LB50, TB72
- **New Concept**: Structures with arrays

## LB52: **Structure Array Manager**

- **Description**: Create an employee database using array of structures storing: employee ID, name, department, salary. Implement add, display all, search by ID, and calculate department totals.
- **Prerequisites**: LB51, TB58
- **New Concept**: Arrays of structures

## LB53: **Structure Pointer Operations**

- **Description**: Build pointer demonstrations with structures: arrow operator vs dot operator, passing structures to functions by pointer, returning structure pointers, and pointer arithmetic with structure arrays.
- **Prerequisites**: LB52, LB6
- **New Concept**: Structure pointers

## LB54: **Point and Distance Calculator**

- **Description**: Create 2D point structure with x,y coordinates. Implement functions for: distance between points, midpoint calculation, point translation, and rotation around origin. Use proper mathematical formulas.
- **Prerequisites**: LB49, TB45
- **New Concept**: Geometric structures

## LB55: **Rectangle Geometry System**

- **Description**: Design rectangle structure using two points (top-left, bottom-right). Calculate area, perimeter, center point, overlap detection with another rectangle, and point-inside-rectangle test.
- **Prerequisites**: LB54
- **New Concept**: Composite structures

## LB56: **Date Structure Handler**

- **Description**: Implement date structure with day/month/year. Create functions for: date validation, leap year checking, days between dates, date arithmetic (add days), and date formatting.
- **Prerequisites**: LB49, TB6
- **New Concept**: Date handling

## LB57: **Time Structure Calculator**

- **Description**: Build time structure with hours/minutes/seconds. Implement: time validation, time arithmetic (add/subtract), time difference, 12/24 hour format conversion, and elapsed time calculation.
- **Prerequisites**: LB56, TB16
- **New Concept**: Time arithmetic

## LB58: **Nested Structure Design**

- **Description**: Create address structure, then person structure containing address. Show initialization of nested structures, accessing nested members, and passing nested structures to functions.
- **Prerequisites**: LB50, LB53
- **New Concept**: Nested structures

## LB59: **Union Demonstration Lab**

- **Description**: Build examples showing union usage: same memory for different types, size of union, practical uses (variant data), and differences from structures. Create type-tagged union for safety.
- **Prerequisites**: LB49, R15
- **New Concept**: Unions

## LB60: **Enumeration System**

- **Description**: Create enums for: days of week, months, menu options, and status codes. Show enum in switch statements, as array indices, and function parameters. Demonstrate enum vs #define advantages.
- **Prerequisites**: TB11, R14
- **New Concept**: Enumerations

## LB61: **Typedef Applications**

- **Description**: Develop typedef examples for: basic types (typedef int Integer), structures, pointers, function pointers, and complex declarations. Show how typedef improves readability.
- **Prerequisites**: LB50, LB14
- **New Concept**: Type definitions

## LB62: **Structure Copy Operations**

- **Description**: Implement structure copying showing: shallow copy with assignment, deep copy for structures with pointers, member-wise copy function, and common copying pitfalls with pointer members.
- **Prerequisites**: LB53, LB27
- **New Concept**: Structure copying

## LB63: **Structure Comparison Functions**

- **Description**: Create comparison functions for structures: equality check, field-by-field comparison, sorting by different fields, and handling structures with array/pointer members properly.
- **Prerequisites**: LB62, TB61
- **New Concept**: Structure comparison

## LB64: **Dynamic Structure Arrays**

- **Description**: Simulate dynamic array of structures using static array with: count tracking, add/remove operations, resize simulation, and maintaining sorted order. Preview of dynamic allocation concepts.
- **Prerequisites**: LB52, TB69
- **New Concept**: Dynamic structure concepts

## LB65: **Linked Node Preview**

- **Description**: Create self-referential structure (node with pointer to same type). Build simple linked chain of 3-4 nodes statically, traverse the chain, and show concept of linked structures.
- **Prerequisites**: LB53, LB8
- **New Concept**: Self-referential structures

## LB66: **Structure Serialization**

- **Description**: Build functions to convert structures to/from strings for storage: format structure as text, parse text back to structure, handle different field types, and validate parsed data.
- **Prerequisites**: LB44, LB62
- **New Concept**: Serialization

## LB67: **Bit Field Structures**

- **Description**: Create structures with bit fields for: flags storage, device registers simulation, packed data representation. Show memory savings and proper bit field usage.
- **Prerequisites**: LB49, R28
- **New Concept**: Bit fields

## LB68: **Structure Alignment Demo**

- **Description**: Demonstrate structure padding and alignment: show actual vs expected size, reorder members for optimization, use pragma pack, and explain alignment rules for different types.
- **Prerequisites**: LB67, R15
- **New Concept**: Memory alignment

## LB69: **Function Pointer in Structures**

- **Description**: Build structures containing function pointers to create: primitive object-like behavior, operation dispatch tables, and callback mechanisms. Show "methods" in structures.
- **Prerequisites**: LB61, LB14
- **New Concept**: Function members

## LB70: **Complex Number Calculator**

- **Description**: Create complex number structure with real/imaginary parts. Implement: addition, subtraction, multiplication, magnitude calculation, and display in a+bi format using structure-based design.
- **Prerequisites**: LB54, TB39
- **New Concept**: Mathematical structures

## LB71: **Configuration Structure System**

- **Description**: Design program configuration structure with: settings, flags, thresholds. Implement load from string buffer, save to string, validate configuration, and apply defaults.
- **Prerequisites**: LB66, LB60
- **New Concept**: Configuration management

## LB72: **TEST: Banking System with Structures**

- **Description**: Create a complete banking system using structures: account structure with nested address, transaction structure with timestamp, account array management, transaction history (fixed size array), balance calculation from transactions, account search and sorting, interest calculation for savings, monthly statement generation, and comprehensive structure usage.
- **Prerequisites**: LB49-LB71
- **New Concept**: Integration of structure concepts
