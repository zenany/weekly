编程基本  
========  


## 消息协议

### The Remote Framebuffer Protocol  
https://tools.ietf.org/html/rfc6143  
RFB ("remote framebuffer") is a simple protocol for remote access to
graphical user interfaces that allows a client to view and control a
window system on another computer.  Because it works at the
framebuffer level, RFB is applicable to all windowing systems and
applications.  This document describes the protocol used to
communicate between an RFB client and RFB server.  RFB is the
protocol used in VNC.

### MQTT  
http://mqtt.org/  
MQTT is a machine-to-machine (M2M)/"Internet of Things" connectivity protocol. It was designed as an extremely lightweight publish/subscribe messaging transport. It is useful for connections with remote locations where a small code footprint is required and/or network bandwidth is at a premium. For example, it has been used in sensors communicating to a broker via satellite link, over occasional dial-up connections with healthcare providers, and in a range of home automation and small device scenarios. 

### WAMP  
http://wamp.ws/  
WAMP is an open standard WebSocket subprotocol that provides two application messaging patterns in one unified protocol:
Remote Procedure Calls + Publish & Subscribe.

### STOMP  
http://stomp.github.io/  
TOMP is the Simple (or Streaming) Text Orientated Messaging Protocol. STOMP provides an interoperable wire format so that STOMP clients can communicate with any STOMP message broker to provide easy and widespread messaging interoperability among many languages, platforms and brokers.


## 数据结构

**Open Data Structures**  
http://opendatastructures.org/  
Open Data Structures covers the implementation and analysis of data structures for sequences (lists), queues, priority queues, unordered dictionaries, ordered dictionaries, and graphs. Data structures presented in the book include stacks, queues, deques, and lists implemented as arrays and linked-lists; space-efficient implementations of lists; skip lists; hash tables and hash codes; binary search trees including treaps, scapegoat trees, and red-black trees; integer searching structures including binary tries, x-fast tries, and y-fast tries; heaps, including implicit binary heaps and randomized meldable heaps; graphs, including adjacency matrix and ajacency list representations; and B-trees. The data structures in this book are all fast, practical, and have provably good running times. All data structures are rigorously analyzed and implemented in Java and C++. The Java implementations implement the corresponding interfaces in the Java Collections Framework. 