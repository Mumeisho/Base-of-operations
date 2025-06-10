# Stage 16: System Programming Fundamentals (Projects 281-308)

**Learning Goal**: Interface with operating system services

## UB33: **Process Creation Basics**

- **Description**: Create programs demonstrating fork(): parent/child identification, process IDs, fork return values, multiple fork calls creating process tree, and process family visualization.
- **Prerequisites**: MB1, TB1
- **New Concept**: Process creation

## UB34: **Process Termination Control**

- **Description**: Build process lifecycle manager: exit with status codes, wait for child termination, retrieve exit status, handle zombie processes, and orphan process demonstration.
- **Prerequisites**: UB33
- **New Concept**: Process termination

## UB35: **Process Hierarchy Explorer**

- **Description**: Develop process tree viewer showing: parent-child relationships, process groups, session leaders, init process inheritance, and hierarchical display.
- **Prerequisites**: UB34, MB57
- **New Concept**: Process hierarchy

## UB36: **Signal Handler Basic**

- **Description**: Implement signal handling for: SIGINT (Ctrl+C), SIGTERM, custom handlers, signal-safe functions, handler installation/restoration, and signal demonstration.
- **Prerequisites**: UB34, TB50
- **New Concept**: Signal handling

## UB37: **Signal Generation System**

- **Description**: Create signal sender/receiver: kill() system call, raise() for self-signaling, alarm() for timed signals, real-time signals, and signal queuing concepts.
- **Prerequisites**: UB36
- **New Concept**: Signal generation

## UB38: **Timer and Alarm Manager**

- **Description**: Build timer system using: alarm() for timeouts, interval timers, signal-based timing, timer precision testing, and multiple timer simulation.
- **Prerequisites**: UB37, LB57
- **New Concept**: Timer signals

## UB39: **Pipe Communication**

- **Description**: Implement unnamed pipes: create pipe, fork processes, parent-child communication, pipe direction closing, and full-duplex simulation.
- **Prerequisites**: UB33, MB26
- **New Concept**: Pipe IPC

## UB40: **Named Pipe FIFO System**

- **Description**: Create FIFO communication: mkfifo creation, reader/writer processes, non-blocking operations, multiple clients, and FIFO-based chat system.
- **Prerequisites**: UB39, MB30
- **New Concept**: Named pipes

## UB41: **Shared Memory Basic**

- **Description**: Build shared memory demo: create/attach segments, inter-process data sharing, synchronization needs, cleanup handling, and performance benefits.
- **Prerequisites**: MB23, UB34
- **New Concept**: Shared memory

## UB42: **Message Queue System**

- **Description**: Develop message queue IPC: create queues, send/receive messages, message types/priorities, queue permissions, and multi-process messaging.
- **Prerequisites**: MB54, UB40
- **New Concept**: Message queues

## UB43: **Semaphore Operations**

- **Description**: Implement semaphore usage: binary semaphores, counting semaphores, wait/signal operations, critical section protection, and resource counting.
- **Prerequisites**: UB41, TB29
- **New Concept**: Semaphores

## UB44: **Mutex Implementation**

- **Description**: Create mutex demonstrations: initialization, lock/unlock, trylock operations, error checking mutexes, and deadlock scenarios.
- **Prerequisites**: UB43
- **New Concept**: Mutexes

## UB45: **POSIX Thread Basics**

- **Description**: Build thread programs: pthread creation, joining threads, detached threads, thread IDs, return values, and thread vs process comparison.
- **Prerequisites**: UB44, UB33
- **New Concept**: Threading

## UB46: **Thread Synchronization**

- **Description**: Develop thread sync examples: mutex for shared data, condition variables, barriers, reader-writer locks, and synchronization patterns.
- **Prerequisites**: UB45
- **New Concept**: Thread sync

## UB47: **Thread-Safe Programming**

- **Description**: Create thread-safe code: identify race conditions, use thread-local storage, implement thread-safe functions, and demonstrate unsafe vs safe code.
- **Prerequisites**: UB46, MB13
- **New Concept**: Thread safety

## UB48: **Deadlock Prevention Lab**

- **Description**: Build deadlock demos: create deadlock scenarios, implement prevention strategies, detect deadlocks, resource ordering, and banker's algorithm concepts.
- **Prerequisites**: UB44, UB47
- **New Concept**: Deadlock handling

## UB49: **Producer-Consumer Classic**

- **Description**: Implement producer-consumer: bounded buffer, multiple producers/consumers, semaphore solution, mutex/condvar solution, and performance analysis.
- **Prerequisites**: UB46, MB11
- **New Concept**: Classic sync problem

## UB50: **Reader-Writer Problem**

- **Description**: Solve reader-writer with: reader preference, writer preference, fair solution, upgradeable locks, and concurrent access demonstration.
- **Prerequisites**: UB49
- **New Concept**: Reader-writer

## UB51: **Dining Philosophers**

- **Description**: Create dining philosophers: deadlock-prone version, deadlock-free solutions, resource hierarchy, arbitrator solution, and visualization.
- **Prerequisites**: UB48, UB50
- **New Concept**: Resource allocation

## UB52: **Memory Mapping Files**

- **Description**: Build mmap examples: map files to memory, shared mappings, private mappings, anonymous mappings, and performance benefits demonstration.
- **Prerequisites**: MB41, MB26
- **New Concept**: Memory mapping

## UB53: **File Locking Mechanisms**

- **Description**: Implement file locking: advisory vs mandatory, exclusive/shared locks, lock regions, deadlock in file locking, and cooperative locking.
- **Prerequisites**: MB30, UB44
- **New Concept**: File locking

## UB54: **I/O Multiplexing Select**

- **Description**: Create select() examples: monitor multiple file descriptors, timeout handling, stdin with sockets simulation, and event-driven programming.
- **Prerequisites**: MB26, UB40
- **New Concept**: I/O multiplexing

## UB55: **Asynchronous I/O Demo**

- **Description**: Build async I/O programs: non-blocking operations, signal-driven I/O, polling strategies, async vs sync performance, and event loops.
- **Prerequisites**: UB54, UB36
- **New Concept**: Async I/O

## UB56: **System Call Error Handling**

- **Description**: Develop robust error handling: errno checking, perror/strerror usage, error recovery strategies, logging errors, and system call retry logic.
- **Prerequisites**: MB21, UB34
- **New Concept**: System errors

## UB57: **Resource Monitor Tool**

- **Description**: Create system monitor showing: CPU usage, memory statistics, process counts, file descriptor usage, and resource limits (getrlimit).
- **Prerequisites**: MB22, UB35
- **New Concept**: Resource monitoring

## UB58: **Daemon Process Creator**

- **Description**: Build daemon programs: proper daemonization steps, syslog integration, PID file handling, signal handling in daemons, and service management.
- **Prerequisites**: UB36, MB32
- **New Concept**: Daemon processes

## UB59: **Inter-Process Communicator**

- **Description**: Implement IPC comparison tool: benchmark different IPC methods, choose appropriate IPC, handle IPC errors, and create IPC abstraction layer.
- **Prerequisites**: UB39-UB42
- **New Concept**: IPC comparison

## UB60: **TEST: Multi-Process Web Server**

- **Description**: Build concurrent web server with: multi-process architecture using fork, socket handling with select/poll, shared memory for statistics, signal handling for graceful shutdown, file locking for log files, daemon mode operation, resource monitoring and limits, and comprehensive error handling.
- **Prerequisites**: UB33-UB59
- **New Concept**: Integration of system programming
