# Stage 13: File I/O and Data Persistence (Projects 201-224)

**Learning Goal**: Master file operations and data storage

## MB25: **File Open/Close Basics**

- **Description**: Create a file handler that demonstrates opening files in different modes (r, w, a, r+, w+, a+), checking if open succeeded, proper file closing, and handling common errors.
- **Prerequisites**: MB2, TB29
- **New Concept**: File operations

## MB26: **Text File Reader**

- **Description**: Build a text file reader that reads character by character with fgetc, line by line with fgets, entire file into buffer, and displays with line numbers and character count.
- **Prerequisites**: MB25, LB39
- **New Concept**: File reading

## MB27: **Text File Writer**

- **Description**: Develop a file writer using: fprintf for formatted output, fputs for strings, fputc for characters, and creating reports with tables, headers, and formatted data.
- **Prerequisites**: MB26, R4
- **New Concept**: File writing

## MB28: **File Copy Utility**

- **Description**: Implement file copying: byte-by-byte copy, buffer-based copy for efficiency, progress indicator, verify copy success, and handle binary files properly.
- **Prerequisites**: MB27, MB7
- **New Concept**: Binary file handling

## MB29: **File Size Calculator**

- **Description**: Create utilities to determine file size using: fseek/ftell method, reading until EOF, stat function (if available), and display sizes in bytes, KB, MB.
- **Prerequisites**: MB26
- **New Concept**: File positioning

## MB30: **File Existence Checker**

- **Description**: Build file validators that check if file exists, is readable/writable, is empty, and get file attributes. Handle permissions and access errors appropriately.
- **Prerequisites**: MB25, TB5
- **New Concept**: File validation

## MB31: **Directory Scanner**

- **Description**: Create a directory listing tool that shows files with sizes, types (simulation), modification times (if available), and sorted display options.
- **Prerequisites**: MB30, LB38
- **New Concept**: Directory operations

## MB32: **Log File Manager**

- **Description**: Implement a logger that appends timestamped entries, rotates logs when size limit reached, maintains multiple log levels, and provides log viewing functionality.
- **Prerequisites**: MB27, LB57
- **New Concept**: Log management

## MB33: **Configuration File Parser**

- **Description**: Build config file handler reading key=value pairs, supporting comments (#), blank lines, sections [section], and providing lookup functions for values.
- **Prerequisites**: MB26, LB34
- **New Concept**: File parsing

## MB34: **CSV File Processor**

- **Description**: Create CSV handler that reads comma-separated data, handles quoted fields, parses into structures, writes CSV from structures, and manages headers properly.
- **Prerequisites**: MB33, LB44
- **New Concept**: CSV format

## MB35: **Binary File Database**

- **Description**: Develop binary file storage for structures: write structures directly, read back into memory, handle endianness issues, and implement simple indexing.
- **Prerequisites**: MB28, LB66
- **New Concept**: Binary persistence

## MB36: **Random Access File System**

- **Description**: Build random access demonstrations: seek to specific positions, read/write at offsets, implement record-based access, and create simple file-based array.
- **Prerequisites**: MB35, MB29
- **New Concept**: Random access

## MB37: **File Backup System**

- **Description**: Create backup utility that creates numbered backups, maintains backup history, removes old backups, and verifies backup integrity with checksums.
- **Prerequisites**: MB28, TB22
- **New Concept**: Backup strategies

## MB38: **File Compression Basic**

- **Description**: Implement simple compression: run-length encoding for files, basic Huffman concepts, show compression ratios, and handle binary data properly.
- **Prerequisites**: LB46, MB35
- **New Concept**: File compression

## MB39: **File Encryption Tool**

- **Description**: Build file encryptor using: XOR with key file, byte substitution, basic stream cipher concepts, and ensuring decryption recovers original.
- **Prerequisites**: LB40, MB28
- **New Concept**: File encryption

## MB40: **Database File Format**

- **Description**: Design custom database format with: file header, record storage, free space management, simple indexing, and CRUD operations on records.
- **Prerequisites**: MB36, MB17
- **New Concept**: File format design

## MB41: **File Integrity Checker**

- **Description**: Create integrity tools: calculate file checksums (simple hash), detect file changes, verify file not corrupted, and store/compare checksums.
- **Prerequisites**: MB29, TB23
- **New Concept**: Integrity checking

## MB42: **Temporary File Handler**

- **Description**: Implement temp file management: create unique temp files, automatic cleanup on exit, temp directory usage, and safe temp file patterns.
- **Prerequisites**: MB25, MB2
- **New Concept**: Temporary files

## MB43: **File Merge Utility**

- **Description**: Build file merger that combines multiple files, handles different merge strategies (append, interleave), removes duplicates option, and maintains formatting.
- **Prerequisites**: MB27, TB63
- **New Concept**: File merging

## MB44: **Binary File Editor**

- **Description**: Create hex editor basics: display file in hex, edit bytes at positions, search for byte patterns, and save modifications. Show offset and ASCII.
- **Prerequisites**: MB36, LB16
- **New Concept**: Binary editing

## MB45: **File System Monitor**

- **Description**: Develop file monitor that tracks file size changes, detects modifications (polling), logs file operations, and reports file system statistics.
- **Prerequisites**: MB32, MB41
- **New Concept**: File monitoring

## MB46: **Serialization Framework**

- **Description**: Build generic serialization: save different data types, handle nested structures, version management, and backward compatibility concepts.
- **Prerequisites**: LB66, MB35
- **New Concept**: Advanced serialization

## MB47: **File Cache System**

- **Description**: Implement simple file cache: buffer frequently read data, track cache hits/misses, implement cache invalidation, and show performance improvement.
- **Prerequisites**: MB12, MB26
- **New Concept**: File caching

## MB48: **TEST: Personal Information Manager**

- **Description**: Create a complete PIM system with: contact storage in binary files, text-based data export/import, search functionality across files, backup and restore features, file-based indexing for fast search, configuration file for settings, log file for operations, data integrity verification, and comprehensive error handling.
- **Prerequisites**: MB25-MB47
- **New Concept**: Integration of file I/O concepts
