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
OSI (Open Systems Interconnection) is an abstract model to describe layered communication and computer network design. The idea is to segregate the different parts of what make communication possible.

It is organized from the lowest level to the highest level:

The lowest level: layer 1 which is for transmission on physical layers with electrical impulse, light or radio signal
The highest level: layer 7 which is for application specific communication like SNMP for emails, HTTP for your web browser, etc
Keep in mind that the OSI model is a concept, it’s not even tangible. The OSI model doesn’t perform any functions in the networking process. It is a conceptual framework so we can better understand complex interactions that are happening. Most of the functionality in the OSI model exists in all communications systems.

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
