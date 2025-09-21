# Networking Basics Project

## Description
This project introduces basic networking concepts and how to use Bash scripts to interact with and explore network settings on Ubuntu 22.04. It covers localhost, the special address 0.0.0.0, the hosts file, and how to display active network interfaces.

## Learning Objectives
By the end of this project, you should be able to explain:

- What is localhost and 127.0.0.1
- What is 0.0.0.0
- What is /etc/hosts
- How to display your machine’s active network interfaces

## Key Concepts

### Localhost / 127.0.0.1
- Localhost refers to the current machine.
- 127.0.0.1 is the IPv4 loopback address.
- Any traffic sent to 127.0.0.1 never leaves the machine.

### 0.0.0.0
- A non-routable meta-address.
- When a server binds to 0.0.0.0, it listens on all available network interfaces.
- In routing, it can represent the default route.

### /etc/hosts
- A system file that maps hostnames to IP addresses.
- It is checked before DNS when resolving hostnames.
- Example:
