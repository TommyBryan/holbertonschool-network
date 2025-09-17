# holbertonschool-network
## Networking basics #0

## *Learning Objectives*

### *OSI MODEL*
* What it is
* How many layers it has
* How it is organized

### *What is LAN*
* Typcal usage
* Typical geographical size

### *What is the Internet*
* What is an IP address
* What are the 2 types of IP address
* What is `localhost`
* What is a subnet
* Why IPv6 was created

### *TCP/UDP*
* What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
* What is the main difference between TCP and UDP
* What is a port
* Memorize SSH, HTTP and HTTPS port numbers
* What tool/protocol is often used to check if a device is connected to a network

___

### OSI MODEL
The OSI model (Open Systems Interconnection model) is a conceptual framework used to understand and describe how data is transmitted over a network. It breaks down the process of communication into seven layers, each with its own specific role.

Think of it like sending a package: each layer is responsible for wrapping/unwrapping, addressing, and delivering the package until it reaches the right person.

### The 7 Layers of the OSI Model

### 1. Physical Layer

- Role: Deals with the actual transmission of raw bits (0s and 1s) over a physical medium.

- Examples: Cables, switches, NICs, electrical signals, light pulses.

### 2. Data Link Layer

- Role: Ensures reliable transfer of data across the physical link. It packages bits into frames and handles MAC addressing and error detection.

- Examples: Ethernet, Wi-Fi (IEEE 802.11), switches.

### 3. Network Layer

- Role: Responsible for routing and delivering packets across multiple networks. Adds logical addressing (IP addresses).

- Examples: IP (IPv4, IPv6), routers.

###  4. Transport Layer

- Role: Provides end-to-end communication, reliability, and flow control. Breaks data into segments, ensures they arrive correctly and in order.

- Examples: TCP, UDP.

### 5. Session Layer

- Role: Manages sessions (connections) between applications—opening, maintaining, and closing communication.

- Examples: NetBIOS, RPC, session tokens.

### 6. Presentation Layer

- Role: Translates data into a format applications can understand. Handles encryption, compression, character encoding.

- Examples: SSL/TLS, JPEG, PNG, ASCII, EBCDIC.

### 7. Application Layer

- Role: Closest to the user. Provides network services directly to applications.

- Examples: HTTP, FTP, SMTP, DNS.
___
