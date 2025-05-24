# The Maplewood Tree: A Complete C Programming Curriculum

## Overview
A 12-18 month intensive journey from C basics to systems mastery, structured as a dependency tree where each level must be completed before ascending. Total: 350+ projects, ~3000-4000 hours.

---

## 🌱 ROOTS: Foundation Projects (50 Projects, 50-200 hours total)

### Root Cluster 1: Basic Syntax & Control (Projects R1-R10)
**R1. Hello Variations** (1hr)
- Print patterns, ASCII art, formatted output
- Concepts: printf, escape sequences, basic I/O

**R2. Number Guesser** (2hr)
- Random number generation, input validation
- Concepts: rand(), conditionals, loops

**R3. Temperature Converter Network** (2hr)
- Convert between C/F/K with menu system
- Concepts: Functions, switch statements

**R4. Calculator Evolution** (3hr)
- Basic → Scientific → RPN calculator
- Prerequisites: R1-R3
- Concepts: Function pointers, stack operations

**R5. Text Statistics Engine** (2hr)
- Count words, chars, lines, frequencies
- Concepts: File I/O, character arrays

**R6. Caesar Cipher Tool** (3hr)
- Encrypt/decrypt with variable shift
- Prerequisites: R5
- Concepts: ASCII manipulation, modular arithmetic

**R7. Tic-Tac-Toe** (4hr)
- 2-player console game with win detection
- Prerequisites: R2, R3
- Concepts: 2D arrays, game state

**R8. Prime Number Harvester** (2hr)
- Find primes up to N using multiple algorithms
- Concepts: Algorithm optimization, timing

**R9. Base Converter** (3hr)
- Convert between base 2-36
- Prerequisites: R4
- Concepts: Number systems, string manipulation

**R10. Multiplication Table Generator** (1hr)
- Dynamic sizing, formatted output
- Checkpoint: Must complete R1-R10 before proceeding

### Root Cluster 2: Pointers & Memory Basics (R11-R20)
**R11. Pointer Playground** (2hr)
- Interactive pointer visualization
- Concepts: Pointer arithmetic, dereferencing

**R12. Array Reverser Collection** (3hr)
- In-place reversal using different techniques
- Prerequisites: R11
- Concepts: Pointer manipulation

**R13. String Library Mini** (4hr)
- Implement strlen, strcpy, strcat from scratch
- Prerequisites: R11, R12
- Concepts: Null termination, buffer management

**R14. Dynamic Array Builder** (3hr)
- Growable array with add/remove
- Prerequisites: R13
- Concepts: malloc, free, realloc

**R15. Memory Leak Detector** (4hr)
- Track allocations/frees, report leaks
- Prerequisites: R14
- Concepts: Memory debugging basics

**R16. Matrix Operations** (3hr)
- Add, multiply, transpose with dynamic allocation
- Prerequisites: R14, R15
- Concepts: 2D dynamic arrays

**R17. Swap Collection** (2hr)
- Swap any type using void pointers
- Prerequisites: R11-R15
- Concepts: Generic programming in C

**R18. Function Pointer Calculator** (3hr)
- Calculator using function pointer arrays
- Prerequisites: R4, R17
- Concepts: Function pointers

**R19. Callback Timer** (2hr)
- Execute functions after delay
- Prerequisites: R18
- Concepts: Time functions, callbacks

**R20. Memory Pool Allocator** (4hr)
- Pre-allocated memory management
- Prerequisites: R15, R16
- Checkpoint: Memory fundamentals mastery

### Root Cluster 3: Structures & File I/O (R21-R30)
**R21. Student Database** (3hr)
- CRUD operations with structs
- Prerequisites: R20
- Concepts: Structures, typedef

**R22. Contact Book** (4hr)
- File-backed contact storage
- Prerequisites: R21, R5
- Concepts: Binary file I/O

**R23. Configuration Parser** (3hr)
- Read key=value config files
- Prerequisites: R22
- Concepts: String parsing, file formats

**R24. CSV Processor** (4hr)
- Read, modify, write CSV files
- Prerequisites: R23
- Concepts: Structured data handling

**R25. Inventory System** (4hr)
- Products with categories, search
- Prerequisites: R24
- Concepts: Nested structures

**R26. Bitmap Reader** (3hr)
- Parse BMP headers, display info
- Prerequisites: R22
- Concepts: Binary formats, packing

**R27. Log File Analyzer** (3hr)
- Parse and summarize log patterns
- Prerequisites: R23, R24
- Concepts: Pattern matching

**R28. Serialization Framework** (4hr)
- Save/load complex structs
- Prerequisites: R25, R26
- Concepts: Data persistence

**R29. File Comparer** (2hr)
- Binary diff tool
- Prerequisites: R26
- Concepts: File comparison algorithms

**R30. Archive Format** (4hr)
- Simple file container format
- Prerequisites: R28, R29
- Checkpoint: File I/O mastery

### Root Cluster 4: Algorithms & Bit Operations (R31-R40)
**R31. Sorting Visualizer** (4hr)
- Animate bubble, insertion, selection sort
- Prerequisites: R16, R30
- Concepts: Sorting algorithms

**R32. Binary Search Variations** (3hr)
- Implement 5 search algorithms
- Prerequisites: R31
- Concepts: Search complexity

**R33. Bit Flag Manager** (2hr)
- Set, clear, toggle, check bits
- Concepts: Bitwise operations

**R34. Hamming Distance Calculator** (2hr)
- Count bit differences
- Prerequisites: R33
- Concepts: Bit manipulation

**R35. Checksum Generator** (3hr)
- Multiple checksum algorithms
- Prerequisites: R34
- Concepts: Error detection

**R36. Run-Length Encoder** (3hr)
- Basic compression algorithm
- Prerequisites: R35
- Concepts: Compression basics

**R37. Maze Generator** (4hr)
- Create solvable mazes
- Prerequisites: R32
- Concepts: Recursive algorithms

**R38. Pathfinder** (4hr)
- Find shortest path in grid
- Prerequisites: R37
- Concepts: Graph traversal basics

**R39. Expression Evaluator** (4hr)
- Parse and evaluate math expressions
- Prerequisites: R32, R18
- Concepts: Parsing, precedence

**R40. Pattern Matcher** (4hr)
- Simple regex-like matching
- Prerequisites: R39
- Checkpoint: Algorithm fundamentals

### Root Cluster 5: System Interaction (R41-R50)
**R41. Process Monitor** (3hr)
- Show running processes
- Prerequisites: R40
- Concepts: System calls

**R42. Environment Manager** (2hr)
- Get/set environment variables
- Prerequisites: R41
- Concepts: Process environment

**R43. Signal Handler** (3hr)
- Graceful shutdown on Ctrl+C
- Prerequisites: R42
- Concepts: Signal handling

**R44. Pipe Communicator** (4hr)
- IPC using pipes
- Prerequisites: R43
- Concepts: Inter-process communication

**R45. Directory Walker** (3hr)
- Recursive directory traversal
- Prerequisites: R30, R41
- Concepts: File system navigation

**R46. File Watcher** (4hr)
- Monitor file changes
- Prerequisites: R45
- Concepts: File system events

**R47. Command Launcher** (3hr)
- Execute external commands
- Prerequisites: R44
- Concepts: Process creation

**R48. Time Tracker** (2hr)
- Measure execution time
- Prerequisites: R19
- Concepts: High-resolution timing

**R49. Resource Monitor** (4hr)
- Track memory/CPU usage
- Prerequisites: R41, R48
- Concepts: System resource APIs

**R50. Mini Shell** (4hr)
- Basic command interpreter
- Prerequisites: R47, R49
- Final Checkpoint: Ready for BASE

---

## 🌲 BASE: Core Engineering Skills (100 Projects, 400-800 hours)

### Base Layer 1: Data Structures From Scratch (B1-B25)

**B1. Dynamic Array v2** (4hr)
- Generic, type-safe implementation
- Prerequisites: R14, R17
- Concepts: Macro magic, type safety

**B2. Linked List Suite** (6hr)
- Single, double, circular variants
- Prerequisites: B1
- Concepts: Node-based structures

**B3. Stack Library** (4hr)
- Array and linked implementations
- Prerequisites: B2
- Concepts: LIFO operations

**B4. Queue Collection** (5hr)
- Regular, circular, priority queues
- Prerequisites: B3
- Concepts: FIFO, heap basics

**B5. Binary Search Tree** (8hr)
- Insert, delete, balance checking
- Prerequisites: B2, R32
- Concepts: Tree traversal

**B6. AVL Tree** (8hr)
- Self-balancing BST
- Prerequisites: B5
- Concepts: Tree rotations

**B7. Red-Black Tree** (8hr)
- Another balancing approach
- Prerequisites: B6
- Concepts: Tree coloring rules

**B8. Hash Table** (8hr)
- Chaining and open addressing
- Prerequisites: B2, R35
- Concepts: Hashing, collision resolution

**B9. Heap Implementation** (6hr)
- Min/max heaps, heapify
- Prerequisites: B4
- Concepts: Heap property

**B10. Graph Library** (8hr)
- Adjacency list/matrix representations
- Prerequisites: B2, B8
- Concepts: Graph theory basics

**B11. Trie Structure** (6hr)
- Prefix tree for strings
- Prerequisites: B5
- Concepts: String storage optimization

**B12. B-Tree** (8hr)
- Disk-friendly tree structure
- Prerequisites: B7
- Concepts: Multi-way trees

**B13. Skip List** (6hr)
- Probabilistic data structure
- Prerequisites: B2, R8
- Concepts: Randomized algorithms

**B14. Bloom Filter** (5hr)
- Probabilistic membership test
- Prerequisites: B8, R35
- Concepts: Space-efficient sets

**B15. LRU Cache** (6hr)
- Least recently used eviction
- Prerequisites: B8, B2
- Concepts: Cache algorithms

**B16. Union-Find** (5hr)
- Disjoint set structure
- Prerequisites: B10
- Concepts: Set operations

**B17. Segment Tree** (7hr)
- Range query structure
- Prerequisites: B5
- Concepts: Interval queries

**B18. Fenwick Tree** (6hr)
- Binary indexed tree
- Prerequisites: B17
- Concepts: Prefix sums

**B19. Circular Buffer** (4hr)
- Fixed-size queue
- Prerequisites: B4
- Concepts: Ring buffers

**B20. Memory Arena** (6hr)
- Region-based allocation
- Prerequisites: R20, B19
- Concepts: Bulk memory management

**B21. Object Pool** (5hr)
- Reusable object allocation
- Prerequisites: B20
- Concepts: Object lifecycle

**B22. String Builder** (5hr)
- Efficient string concatenation
- Prerequisites: B1, R13
- Concepts: Buffer management

**B23. Rope Structure** (7hr)
- Efficient string editing
- Prerequisites: B5, B22
- Concepts: Tree of strings

**B24. Persistent Array** (8hr)
- Immutable with history
- Prerequisites: B5, B20
- Concepts: Structural sharing

**B25. Lock-Free Queue** (8hr)
- Thread-safe without locks
- Prerequisites: B4, R33
- Checkpoint: Data structures mastery

### Base Layer 2: Algorithm Implementation (B26-B50)

**B26. QuickSort Suite** (6hr)
- Multiple pivot strategies
- Prerequisites: R31, B3
- Concepts: Divide and conquer

**B27. MergeSort Variants** (6hr)
- In-place, external, parallel-ready
- Prerequisites: B26
- Concepts: Stable sorting

**B28. HeapSort** (4hr)
- Using your heap implementation
- Prerequisites: B9
- Concepts: Heap-based sorting

**B29. RadixSort** (5hr)
- Non-comparison sorting
- Prerequisites: B27, R33
- Concepts: Linear time sorting

**B30. String Search Algorithms** (8hr)
- KMP, Boyer-Moore, Rabin-Karp
- Prerequisites: R40, B11
- Concepts: Pattern matching optimization

**B31. Graph Traversal Suite** (8hr)
- DFS, BFS, topological sort
- Prerequisites: B10, B3
- Concepts: Graph exploration

**B32. Shortest Path Collection** (8hr)
- Dijkstra, Bellman-Ford, Floyd-Warshall
- Prerequisites: B31, B9
- Concepts: Path optimization

**B33. Minimum Spanning Tree** (6hr)
- Kruskal's and Prim's algorithms
- Prerequisites: B32, B16
- Concepts: Graph connectivity

**B34. Dynamic Programming Kit** (8hr)
- Classic DP problems
- Prerequisites: B17
- Concepts: Optimal substructure

**B35. Backtracking Framework** (7hr)
- N-Queens, Sudoku solver
- Prerequisites: B34
- Concepts: Exhaustive search

**B36. Greedy Algorithm Set** (6hr)
- Activity selection, Huffman coding
- Prerequisites: B9, B35
- Concepts: Local optimization

**B37. Matrix Algorithm Library** (7hr)
- Multiplication, inversion, decomposition
- Prerequisites: R16, B34
- Concepts: Numerical methods

**B38. FFT Implementation** (8hr)
- Fast Fourier Transform
- Prerequisites: B37
- Concepts: Signal processing

**B39. Convex Hull** (6hr)
- Multiple algorithms
- Prerequisites: B31
- Concepts: Computational geometry

**B40. Line Intersection** (5hr)
- Segment intersection detection
- Prerequisites: B39
- Concepts: Geometric algorithms

**B41. Voronoi Diagram** (8hr)
- Fortune's algorithm
- Prerequisites: B40, B9
- Concepts: Space partitioning

**B42. A* Pathfinding** (7hr)
- Heuristic search
- Prerequisites: B32, B9
- Concepts: Informed search

**B43. Genetic Algorithm** (7hr)
- Optimization framework
- Prerequisites: R8, B36
- Concepts: Evolutionary computation

**B44. Simulated Annealing** (6hr)
- Probabilistic optimization
- Prerequisites: B43
- Concepts: Metaheuristics

**B45. K-Means Clustering** (6hr)
- Unsupervised learning basics
- Prerequisites: B37
- Concepts: Clustering

**B46. Decision Tree** (7hr)
- Basic classifier
- Prerequisites: B5, B45
- Concepts: Machine learning basics

**B47. Neural Network** (8hr)
- Simple feedforward network
- Prerequisites: B37, B46
- Concepts: Backpropagation

**B48. Compression Suite** (8hr)
- Huffman, LZ77, LZ78
- Prerequisites: B36, B8
- Concepts: Data compression

**B49. Cryptography Basics** (8hr)
- XOR cipher, DES, RSA basics
- Prerequisites: R35, B37
- Concepts: Encryption principles

**B50. Error Correction** (7hr)
- Hamming codes, Reed-Solomon basics
- Prerequisites: B49, R34
- Checkpoint: Algorithm implementation complete

### Base Layer 3: System Programming (B51-B75)

**B51. Thread Pool** (8hr)
- Work queue with multiple threads
- Prerequisites: B25, R44
- Concepts: Concurrency basics

**B52. Mutex Implementation** (7hr)
- Build mutex from atomics
- Prerequisites: B51, R33
- Concepts: Synchronization primitives

**B53. Condition Variable** (6hr)
- Thread coordination
- Prerequisites: B52
- Concepts: Thread signaling

**B54. Read-Write Lock** (6hr)
- Multiple readers, single writer
- Prerequisites: B53
- Concepts: Lock optimization

**B55. Memory Mapped Files** (6hr)
- Efficient file access
- Prerequisites: R46, B20
- Concepts: Virtual memory

**B56. Shared Memory IPC** (7hr)
- Process communication via memory
- Prerequisites: B55, R44
- Concepts: Shared memory

**B57. Message Queue** (7hr)
- IPC message passing
- Prerequisites: B56, B4
- Concepts: Message passing

**B58. Socket Library** (8hr)
- TCP/UDP client/server
- Prerequisites: B57
- Concepts: Network programming

**B59. HTTP Parser** (8hr)
- Parse HTTP requests/responses
- Prerequisites: B58, R23
- Concepts: Protocol parsing

**B60. JSON Parser** (7hr)
- Full JSON support
- Prerequisites: B59, B8
- Concepts: Recursive descent parsing

**B61. XML Parser** (8hr)
- SAX-style parser
- Prerequisites: B60
- Concepts: Streaming parsing

**B62. Protocol Buffer Clone** (8hr)
- Binary serialization format
- Prerequisites: B61, R28
- Concepts: Schema-based serialization

**B63. Event Loop** (8hr)
- Single-threaded async I/O
- Prerequisites: B58, B4
- Concepts: Event-driven programming

**B64. Timer Wheel** (6hr)
- Efficient timer management
- Prerequisites: B63, B19
- Concepts: Time-based scheduling

**B65. Logger Framework** (7hr)
- Levels, rotation, async writing
- Prerequisites: B51, B19
- Concepts: Diagnostic output

**B66. Configuration System** (6hr)
- Hierarchical config with hot reload
- Prerequisites: R23, B8
- Concepts: Application configuration

**B67. Plugin System** (8hr)
- Dynamic library loading
- Prerequisites: B66, R47
- Concepts: Dynamic linking

**B68. Memory Debugger** (8hr)
- Detect leaks, corruption
- Prerequisites: R15, B65
- Concepts: Memory safety

**B69. Profiler** (8hr)
- Function timing, call graphs
- Prerequisites: B68, R48
- Concepts: Performance analysis

**B70. Coverage Tool** (7hr)
- Track code execution
- Prerequisites: B69
- Concepts: Code coverage

**B71. Unit Test Framework** (7hr)
- Assertions, fixtures, runners
- Prerequisites: B70
- Concepts: Testing methodology

**B72. Benchmark Suite** (6hr)
- Micro-benchmarking tools
- Prerequisites: B71, R48
- Concepts: Performance testing

**B73. Sanitizer Clone** (8hr)
- Detect undefined behavior
- Prerequisites: B68
- Concepts: Runtime checking

**B74. Static Analyzer** (8hr)
- Basic code analysis
- Prerequisites: B73, R39
- Concepts: Static analysis

**B75. Build System** (8hr)
- Dependency tracking, incremental builds
- Prerequisites: B74, B10
- Checkpoint: System programming complete

### Base Layer 4: Architecture & Design (B76-B100)

**B76. Entity Component System** (8hr)
- Game architecture pattern
- Prerequisites: B8, B15
- Concepts: Data-oriented design

**B77. Model-View-Controller** (7hr)
- Classic GUI pattern
- Prerequisites: B76
- Concepts: Separation of concerns

**B78. Observer Pattern** (5hr)
- Event notification system
- Prerequisites: B77, B2
- Concepts: Loose coupling

**B79. Command Pattern** (5hr)
- Undo/redo system
- Prerequisites: B78, B3
- Concepts: Encapsulating requests

**B80. State Machine** (6hr)
- FSM framework
- Prerequisites: B79, B8
- Concepts: State management

**B81. Actor Model** (8hr)
- Message-based concurrency
- Prerequisites: B80, B57
- Concepts: Actor systems

**B82. Pipeline Architecture** (7hr)
- Data processing pipeline
- Prerequisites: B81, B51
- Concepts: Stream processing

**B83. Microkernel Pattern** (8hr)
- Core + plugins architecture
- Prerequisites: B67, B82
- Concepts: Extensible systems

**B84. Layered Architecture** (6hr)
- Clean layer separation
- Prerequisites: B83
- Concepts: Architectural layers

**B85. Repository Pattern** (6hr)
- Data access abstraction
- Prerequisites: B84, B15
- Concepts: Data access patterns

**B86. Service Locator** (5hr)
- Service discovery pattern
- Prerequisites: B85
- Concepts: Dependency injection

**B87. Factory Pattern Suite** (6hr)
- Object creation patterns
- Prerequisites: B86
- Concepts: Creational patterns

**B88. Proxy Pattern** (6hr)
- Remote/virtual/protection proxies
- Prerequisites: B87
- Concepts: Structural patterns

**B89. Decorator Pattern** (5hr)
- Dynamic behavior addition
- Prerequisites: B88
- Concepts: Composition over inheritance

**B90. Strategy Pattern** (5hr)
- Algorithm selection
- Prerequisites: B89, R18
- Concepts: Behavioral patterns

**B91. Template Method** (5hr)
- Algorithm skeleton
- Prerequisites: B90
- Concepts: Inheritance-based patterns

**B92. Visitor Pattern** (6hr)
- Double dispatch
- Prerequisites: B91
- Concepts: Advanced polymorphism

**B93. Interpreter Pattern** (7hr)
- Mini-language implementation
- Prerequisites: B92, R39
- Concepts: Language design

**B94. Memento Pattern** (5hr)
- State snapshots
- Prerequisites: B93, B79
- Concepts: State preservation

**B95. Chain of Responsibility** (5hr)
- Request handling chain
- Prerequisites: B94, B2
- Concepts: Decoupling handlers

**B96. Mediator Pattern** (6hr)
- Component communication hub
- Prerequisites: B95
- Concepts: Reducing dependencies

**B97. Flyweight Pattern** (6hr)
- Shared object optimization
- Prerequisites: B96, B8
- Concepts: Memory optimization

**B98. Bridge Pattern** (6hr)
- Implementation abstraction
- Prerequisites: B97
- Concepts: Decoupling abstraction

**B99. Composite Pattern** (6hr)
- Tree structures
- Prerequisites: B98, B5
- Concepts: Recursive composition

**B100. Architecture Documentation** (8hr)
- Document your patterns
- Prerequisites: All Base projects
- Final Checkpoint: Ready for BRANCHES

---

## 🌿 BRANCHES: Domain Specialization (200+ Projects)

### Lower Branches (50 Projects, 50-100 hours)

**LB1-10: CLI Tools**
- LB1. **ls Clone** (1 day) - Prerequisites: R45, B65
- LB2. **grep Clone** (1 day) - Prerequisites: B30
- LB3. **find Clone** (2 days) - Prerequisites: LB1, B31
- LB4. **sed Mini** (2 days) - Prerequisites: LB2, B93
- LB5. **awk Mini** (2 days) - Prerequisites: LB4
- LB6. **tar Clone** (2 days) - Prerequisites: B19, R30
- LB7. **diff Tool** (2 days) - Prerequisites: B34
- LB8. **hexdump Clone** (1 day) - Prerequisites: R26
- LB9. **tree Command** (1 day) - Prerequisites: LB1, B31
- LB10. **watch Command** (1 day) - Prerequisites: B64

**LB11-20: Terminal Games**
- LB11. **Snake** (1 day) - Prerequisites: R7, B19
- LB12. **Tetris** (2 days) - Prerequisites: LB11, B80
- LB13. **Roguelike Basics** (2 days) - Prerequisites: B76, B42
- LB14. **Conway's Game of Life** (1 day) - Prerequisites: B37
- LB15. **Minesweeper** (1 day) - Prerequisites: LB14
- LB16. **2048** (1 day) - Prerequisites: B34
- LB17. **Breakout** (2 days) - Prerequisites: LB11
- LB18. **Space Invaders** (2 days) - Prerequisites: LB17
- LB19. **Pac-Man Clone** (2 days) - Prerequisites: B42, LB18
- LB20. **Chess Engine** (2 days) - Prerequisites: B35, B46

**LB21-30: Network Tools**
- LB21. **ping Clone** (1 day) - Prerequisites: B58
- LB22. **traceroute Clone** (2 days) - Prerequisites: LB21
- LB23. **netcat Clone** (2 days) - Prerequisites: B58
- LB24. **Port Scanner** (1 day) - Prerequisites: LB23
- LB25. **Packet Sniffer** (2 days) - Prerequisites: LB24
- LB26. **DNS Resolver** (2 days) - Prerequisites: B59
- LB27. **DHCP Client** (2 days) - Prerequisites: LB26
- LB28. **FTP Client** (2 days) - Prerequisites: B58
- LB29. **IRC Client** (2 days) - Prerequisites: LB28
- LB30. **Bandwidth Monitor** (1 day) - Prerequisites: LB25

**LB31-40: File Tools**
- LB31. **File Encryptor** (1 day) - Prerequisites: B49
- LB32. **File Splitter** (1 day) - Prerequisites: R30
- LB33. **Duplicate Finder** (1 day) - Prerequisites: B8, R35
- LB34. **File Synchronizer** (2 days) - Prerequisites: LB33
- LB35. **Backup Tool** (2 days) - Prerequisites: LB34
- LB36. **File Carver** (2 days) - Prerequisites: R26
- LB37. **Metadata Extractor** (1 day) - Prerequisites: LB36
- LB38. **File Type Detector** (1 day) - Prerequisites: LB37
- LB39. **Secure Delete** (1 day) - Prerequisites: LB31
- LB40. **File System Walker** (1 day) - Prerequisites: R45

**LB41-50: System Tools**
- LB41. **Process Tree** (1 day) - Prerequisites: R41
- LB42. **Memory Map Viewer** (1 day) - Prerequisites: B55
- LB43. **CPU Monitor** (1 day) - Prerequisites: R49
- LB44. **Disk Usage Analyzer** (1 day) - Prerequisites: LB40
- LB45. **System Info Tool** (1 day) - Prerequisites: LB43
- LB46. **Service Manager** (2 days) - Prerequisites: R47
- LB47. **Log Rotator** (1 day) - Prerequisites: B65
- LB48. **Cron Clone** (2 days) - Prerequisites: B64
- LB49. **Init System Mini** (2 days) - Prerequisites: LB46
- LB50. **Container Runtime Basics** (2 days) - Prerequisites: B56

### Middle Branches (80 Projects, 240-560 hours)

**MB1-10: Graphics & Rendering**
- MB1. **Software Rasterizer** (5 days) - Prerequisites: B37, B39
- MB2. **Ray Tracer** (7 days) - Prerequisites: MB1
- MB3. **Particle System** (3 days) - Prerequisites: MB1
- MB4. **2D Physics Engine** (5 days) - Prerequisites: MB3, B37
- MB5. **Sprite Editor** (4 days) - Prerequisites: MB1
- MB6. **Vector Graphics Renderer** (5 days) - Prerequisites: MB5
- MB7. **Font Renderer** (4 days) - Prerequisites: MB6
- MB8. **Image Filters** (3 days) - Prerequisites: MB1
- MB9. **Fractal Generator** (3 days) - Prerequisites: B38
- MB10. **3D Model Loader** (4 days) - Prerequisites: MB2

**MB11-20: Audio Processing**
- MB11. **WAV Player** (3 days) - Prerequisites: R26, B19
- MB12. **Audio Mixer** (5 days) - Prerequisites: MB11
- MB13. **FFT Spectrum Analyzer** (4 days) - Prerequisites: B38, MB11
- MB14. **Audio Effects** (5 days) - Prerequisites: MB13
- MB15. **MIDI Parser** (3 days) - Prerequisites: B60
- MB16. **Synthesizer** (6 days) - Prerequisites: MB15, MB14
- MB17. **Audio Recorder** (3 days) - Prerequisites: MB11
- MB18. **Audio Compressor** (4 days) - Prerequisites: MB14
- MB19. **Beat Detector** (4 days) - Prerequisites: MB13
- MB20. **Audio Format Converter** (3 days) - Prerequisites: MB11

**MB21-30: Database Engines**
- MB21. **B-Tree Storage** (5 days) - Prerequisites: B12
- MB22. **Query Parser** (5 days) - Prerequisites: B93
- MB23. **Transaction Manager** (6 days) - Prerequisites: MB21
- MB24. **Index Manager** (4 days) - Prerequisites: MB22
- MB25. **Buffer Pool** (4 days) - Prerequisites: B15, MB21
- MB26. **Lock Manager** (5 days) - Prerequisites: B54, MB23
- MB27. **Recovery Manager** (5 days) - Prerequisites: MB26
- MB28. **Query Optimizer** (6 days) - Prerequisites: MB24
- MB29. **Replication System** (5 days) - Prerequisites: MB27
- MB30. **Storage Compaction** (4 days) - Prerequisites: MB29

**MB31-40: Embedded Systems (Raspberry Pi)**
- MB31. **GPIO Library** (3 days) - Prerequisites: R41
- MB32. **I2C Driver** (4 days) - Prerequisites: MB31
- MB33. **SPI Driver** (4 days) - Prerequisites: MB32
- MB34. **PWM Controller** (3 days) - Prerequisites: MB31
- MB35. **Sensor Hub** (5 days) - Prerequisites: MB32, MB33
- MB36. **Motor Controller** (4 days) - Prerequisites: MB34
- MB37. **Display Driver** (5 days) - Prerequisites: MB33
- MB38. **Real-Time Scheduler** (5 days) - Prerequisites: B64, MB31
- MB39. **Bootloader** (6 days) - Prerequisites: MB38
- MB40. **Bare Metal OS** (7 days) - Prerequisites: MB39

**MB41-50: Compilers & Interpreters**
- MB41. **Lexer Generator** (4 days) - Prerequisites: B30, B80
- MB42. **Parser Generator** (6 days) - Prerequisites: MB41
- MB43. **AST Builder** (4 days) - Prerequisites: MB42
- MB44. **Type Checker** (5 days) - Prerequisites: MB43
- MB45. **Code Generator** (6 days) - Prerequisites: MB44
- MB46. **Optimizer** (6 days) - Prerequisites: MB45
- MB47. **Register Allocator** (5 days) - Prerequisites: MB46
- MB48. **Bytecode VM** (5 days) - Prerequisites: MB45
- MB49. **JIT Compiler** (7 days) - Prerequisites: MB48
- MB50. **Debugger Backend** (5 days) - Prerequisites: MB49

**MB51-60: Security Tools**
- MB51. **Password Manager** (4 days) - Prerequisites: B49
- MB52. **Firewall** (5 days) - Prerequisites: LB25
- MB53. **Intrusion Detector** (6 days) - Prerequisites: MB52
- MB54. **Virus Scanner** (5 days) - Prerequisites: B30, MB53
- MB55. **Sandbox** (6 days) - Prerequisites: B56
- MB56. **Fuzzer** (4 days) - Prerequisites: B43
- MB57. **Binary Analyzer** (5 days) - Prerequisites: MB56
- MB58. **Exploit Mitigations** (5 days) - Prerequisites: MB57
- MB59. **Secure Allocator** (4 days) - Prerequisites: B68
- MB60. **TPM Interface** (5 days) - Prerequisites: MB51

**MB61-70: Game Engine Components**
- MB61. **Entity Manager** (4 days) - Prerequisites: B76
- MB62. **Physics Integration** (5 days) - Prerequisites: MB4, MB61
- MB63. **Animation System** (5 days) - Prerequisites: MB62
- MB64. **Scene Graph** (4 days) - Prerequisites: MB63, B5
- MB65. **Resource Manager** (4 days) - Prerequisites: MB64, B15
- MB66. **Script Binding** (5 days) - Prerequisites: MB65
- MB67. **UI System** (5 days) - Prerequisites: MB66
- MB68. **Audio Manager** (4 days) - Prerequisites: MB12, MB67
- MB69. **Network Layer** (5 days) - Prerequisites: MB68
- MB70. **Save System** (3 days) - Prerequisites: MB69

**MB71-80: Development Tools**
- MB71. **Code Formatter** (4 days) - Prerequisites: B74
- MB72. **Linter** (5 days) - Prerequisites: MB71
- MB73. **Refactoring Tool** (6 days) - Prerequisites: MB72
- MB74. **Documentation Generator** (4 days) - Prerequisites: MB73
- MB75. **Dependency Analyzer** (4 days) - Prerequisites: B10, MB74
- MB76. **Build Cache** (4 days) - Prerequisites: B75
- MB77. **Test Runner** (4 days) - Prerequisites: B71
- MB78. **Profile Visualizer** (5 days) - Prerequisites: B69
- MB79. **Memory Profiler** (5 days) - Prerequisites: MB78
- MB80. **Distributed Builder** (6 days) - Prerequisites: MB76

### Upper Branches (60 Projects, 420-1260 hours)

**UB1-10: Operating System Components**
- UB1. **Bootloader x86** (2 weeks) - Prerequisites: MB39
- UB2. **Memory Manager** (2 weeks) - Prerequisites: UB1, B20
- UB3. **Process Scheduler** (2 weeks) - Prerequisites: UB2
- UB4. **File System** (3 weeks) - Prerequisites: UB3, MB21
- UB5. **Device Drivers** (2 weeks) - Prerequisites: UB4
- UB6. **Network Stack** (3 weeks) - Prerequisites: UB5, B58
- UB7. **System Calls** (2 weeks) - Prerequisites: UB6
- UB8. **Virtual Memory** (2 weeks) - Prerequisites: UB2
- UB9. **IPC Mechanisms** (2 weeks) - Prerequisites: UB7
- UB10. **Security Layer** (2 weeks) - Prerequisites: UB9

**UB11-20: Language Implementation**
- UB11. **C Compiler** (3 weeks) - Prerequisites: MB50
- UB12. **Assembler** (2 weeks) - Prerequisites: UB11
- UB13. **Linker** (2 weeks) - Prerequisites: UB12
- UB14. **Debugger** (2 weeks) - Prerequisites: UB13
- UB15. **Lisp Interpreter** (2 weeks) - Prerequisites: MB48
- UB16. **Forth System** (2 weeks) - Prerequisites: UB15
- UB17. **Prolog Engine** (3 weeks) - Prerequisites: UB16
- UB18. **JavaScript Engine** (3 weeks) - Prerequisites: MB49
- UB19. **Python Subset** (3 weeks) - Prerequisites: UB18
- UB20. **SQL Engine** (3 weeks) - Prerequisites: MB30

**UB21-30: Emulators**
- UB21. **6502 Emulator** (2 weeks) - Prerequisites: MB48
- UB22. **Z80 Emulator** (2 weeks) - Prerequisites: UB21
- UB23. **GameBoy Emulator** (3 weeks) - Prerequisites: UB22, MB10
- UB24. **NES Emulator** (3 weeks) - Prerequisites: UB23
- UB25. **SNES Emulator** (3 weeks) - Prerequisites: UB24
- UB26. **x86 Emulator** (3 weeks) - Prerequisites: UB25
- UB27. **ARM Emulator** (3 weeks) - Prerequisites: UB26
- UB28. **PS1 Emulator** (3 weeks) - Prerequisites: UB27
- UB29. **Virtual Machine Monitor** (3 weeks) - Prerequisites: UB28
- UB30. **Hardware Simulator** (2 weeks) - Prerequisites: UB29

**UB31-40: Advanced Tools**
- UB31. **Git Clone** (3 weeks) - Prerequisites: B8, MB30
- UB32. **Text Editor (vi-like)** (3 weeks) - Prerequisites: B23, MB67
- UB33. **Shell** (2 weeks) - Prerequisites: R50, UB7
- UB34. **Make Clone** (2 weeks) - Prerequisites: B75
- UB35. **GDB Clone** (3 weeks) - Prerequisites: UB14
- UB36. **Valgrind Clone** (3 weeks) - Prerequisites: MB79
- UB37. **strace Clone** (2 weeks) - Prerequisites: UB7
- UB38. **Package Manager** (2 weeks) - Prerequisites: UB34
- UB39. **Container Runtime** (3 weeks) - Prerequisites: LB50, UB9
- UB40. **Orchestrator** (3 weeks) - Prerequisites: UB39

**UB41-50: Network Services**
- UB41. **Web Server** (2 weeks) - Prerequisites: B59, B63
- UB42. **Load Balancer** (2 weeks) - Prerequisites: UB41
- UB43. **Proxy Server** (2 weeks) - Prerequisites: UB42
- UB44. **Mail Server** (3 weeks) - Prerequisites: UB43
- UB45. **DNS Server** (2 weeks) - Prerequisites: LB26
- UB46. **DHCP Server** (2 weeks) - Prerequisites: LB27
- UB47. **VPN Server** (3 weeks) - Prerequisites: MB52
- UB48. **Message Broker** (3 weeks) - Prerequisites: B57
- UB49. **Distributed Cache** (3 weeks) - Prerequisites: B15, UB48
- UB50. **Consensus Protocol** (3 weeks) - Prerequisites: UB49

**UB51-60: Real-Time Systems**
- UB51. **RTOS Kernel** (3 weeks) - Prerequisites: MB38, UB3
- UB52. **Rate Monotonic Scheduler** (2 weeks) - Prerequisites: UB51
- UB53. **Priority Ceiling Protocol** (2 weeks) - Prerequisites: UB52
- UB54. **Watchdog System** (1 week) - Prerequisites: UB53
- UB55. **Time Synchronization** (2 weeks) - Prerequisites: UB54
- UB56. **Fault Tolerance** (2 weeks) - Prerequisites: UB55
- UB57. **Hot Standby** (2 weeks) - Prerequisites: UB56
- UB58. **Flight Controller** (3 weeks) - Prerequisites: UB57
- UB59. **Industrial Controller** (3 weeks) - Prerequisites: UB58
- UB60. **Medical Device OS** (3 weeks) - Prerequisites: UB59

---

## 🌸 FLOWERS: Capstone Projects (6 Projects, 2-3 months each)

### Flower 1: Bare-Metal Multi-System Emulator (2-3 months)
**Prerequisites**: UB23-25, MB40, MB10
**Description**: Complete emulation platform running directly on Raspberry Pi 3 hardware without any OS.

**Core Requirements**:
- Boot directly to emulator menu
- Support NES, SNES, GameBoy emulation
- Implement all graphics rendering from scratch
- Create audio synthesis system
- Handle USB controllers natively
- Library management system with metadata
- Save state support
- Network play capability

**Technical Challenges**:
- Write ARM assembly bootstrap
- Implement memory management unit
- Create graphics driver for Pi GPU
- Build USB HID driver
- Optimize for 60fps on all systems

### Flower 2: Beginner Streamer's Toolkit (2-3 months)
**Prerequisites**: MB12, MB1, UB41, MB69
**Description**: Complete streaming solution with zero external dependencies, designed for someone just starting out.

**Core Components**:
- **Simple Capture**: Basic screen and window capture
- **Audio Basics**: Microphone input with noise reduction
- **Stream Output**: RTMP to Twitch/YouTube
- **Basic Overlay**: Text, images, alerts
- **Scene Switching**: Smooth transitions
- **Chat Reader**: Display chat on screen
- **Simple Controls**: Hotkeys and basic UI

**Key Features**:
- One-click streaming setup
- Automatic bitrate adjustment
- Built-in stream health monitoring
- Local recording option
- Basic webcam support
- Stream notifications

### Flower 3: Retro Game Maker (2-3 months)
**Prerequisites**: MB70, LB20, MB1, B76
**Description**: Visual game creation tool where anyone can make NES-style games without coding, like Mario Maker but for everything.

**Creation Tools**:
- **Visual Level Editor**: Drag-and-drop tiles, enemies, items
- **Sprite Designer**: Pixel art editor with animations
- **Sound Composer**: Chiptune music creation
- **Logic System**: Visual scripting for game rules
- **Physics Presets**: Platformer, top-down, shooter
- **Publishing**: Export as actual NES ROMs!

**Consumer Features**:
- Built-in tutorial games to remix
- Community asset sharing
- Couch co-op testing mode
- Achievement system designer
- Speed-run timer support
- One-click sharing to friends
- Runs on Raspberry Pi for TV play

### Flower 4: AR Pet Simulator (2-3 months)
**Prerequisites**: MB1, MB63, B46, MB35
**Description**: Tamagotchi meets Pokemon Go - virtual pets that live in your real world through computer vision.

**Pet System**:
- **Computer Vision**: Track real objects for pet interaction
- **Pet AI**: Personality development, mood system
- **Evolution Tree**: Pets grow based on care style
- **Mini-Games**: Play with pets using hand gestures
- **Social Features**: Pet playdates via local network
- **Collection System**: Discover rare pets in special conditions

**Fun Features**:
- Pets react to real objects (hide behind cups, play with pens)
- Feed using real food images
- Pet genetics for breeding
- Daily surprises and events
- Webcam-based AR (no phone needed)
- Desktop widget mode
- Emotion recognition for pet bonding

### Flower 5: Music Visualizer Studio (2-3 months)
**Prerequisites**: MB13, MB1, B38, MB16
**Description**: Create stunning music videos from any song - think Winamp visualizer meets professional VJ software.

**Visualization Engine**:
- **Audio Analysis**: Beat detection, frequency separation
- **Effect Library**: 50+ visual effects
- **Scene Builder**: Layer and combine effects
- **Particle Systems**: React to music dynamics
- **3D Environments**: Traveling through sound worlds
- **Color Schemes**: Auto-generate from album art

**Creator Features**:
- Real-time recording to video
- Spotify/YouTube integration
- Live performance mode
- Custom shader support
- Motion capture from webcam
- Social media export presets
- VR headset support

### Flower 6: Desktop Pet Paradise (3 months)
**Prerequisites**: MB63, B76, MB1, B46
**Description**: Adorable desktop pets that live on your screen edges, play together, and develop personalities - like Shimeji meets The Sims.

**Pet Features**:
- **Physics Playground**: Pets climb windows, knock over icons
- **Personality Engine**: Each pet unique based on interactions
- **Cross-Screen Travel**: Pets visit between monitors/computers
- **Mini-Games**: Play directly on desktop
- **Breeding System**: Combine pets for rare types
- **Weather Reactions**: Pets respond to real weather
- **Holiday Events**: Special pets and activities

**Social Elements**:
- Trade pets with friends
- Pet Olympics competitions
- Build furniture from app windows
- Leave treats on desktop
- Pet photo mode with filters
- Twitch integration for streamers
- Mobile companion app
- Community pet contests

---

## Support Systems

### Failure Recovery System

**Debug Journal Structure**:
```
Problem: [What broke]
Hypothesis: [Why it might have broken]
Test: [How to verify hypothesis]
Result: [What actually happened]
Learning: [Key insight gained]
```

**Minimum Viable Criteria**:
- Compiles without warnings
- Runs without crashing
- Produces expected output
- No memory leaks

**Excellence Criteria**:
- Sub-millisecond response time
- Zero allocations in hot path
- 100% code coverage
- Clean valgrind report

### Weekly Reflection Questions
1. What assumption about C was wrong this week?
2. Which bug took longest to fix and why?
3. What pattern am I starting to see repeatedly?
4. Which project excited me most?

### Anti-Rust Mechanisms

**Daily Kata** (15 min):
- Monday: Pointer arithmetic
- Tuesday: String manipulation  
- Wednesday: Bit operations
- Thursday: Memory management
- Friday: Data structure implementation

**Monthly Regression Projects**:
- Reimplement a ROOT project using only BASE knowledge
- Optimize a BASE project using BRANCH techniques
- Combine 3 previous projects into new tool

### Portfolio Architecture

```
codebase/
├── core/          # Your standard library
├── tools/         # Completed CLI tools
├── engines/       # Reusable components
├── apps/          # Full applications
└── docs/          # Pattern documentation
```

### Code Quality Metrics

**Nintendo Standard Checklist**:
- [ ] Zero compiler warnings
- [ ] Zero memory leaks
- [ ] Handles all error cases
- [ ] Consistent style throughout
- [ ] Meaningful variable names
- [ ] Comprehensive comments
- [ ] Stress tested thoroughly
- [ ] Performance profiled
- [ ] Security reviewed

---

## Learning Resources

### Modern C Programming Books (2020+)

1. **"Modern C" by Jens Gustedt (2024 Edition)**
   - Comprehensive modern C programming
   - Focus on C23 features
   - Excellent for understanding language evolution

2. **"Effective C" by Robert C. Seacord (2020)**
   - Security-focused C programming
   - Modern best practices
   - Engaging writing style

3. **"Bare Metal C" by Stephen Oualline (2022)**
   - Embedded systems focus
   - No-OS programming
   - Perfect for Raspberry Pi projects

4. **"The Art of 64-Bit Assembly" by Randall Hyde (2021)**
   - Modern assembly programming
   - Integrates well with C
   - Essential for system programming

5. **"Computer Systems: A Programmer's Perspective" 4th Ed (2023)**
   - Systems programming fundamentals
   - Excellent exercises
   - Bridges hardware/software gap

### Online Resources

1. **Beej's Guides** (Updated 2023)
   - Network programming
   - IPC programming
   - Humorous, engaging style

2. **OSDev Wiki**
   - Operating system development
   - Community-driven
   - Practical tutorials

3. **Handmade Network**
   - From-scratch programming
   - Video content available
   - Active community

---

## 12-Month Schedule (60 hours/week)

### Month 1-2: ROOTS (300 hours)
- Week 1-2: R1-R15 (Basic syntax, pointers)
- Week 3-4: R16-R30 (Structures, files)
- Week 5-6: R31-R40 (Algorithms, bits)
- Week 7-8: R41-R50 (System interaction)

### Month 3-5: BASE (700 hours)
- Week 9-11: B1-B25 (Data structures)
- Week 12-14: B26-B50 (Algorithms)
- Week 15-17: B51-B75 (System programming)
- Week 18-20: B76-B100 (Architecture)

### Month 6-7: LOWER BRANCHES (400 hours)
- Week 21-24: LB1-LB25 (CLI/Games)
- Week 25-28: LB26-LB50 (Network/System)

### Month 8-9: MIDDLE BRANCHES (500 hours)
- Week 29-32: MB1-MB40 (Graphics/Audio/Embedded)
- Week 33-36: MB41-MB80 (Compilers/Security/Tools)

### Month 10-11: UPPER BRANCHES (600 hours)
- Week 37-40: UB1-UB30 (OS/Languages/Emulators)
- Week 41-44: UB31-UB60 (Tools/Network/Real-time)

### Month 12+: FLOWERS (500+ hours)
- Choose based on discovered interests
- Minimum 2-3 flowers for portfolio
- Consider building all 6 if time allows
- Document extensively

---

## Skill Checkpoints

### After ROOTS
- Can implement any algorithm in C
- Comfortable with pointers and memory
- Understands system calls

### After BASE  
- Can build complex data structures
- Writes production-quality code
- Understands computer architecture

### After LOWER BRANCHES
- Can create useful tools
- Comfortable with networking
- Basic game development skills

### After MIDDLE BRANCHES
- Domain expertise emerging
- Can tackle complex problems
- Performance optimization skills

### After UPPER BRANCHES
- Systems programming mastery
- Can build OS components
- Language implementation skills

### After FLOWERS
- Portfolio demonstrates expertise
- Ready for any C challenge  
- True understanding of computing
- Created 2-6 consumer applications people love

---

## Final Notes

This curriculum emphasizes:
1. **Building over reading** - Every concept is learned by implementation
2. **Quality over quantity** - Nintendo standard throughout
3. **Foundation first** - Each level prepares for the next
4. **Discovery through doing** - Find your passion by exploring everything
5. **No shortcuts** - Pure C, no libraries, no AI assistance

Remember: The goal isn't just to learn C, but to truly understand how computers work at every level. By the end, you'll have built everything from basic utilities to operating systems, all from scratch, all meeting the highest quality standards.

The journey is challenging but rewarding. Each project builds your confidence and skills. Stay persistent through the difficult moments - they're where the real learning happens.

Good luck on your journey through the Maplewood Tree!