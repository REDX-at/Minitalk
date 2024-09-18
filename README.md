# MiniTalk - 1337 (42 Network)

![Dining Philosophers](https://github.com/REDX-at/Minitalk/blob/master/images/minitalk%2042.png)

MiniTalk is a project designed to help students understand inter-process communication (IPC) using UNIX signals. The goal is to create a simple communication system between a client and a server using only system calls like signal and kill.

## Introduction
The MiniTalk project introduces the fundamentals of inter-process communication in UNIX-like systems. By sending and receiving messages between a client and a server via signals, students gain practical experience in how processes communicate with one another without using traditional input/output methods.

## Key Concepts
1. Signals and Process Management
Learn how to send and receive UNIX signals, such as SIGUSR1 and SIGUSR2, to transfer information between processes. Understanding how to manage signals is key for handling asynchronous events in a UNIX environment.

### 2. Client-Server Communication
Implement a basic client-server model where the server waits for messages and the client sends data one bit at a time. This helps solidify the concepts of synchronous and asynchronous communication between processes.

### 3. Bitwise Operations
Understand how to use bitwise operations to convert characters into a series of signals, allowing you to transmit data between the client and server, one bit at a time.

### 4. Error Handling and Signal Reliability
Learn how to handle potential errors in signal transmission and reception, and ensure the reliability of the communication by managing signal interruptions and verifying message integrity.

### Features
Client-Server Model: Establish communication between a client and a server using UNIX signals.
Bitwise Data Transfer: Send messages bit by bit, demonstrating how to encode and decode information using bitwise operations.
Asynchronous Communication: Handle asynchronous signal-based communication, where processes do not need to block or wait for each other.
Signal Management: Use system calls like signal and kill to manage and handle UNIX signals effectively.
### Contact
For any questions or feedback, feel free to reach out to me at taoussi.aimen@gmail.com or visit my GitHub profile at GitHub.
