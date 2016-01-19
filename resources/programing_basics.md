编程基本  
========  


## languages

http://blog.rust-lang.org/  
https://github.com/rui314/8cc  可以当做学习编译器技术的材料  
https://github.com/JuliaLang/julia  
https://kotlinlang.org/ Kotlin 

**How We Spent Two Days Making Perl Faster**  
http://blog.booking.com/making-perl-faster.html  

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

### ifps  

http://ipfs.io/  
IPFS is a new hypermedia distribution protocol, addressed by content and identities. IPFS enables the creation of completely distributed applications. It aims to make the web faster, safer, and more open. IPFS is an open source project developed by the team at Interplanetary Networks and many contributors from the open source community.

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

**Swap Two Variables Without Using a Temp Variable (With Math!)**  
http://chris-taylor.github.io/blog/2013/02/25/xor-trick/  

## 协同 

together.js  

## 架构

**林仕鼎 - 系统架构领域的一些学习材料**  
http://qing.blog.sina.com.cn/2244218960/85c41050330031zq.html  
系统架构是一个工程和研究相结合的领域，既注重实践又依赖理论指导，入门容易但精通很难，有时候还要讲点悟性，很具有“伪科学”的特征。要在此领域进阶，除了要不断设计并搭建实际系统，也要注意方法论和设计理念的学习和提炼。经常有同学询问如何学习，特贴一篇学习材料，供大家参考。

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

## 软件工程  

**The Failure of Agile**  
http://blog.toolshed.com/2015/05/the-failure-of-agile.html  
I am proud to be one of the 17 founders/authors of the The Agile Manifesto back in 2001. I think it provided a jolt of energy, hope of a better way of doing things, of creating software and making the world work better. It was a pivotal turning point. But in the 14 years since then, we‘ve lost our way.

**构建之法**  
http://book.douban.com/subject/25965995/  
非常优秀的一本软件工程书籍。如果你是一名技术管理人员 or 项目经理，这本书有助于你系统化的总结和提炼过往经验，并查漏补缺，结合书中的微软最佳实践，找到目前仍在困扰你的一些疑难杂症的解决思路，从而让你的团队战斗力更强、效率更高，更有底气地支撑业务研发和创新。如果你是一名互联网行业的产品经理，这本书讲有助于让你了解工程师团队的思维、工作模式以及苦衷，从而帮助你有效地和研发团队打交道，让产品高效高质量的落地。

**Software Design and Implementation**  
https://www.cs.duke.edu/courses/fall15/cps108/resources/  
杜克大学的软件设计与实现教材。

**Introduction to Microservices**  
http://nginx.com/blog/introduction-to-microservices/  
This is a guest post by Chris Richardson. Chris is the founder of the original CloudFoundry.com, an early Java PaaS (Platform-as-a-Service) for Amazon EC2. He now consults with organizations to improve how they develop and deploy applications. He also blogs regularly about microservices at http://microservices.io.

**Organizational Skills Beat Algorithmic Wizardry**  
http://prog21.dadgum.com/177.html  
Organizing complexity is the most important skill in software development http://www.johndcook.com/blog/2015/06/18/most-important-skill-in-software/  

## OO

https://www.sics.se/~joe/bluetail/vol1/v1_oo.html  