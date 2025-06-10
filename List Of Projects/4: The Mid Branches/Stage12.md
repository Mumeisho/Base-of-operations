# Stage 12: Memory Management (Projects 177-200)

**Learning Goal**: Master dynamic memory allocation and management

## MB1: **Basic malloc Usage**

- **Description**: Create a program that allocates memory for single integers, floats, and characters using malloc. Show proper allocation, usage, and freeing. Display addresses and values before/after allocation.
- **Prerequisites**: LB1, LB11
- **New Concept**: Dynamic memory allocation

## MB2: **Memory Deallocation Practice**

- **Description**: Build examples showing proper free() usage: freeing in reverse order of allocation, setting pointers to NULL after free, avoiding double-free, and demonstrating memory leaks without free.
- **Prerequisites**: MB1
- **New Concept**: Memory deallocation

## MB3: **Memory Leak Detector**

- **Description**: Implement a simple memory tracker that counts allocations/deallocations, reports unfreed memory, tracks allocation sizes, and identifies common leak patterns in example code.
- **Prerequisites**: MB2, TB52
- **New Concept**: Leak detection

## MB4: **Dynamic Array Implementation**

- **Description**: Create a resizable array that starts with capacity 4, doubles when full, tracks size and capacity, provides append and remove operations, and properly manages memory during resize.
- **Prerequisites**: MB1, TB69
- **New Concept**: Dynamic arrays

## MB5: **calloc vs malloc Comparison**

- **Description**: Build demonstrations showing: malloc (uninitialized) vs calloc (zero-initialized), performance differences, when to use each, and memory content examination before/after allocation.
- **Prerequisites**: MB1, LB16
- **New Concept**: calloc function

## MB6: **Memory Reallocation System**

- **Description**: Develop examples using realloc to: grow arrays, shrink arrays, handle realloc failures, show when memory moves vs stays, and implement safe realloc wrapper.
- **Prerequisites**: MB4, MB2
- **New Concept**: realloc function

## MB7: **Custom memcpy Implementation**

- **Description**: Create your own memcpy handling: byte-by-byte copy, word-aligned copy for speed, overlap detection, and performance comparison. Show memory contents during copy.
- **Prerequisites**: LB42, MB1
- **New Concept**: Memory copying

## MB8: **Memory Comparison Tool**

- **Description**: Implement memcmp functionality for: equality checking, finding first difference, comparing structures byte-wise, and handling different data types. Display comparison process.
- **Prerequisites**: MB7, LB63
- **New Concept**: Memory comparison

## MB9: **Memory Pattern Setter**

- **Description**: Build memset alternatives: set bytes, set words, set patterns, and clear sensitive data. Show memory state before/after, demonstrate security clearing.
- **Prerequisites**: MB5, MB7
- **New Concept**: Memory initialization

## MB10: **Stack Data Structure**

- **Description**: Implement dynamic stack with: push, pop, peek, isEmpty, automatic growth, and proper cleanup. Show stack state after each operation with memory addresses.
- **Prerequisites**: MB4, TB55
- **New Concept**: Dynamic stack

## MB11: **Queue Implementation**

- **Description**: Create dynamic queue using: array with wrap-around, head/tail pointers, enqueue/dequeue, automatic resize, and memory efficiency display.
- **Prerequisites**: MB10
- **New Concept**: Dynamic queue

## MB12: **Memory Pool Manager**

- **Description**: Build a simple memory pool that pre-allocates large block, provides fixed-size allocations, tracks free slots, and shows fragmentation reduction benefits.
- **Prerequisites**: MB3, MB6
- **New Concept**: Memory pooling

## MB13: **Reference Counting System**

- **Description**: Implement basic reference counting: track reference count, increment on copy, decrement on release, free when count reaches zero, and prevent use-after-free.
- **Prerequisites**: MB3, LB53
- **New Concept**: Reference counting

## MB14: **Memory Fragmentation Demo**

- **Description**: Create visualization of fragmentation: allocate various sizes, free in different orders, show memory gaps, demonstrate external fragmentation, and compaction concepts.
- **Prerequisites**: MB12, MB2
- **New Concept**: Fragmentation

## MB15: **Alignment Handler**

- **Description**: Build alignment demos: align allocations to boundaries, show performance impact, handle structure alignment, and implement aligned_alloc functionality.
- **Prerequisites**: LB68, MB1
- **New Concept**: Memory alignment

## MB16: **Buffer Overflow Detector**

- **Description**: Implement overflow detection using guard bytes: place sentinels around allocations, check for corruption, demonstrate common overflow scenarios, and safe alternatives.
- **Prerequisites**: MB7, TB68
- **New Concept**: Overflow protection

## MB17: **Custom Allocator Basic**

- **Description**: Create simple custom allocator: manage fixed memory buffer, implement fit strategies (first-fit), track free list, show allocation map, and compare with malloc.
- **Prerequisites**: MB12, MB14
- **New Concept**: Custom allocation

## MB18: **Memory Usage Profiler**

- **Description**: Build profiler tracking: current allocations, peak usage, allocation patterns, allocation call sites (simulated), and generate usage report with statistics.
- **Prerequisites**: MB3, TB57
- **New Concept**: Memory profiling

## MB19: **String Memory Manager**

- **Description**: Develop dynamic string functions: strdup implementation, dynamic string concatenation, string array with dynamic strings, and proper cleanup of string collections.
- **Prerequisites**: LB28, MB4
- **New Concept**: Dynamic strings

## MB20: **Matrix Memory Handler**

- **Description**: Create dynamic 2D arrays: single allocation technique, row-pointer technique, access like normal 2D array, and safe deallocation. Compare memory layouts.
- **Prerequisites**: TB65, MB6
- **New Concept**: Dynamic 2D arrays

## MB21: **Memory Error Recovery**

- **Description**: Implement robust allocation: check malloc return, handle allocation failures, provide fallback strategies, clean partial allocations, and demonstrate graceful degradation.
- **Prerequisites**: MB16, TB48
- **New Concept**: Error handling

## MB22: **Memory Statistics Tracker**

- **Description**: Build comprehensive statistics: allocation count by size, fragmentation percentage, allocation/free call frequency, memory usage timeline, and performance metrics.
- **Prerequisites**: MB18, TB36
- **New Concept**: Memory analytics

## MB23: **Shared Buffer Manager**

- **Description**: Create shared memory simulation: multiple "users" of same buffer, reference counting for sharing, copy-on-write concept, and demonstrate memory savings.
- **Prerequisites**: MB13, MB7
- **New Concept**: Shared memory concepts

## MB24: **TEST: Dynamic Database Engine**

- **Description**: Build a complete database system with: dynamic array of records (structures), automatic array resizing, string fields with dynamic allocation, index structure for fast lookup, memory-efficient storage, comprehensive error handling, memory usage reporting, proper cleanup on exit, and stress testing with many records.
- **Prerequisites**: MB1-MB23
- **New Concept**: Integration of memory management
