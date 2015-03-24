编程基本  
========  


## languages

http://blog.rust-lang.org/  
https://github.com/rui314/8cc  可以当做学习编译器技术的材料

## Interface Design 

### HTTP API Design Guide  
https://github.com/interagent/http-api-design  
This guide describes a set of HTTP+JSON API design practices, originally extracted from work on the Heroku Platform API. This guide informs additions to that API and also guides new internal APIs at Heroku. We hope it’s also of interest to API designers outside of Heroku. Our goals here are consistency and focusing on business logic while avoiding design bikeshedding. We’re looking for a good, consistent, well-documented way to design APIs, not necessarily the only/ideal way. We assume you’re familiar with the basics of HTTP+JSON APIs and won’t cover all of the fundamentals of those in this guide.

##  arch

**Adopting Microservices at Netflix: Lessons for Architectural Design**  
http://nginx.com/blog/microservices-at-netflix-architectural-best-practices/  

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

**Algorithms**  
https://github.com/arnauddri/algorithms  
Classic algorithms and data structures implemented in Go. Not for production use, it is mostly an attempt to get comfortable both with Go and key CS concepts.  

## 协同 

together.js  

## 架构

**架构师的四种兵器**  
http://mp.weixin.qq.com/s?__biz=MTEwNTM0ODI0MQ==&mid=204102619&idx=1&sn=baa51b5437a25ce994c801e6454f4b21  
作者结合自己的经验，从这几方面进行了总结：  
- KISS
- Architect vs Gardener
- Hard Skill and Soft Skill
- Technology Meaning
架构是一个综合问题，文末总结的这段相当不错：“一将无能，累死三军。”往往因为架构师对知识广度或深度不够，导致技术选型不当。前瞻性不够，导致拆拆补补。问题分析不够，导致舍本逐末。大量的从后期呈现出来的现象和结果，往往都是因为架构师在前期的考虑不足导致的。有时候架构师会质疑：这是建设的问题，没有按照规范执行。这是运营的问题，运营处理不及时。这是机房环境的问题。甚至说这是天灾、这是人祸。但我们相信，这都是您需要考虑的问题。

**首席技术官：CTO是做什么的**  
http://www.tuluobo.com/2015/01/17/207.html  
这三个CTO的使命总结得相当不错：
- 为长期的技术战略负责：确保公司在动态演变和高度竞争的空间中继续拥有最好的技术产品，使公司的商业战略和技术战略齐头并进。
- 技术专员：鼓舞（震撼）人们从长远眼光看公司，以及说服外界这是世界发展的方向，他/她的公司是带他/她来这里的最佳的选择。
- 工程师的精神领袖和技术文化的拥护者：团结工程师组织迈向公司的长期技术目标，鼓舞新的工程师加入工程师组织，帮助设定和拥护技术文化，确保公司能继续留住并吸引顶尖技术人才