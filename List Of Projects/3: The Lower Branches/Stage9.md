# Stage 9: Pointers Foundation (Projects 105-128)

**Learning Goal**: Master pointer concepts and basic usage

## LB1: **Pointer Declaration Lab**

- **Description**: Create a pointer exploration program that declares pointers to different types (int, float, char, double), initializes them to address of variables, and displays both addresses and values using & and * operators.
- **Prerequisites**: R9, R15
- **New Concept**: Pointer declaration and initialization

## LB2: **Address Explorer System**

- **Description**: Build an address viewer that shows memory addresses of various variables, arrays, and functions. Display addresses in hexadecimal, compare addresses to understand memory layout, and show address differences.
- **Prerequisites**: LB1, TB55
- **New Concept**: Address operator and memory layout

## LB3: **Dereferencing Demonstrator**

- **Description**: Develop a program that modifies variables through pointers, shows before/after values, demonstrates changing pointer targets, and proves that changes through pointers affect original variables.
- **Prerequisites**: LB1, LB2
- **New Concept**: Pointer dereferencing

## LB4: **Pointer Arithmetic Explorer**

- **Description**: Create an arithmetic demonstrator showing: pointer increment/decrement with different types, adding integers to pointers, subtracting pointers, and relationship between pointer arithmetic and array indexing.
- **Prerequisites**: LB3, TB55
- **New Concept**: Pointer arithmetic

## LB5: **Array-Pointer Relationship**

- **Description**: Build a program proving arrays and pointers relationship: access array elements using pointer notation, use array name as pointer, compare arr[i] with *(arr+i), and show they're equivalent.
- **Prerequisites**: LB4, TB56
- **New Concept**: Arrays as pointers

## LB6: **Function Parameter Pointers**

- **Description**: Create functions that take pointer parameters to: swap two values, modify array elements, return multiple values (via pointer parameters), and demonstrate call-by-reference behavior.
- **Prerequisites**: LB3, TB37
- **New Concept**: Pointers as parameters

## LB7: **Advanced Swap Functions**

- **Description**: Implement generic swap using pointers that works for different types, swap array elements by position, rotate three values, and reverse array using pointer swapping.
- **Prerequisites**: LB6, R13
- **New Concept**: Pointer-based algorithms

## LB8: **Pointer-to-Pointer Demo**

- **Description**: Create a double pointer demonstration showing: declaration of pointer-to-pointer, accessing values through double indirection, modifying pointer targets, and practical use in function parameters.
- **Prerequisites**: LB3, LB6
- **New Concept**: Multiple indirection

## LB9: **Array Traversal with Pointers**

- **Description**: Build array processors using only pointers (no indices) for: sum calculation, finding min/max, searching elements, and counting occurrences. Compare with index-based versions.
- **Prerequisites**: LB5, TB57
- **New Concept**: Pointer-based iteration

## LB10: **Pointer Comparison Operations**

- **Description**: Develop a pointer analyzer that compares pointers for equality, determines which points to higher/lower address, calculates elements between pointers, and validates pointer ranges.
- **Prerequisites**: LB4, LB9
- **New Concept**: Pointer comparison

## LB11: **Null Pointer Handler**

- **Description**: Create a safe pointer system that checks for NULL before operations, demonstrates NULL pointer usage, shows common NULL pointer errors, and implements NULL-safe functions.
- **Prerequisites**: LB3, TB48
- **New Concept**: NULL pointer handling

## LB12: **Pointer Array Manager**

- **Description**: Build a system using array of pointers to: store addresses of different variables, create pointer-based lookup table, sort pointers without moving data, and implement indirection table.
- **Prerequisites**: LB1, TB55
- **New Concept**: Arrays of pointers

## LB13: **String Pointer Operations**

- **Description**: Develop string handlers using char pointers for: string length without strlen, string copy without strcpy, string concatenation, and character search. Show pointer advancement through strings.
- **Prerequisites**: LB9, TB71
- **New Concept**: String pointers

## LB14: **Function Pointer Calculator**

- **Description**: Create a calculator using function pointers where operations are selected via pointer array, user chooses operation by number, and new operations can be easily added.
- **Prerequisites**: TB50, LB12
- **New Concept**: Function pointer arrays

## LB15: **Const Pointer Laboratory**

- **Description**: Build demonstrations of: pointer to const (can't modify data), const pointer (can't change where it points), const pointer to const, and practical uses of each type.
- **Prerequisites**: LB3, R14
- **New Concept**: Const with pointers

## LB16: **Memory Scanner Tool**

- **Description**: Create a memory examiner that displays memory contents byte by byte, shows different interpretations of same memory, demonstrates endianness, and explores structure padding.
- **Prerequisites**: LB4, LB10
- **New Concept**: Memory examination

## LB17: **Generic Data Processor**

- **Description**: Implement generic functions using void pointers that can: swap any type, copy memory blocks, compare memory regions, and search in any array type. Include size parameter for type safety.
- **Prerequisites**: LB8, LB7
- **New Concept**: Void pointers

## LB18: **Pointer Validation Suite**

- **Description**: Build pointer validators that check: if pointer is within array bounds, if two pointers point to same array, if pointer has been initialized, and demonstrate defensive pointer programming.
- **Prerequisites**: LB11, TB68
- **New Concept**: Pointer validation

## LB19: **Dynamic Array Preview**

- **Description**: Create a preview of dynamic arrays using fixed storage but pointer access, simulating malloc/free behavior, showing how pointers enable dynamic structures, and implementing growth strategy.
- **Prerequisites**: LB9, TB69
- **New Concept**: Dynamic concepts preview

## LB20: **Pointer Performance Tester**

- **Description**: Develop benchmarks comparing: array index vs pointer access speed, function calls vs function pointers, direct vs indirect access, showing when pointers improve performance.
- **Prerequisites**: LB9, LB14
- **New Concept**: Performance analysis

## LB21: **Command Line Argument Processor**

- **Description**: Build a program that processes argc/argv to: display all arguments, parse numeric arguments, implement command flags, and create simple command-line calculator.
- **Prerequisites**: LB12, LB13
- **New Concept**: main() parameters

## LB22: **Pointer Casting Workshop**

- **Description**: Create safe casting demonstrations: casting between numeric types, type punning examples, alignment considerations, and when casting is appropriate vs dangerous.
- **Prerequisites**: LB17, R11
- **New Concept**: Pointer type casting

## LB23: **Complex Expression Parser**

- **Description**: Build expression evaluator using pointers for: parsing numeric expressions, handling operator precedence, implementing recursive evaluation, and showing pointer-based parsing.
- **Prerequisites**: LB13, TB49
- **New Concept**: Pointer-based parsing

## LB24: **TEST: Pointer-Based Database**

- **Description**: Create a mini database system using pointers: array of pointers to "records", sort records without moving data, search using pointer comparison, implement primitive indexing, handle NULL entries properly, use function pointers for comparisons, demonstrate memory efficiency, and include comprehensive error checking.
- **Prerequisites**: LB1-LB23
- **New Concept**: Integration of pointer concepts
