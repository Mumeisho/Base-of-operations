# Stage 18: Networking and Communication (Projects 337-352)

**Learning Goal**: Master network programming concepts

## C1: **Socket Creation Basics**

- **Description**: Create TCP socket programs demonstrating: socket creation, address structures, binding to ports, error handling for socket operations, and socket option setting.
- **Prerequisites**: UB56, MB25
- **New Concept**: Socket programming

## C2: **TCP Client-Server Simple**

- **Description**: Build basic client-server: server listens and accepts, client connects and sends, bidirectional communication, graceful disconnection, and connection status display.
- **Prerequisites**: C1
- **New Concept**: TCP communication

## C3: **UDP Datagram Exchange**

- **Description**: Implement UDP communication: connectionless sockets, sendto/recvfrom usage, packet loss demonstration, broadcast messages, and UDP vs TCP comparison.
- **Prerequisites**: C2
- **New Concept**: UDP protocol

## C4: **Multi-Client Server Design**

- **Description**: Create concurrent server handling multiple clients using: fork per client, select/poll for I/O multiplexing, client tracking, and resource management.
- **Prerequisites**: C2, UB54
- **New Concept**: Concurrent servers

## C5: **HTTP Client Implementation**

- **Description**: Build HTTP client that: constructs GET/POST requests, parses HTTP responses, handles headers, follows redirects (basic), and displays retrieved content.
- **Prerequisites**: C2, LB34
- **New Concept**: HTTP protocol

## C6: **HTTP Server Basic**

- **Description**: Develop simple web server: serve static files, generate HTTP responses, handle multiple requests, MIME type detection, and basic error pages.
- **Prerequisites**: C5, C4
- **New Concept**: HTTP server

## C7: **File Transfer Protocol**

- **Description**: Implement file transfer system: protocol design, chunked transfers, progress indication, resume capability, and integrity verification.
- **Prerequisites**: MB28, C2
- **New Concept**: Protocol design

## C8: **Chat Application Core**

- **Description**: Create multi-user chat: server manages connections, broadcasts messages, private messages, user list maintenance, and formatted message display.
- **Prerequisites**: C4, LB36
- **New Concept**: Real-time messaging

## C9: **Port Scanner Tool**

- **Description**: Build port scanner showing: TCP connect scanning, service detection, timeout handling, parallel scanning, and result reporting.
- **Prerequisites**: C1, UB61
- **New Concept**: Network scanning

## C10: **Packet Sniffer Basic**

- **Description**: Create packet capturer: raw socket usage, Ethernet frame parsing, IP header extraction, TCP/UDP discrimination, and packet statistics.
- **Prerequisites**: C9, LB42
- **New Concept**: Packet analysis

## C11: **DNS Resolver Client**

- **Description**: Implement DNS lookup: query construction, response parsing, recursive queries, caching results, and timeout/retry logic.
- **Prerequisites**: C3, MB56
- **New Concept**: DNS protocol

## C12: **Network Protocol Parser**

- **Description**: Build protocol analyzer for: Ethernet headers, IP headers, TCP/UDP headers, application layer basics, and protocol statistics display.
- **Prerequisites**: C10, LB67
- **New Concept**: Protocol parsing

## C13: **Socket Options Explorer**

- **Description**: Demonstrate socket options: SO_REUSEADDR, SO_KEEPALIVE, SO_LINGER, TCP_NODELAY, buffer sizes, and performance impact analysis.
- **Prerequisites**: C1, UB65
- **New Concept**: Socket tuning

## C14: **Non-Blocking Sockets**

- **Description**: Create non-blocking examples: fcntl for non-blocking, handling EAGAIN/EWOULDBLOCK, event-driven design, and async connection handling.
- **Prerequisites**: UB55, C4
- **New Concept**: Non-blocking I/O

## C15: **Network Byte Order Handler**

- **Description**: Build byte order converter: htons/ntohs usage, protocol marshalling, endianness detection, portable network code, and data serialization.
- **Prerequisites**: LB22, C12
- **New Concept**: Byte ordering

## C16: **TEST: Distributed System Core**

- **Description**: Create distributed application with: client-server architecture, custom application protocol, multi-threaded server, connection pooling on client, heartbeat/keepalive mechanism, automatic reconnection, protocol versioning, and comprehensive error handling.
- **Prerequisites**: C1-C15
- **New Concept**: Integration of networking
