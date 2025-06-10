# Stage 10: Strings and Character Handling (Projects 129-152)

**Learning Goal**: Master character arrays and string manipulation

## LB25: **String Initialization Methods**

- **Description**: Create a string laboratory showing 5 ways to initialize strings: char array with size, without size, pointer to literal, character by character, and from user input. Display each with length and memory used.
- **Prerequisites**: TB71, LB13
- **New Concept**: String initialization

## LB26: **Custom strlen Implementation**

- **Description**: Build your own string length function using: array indexing method, pointer arithmetic method, and recursive method. Compare with standard strlen and show character counting process.
- **Prerequisites**: LB25, LB9
- **New Concept**: String length calculation

## LB27: **String Copy Mechanisms**

- **Description**: Implement strcpy alternatives: character-by-character copy, pointer-based copy, copy with size limit (strncpy style), and safe copy that prevents overflow. Show memory states during copy.
- **Prerequisites**: LB26, LB6
- **New Concept**: String copying

## LB28: **String Concatenation Engine**

- **Description**: Create strcat variations that: append strings safely, concatenate with size limits, insert string at position, and join multiple strings with separator. Handle buffer size properly.
- **Prerequisites**: LB27, LB13
- **New Concept**: String concatenation

## LB29: **String Comparison System**

- **Description**: Build strcmp alternatives: case-sensitive comparison, case-insensitive comparison, partial comparison (n characters), and locale-aware comparison concepts. Return proper comparison values.
- **Prerequisites**: LB26, TB61
- **New Concept**: String comparison

## LB30: **Character Classification Suite**

- **Description**: Create character analyzers without ctype.h: isAlpha, isDigit, isSpace, isUpper, isLower, isPunctuation, and isAlphanumeric. Build complete ASCII character classifier.
- **Prerequisites**: R12, TB13
- **New Concept**: Character classification

## LB31: **Case Conversion Tools**

- **Description**: Implement case converters: toUpper, toLower, toggleCase, sentence case, title case, and camelCase converter. Handle non-alphabetic characters properly.
- **Prerequisites**: LB30, LB25
- **New Concept**: Character transformation

## LB32: **String Reversal Workshop**

- **Description**: Build string reversers using: two-pointer approach, recursive method, word-wise reversal (reverse word order), and in-place character reversal. Preserve word boundaries where needed.
- **Prerequisites**: LB7, LB27
- **New Concept**: String reversal algorithms

## LB33: **Substring Search Engine**

- **Description**: Create substring finders implementing: naive search, first occurrence, last occurrence, all occurrences with positions, and case-insensitive search. Show comparison process.
- **Prerequisites**: LB29, TB58
- **New Concept**: Pattern searching

## LB34: **String Tokenizer System**

- **Description**: Build a tokenizer that: splits string by delimiter, handles multiple delimiters, preserves or removes empty tokens, and counts words/tokens. Similar to strtok but safer.
- **Prerequisites**: LB33, LB28
- **New Concept**: String tokenization

## LB35: **Input Validation Framework**

- **Description**: Create validators for: email format (basic), phone number patterns, numeric strings, date formats, and password requirements. Use character classification and pattern matching.
- **Prerequisites**: LB30, TB9
- **New Concept**: String validation

## LB36: **String Buffer Manager**

- **Description**: Develop safe string handlers with: buffer overflow prevention, automatic size tracking, safe append operations, and buffer usage reporting. Implement string buffer structure concept.
- **Prerequisites**: LB28, TB68
- **New Concept**: Buffer management

## LB37: **String Array Handler**

- **Description**: Build a name database using array of strings (2D char array) that can: store multiple strings, sort alphabetically, search for names, and remove duplicates. Handle variable-length strings.
- **Prerequisites**: TB62, LB25
- **New Concept**: String arrays

## LB38: **String Sorting System**

- **Description**: Implement string sorting with: alphabetical sort, length-based sort, reverse alphabetical, and custom comparison functions. Use pointer arrays to avoid moving strings.
- **Prerequisites**: LB37, LB12
- **New Concept**: String sorting

## LB39: **Text Line Processor**

- **Description**: Create a line-based text handler that: counts lines, finds longest/shortest line, removes empty lines, numbers lines, and wraps long lines at word boundaries.
- **Prerequisites**: LB34, LB36
- **New Concept**: Line processing

## LB40: **String Encryption Tool**

- **Description**: Build simple encryption using: Caesar cipher, substitution cipher, XOR encryption, and ROT13. Include both encryption and decryption functions with key management.
- **Prerequisites**: LB31, R28
- **New Concept**: String encryption

## LB41: **Pattern Matching Engine**

- **Description**: Implement pattern matchers for: wildcard (* and ?), character classes [a-z], escaped characters, and simple regular expression concepts. Show match/no-match with positions.
- **Prerequisites**: LB33, LB30
- **New Concept**: Pattern matching

## LB42: **String Memory Utilities**

- **Description**: Create memory functions for strings: custom memcpy, memset, memcmp, and memmove implementations. Show how these work with overlapping memory regions.
- **Prerequisites**: LB17, LB27
- **New Concept**: Memory operations

## LB43: **String Formatting Library**

- **Description**: Build formatters for: padding strings (left/right/center), truncating with ellipsis, formatting numbers as strings, and creating aligned columns of text.
- **Prerequisites**: R4, LB36
- **New Concept**: String formatting

## LB44: **String Parsing Toolkit**

- **Description**: Develop parsers that extract: integers from strings, floating-point values, key-value pairs, and CSV fields. Handle parsing errors and invalid formats gracefully.
- **Prerequisites**: LB34, R23
- **New Concept**: String parsing

## LB45: **Character Frequency Analyzer**

- **Description**: Create frequency analysis tools: character histogram, most/least frequent characters, character distribution visualization, and entropy calculation for strings.
- **Prerequisites**: TB64, LB30
- **New Concept**: Frequency analysis

## LB46: **String Compression Basic**

- **Description**: Implement simple compression: run-length encoding (RLE), character frequency replacement, and basic dictionary compression concepts. Show compression ratios.
- **Prerequisites**: LB45, LB40
- **New Concept**: String compression

## LB47: **Unicode Awareness Demo**

- **Description**: Build UTF-8 awareness demos: detect multi-byte characters, count actual characters vs bytes, handle basic Unicode operations, and show ASCII vs Unicode differences.
- **Prerequisites**: LB30, LB42
- **New Concept**: Character encoding basics

## LB48: **TEST: Text Editor Core**

- **Description**: Create a simple text editor engine with: line-based text storage using string arrays, insert/delete lines, search and replace functionality, word wrap implementation, undo single operation (using backup), line numbering display, text statistics (words/chars/lines), save/load to string buffer (not file), and comprehensive string manipulation.
- **Prerequisites**: LB25-LB47
- **New Concept**: Integration of string concepts
