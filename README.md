# TCP Flow Control and Congestion Control

**Student ID:** 223902048  
**Course Code:** CSE312  
**Section:** 223-D1  
**Assessment Name:** Lab Report 04 (TCP)

---

## 📌 Objective

Implement and analyze **flow control** and **congestion control** mechanisms in TCP to ensure efficient and reliable data transfer, while avoiding buffer overflow and network congestion.

---

## 🛠 Tools and Technologies

- Programming Language: C / Python (simulation)
- TCP Socket Programming / Network Simulator
- OS: Windows / Linux

---

## 🧪 Lab Overview

### 🔷 Flow Control (rwnd)

- TCP uses a sliding window based on the **Receive Window (rwnd)** advertised by the receiver.
- Ensures `LastByteSent - LastByteAcked ≤ rwnd`.
- Prevents overwhelming the receiver.

### 🔷 Congestion Control (cwnd)

- Manages how much data is sent into the network using **Congestion Window (cwnd)**.
- Includes three phases:
  - **Slow Start**: Exponential growth
  - **Congestion Avoidance**: Linear growth
  - **Fast Recovery** (TCP Reno): Handles triple duplicate ACKs

---

##
