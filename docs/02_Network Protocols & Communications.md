# 02 — Network Protocols

## What is Data Communication?
Data communication is the exchange of data between two nodes using a transmission medium (e.g., cable, wireless).

---

## Data Flow Modes

- **Simplex**
  - Communication is unidirectional.
  - One device transmits, the other only receives.
  - *Example:* Keyboard → Monitor (traditional).

- **Half Duplex**
  - Communication is bidirectional, but only one side at a time.
  - *Example:* Walkie-Talkies.

- **Full Duplex**
  - Communication is bidirectional simultaneously.
  - Both devices can send and receive at the same time.
  - *Example:* Telephone line.

---

## Protocols (Rules of Communication)
All communication systems require:
1. **Source (Sender)**
2. **Destination (Receiver)**
3. **Channel (Transmission Medium)**
4. **Rules (Protocols)** → govern how communication happens
"""

## Protocols 
Protocol = Rule.

it is a set of rule that govern data communication
Protocol Determines:
What is Communicated?
How it is Communicated?
When it is Communicated?

## Protocols - Network Communications
Protocols used in network communications also define:
-> Message Encoding
-> Message formatting and encapsulation
-> Message Size
-> Message Timing
-> message Delivery options

## Elements of a Protocol
1: Message Encoding
2: Message formatting and encapsulation
3: Message Size
4: Message Timing
5: Message Delivery Options


1: Message Encoding -> Message(Source) ->Transmitter -> Transmission(Medium) -> Receiver -> Decoder(Signal) -> Message(Destination)

2: Message formatting and encapsulation: It encapsulates source and destination information to correctly identify the sender and the receiver, ensuring that the data reaches the intended recipient without errors.

3: Message Size -> Human Break long messages into smaller parts or sentances long messages must also be broken into smaller pieces to travel across a network

4: Message Timing -> Flow Control , Response Timeout.

5: Message Delivery Options -> There are 3 Delivery Options.
1: Unicast -> the sender is sending the data to excatly one reciver in the network
2: Multicast -> the sender is sending the data to set of reciver not to all is called multicast.
3: Broadcast -> the sender is sending the data to all the particepents in the network is called broadcast.



# what is  Peer-To-Peer Network?
No centralized administration.
All Peers are equal.
Simple Sharing applications.
Not Scalable.

# Client Server Network ?
centralized administration.
Request-Response model.
Scalable.
Server may be overloaded.