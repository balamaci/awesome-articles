# Curated lists of articles on different IT topics

- [Java](#java)
    - [Java8](#java8)
    - [Logging](#logging)
    - [Threads and Concurency](#threads-and-concurency)
    - [Maven](#maven)
    - [Debugging](#debugging)
    - [Caching](#caching)
    - [Bytecode manipulation](#bytecode-manipulation)
    - [General](#general)
    - [NIO](#nio)
    - [JMX](#jmx)
    - [Generics](#generics)
- [Software Patterns & Design](#patterns)    
    - [General](#general)
    - [SOLID Principles](#solid)
- [Docker](#docker)
    - [Compose](#compose)
    - [Networking](#docker-networking)
- [DBs](#database)
    - [Connection pools](#ancients)
    - [JPA](#jpa)
    - [JTA](#jta)
- [GIT](#git)
- [Distributed systems](#distributed-systems)
- [Linux](#linux)
    - [General](#linux-general-stuff)
    - [Security](#security)
- [Machine Learning](#machine-learning)
    
    
# Java    

## Java8

* [Java 8 Features](http://winterbe.com/posts/2014/03/16/java-8-tutorial/) - High level explainations of the features in Java8
* [Java 8 Collectors](http://codingjunkie.net/guava-and-java8-collectors/) - Java8 Collector and Streams explained by implementing Guava Multimap collector
* [CompletableFuture](https://www.youtube.com/watch?v=-MBPQ7NIL_Y) - Video on CompletableFuture


## Logging
 * [Java Logging Basics](https://www.loggly.com/ultimate-guide/java-logging-basics/) - Loggers, Appenders, Layouts explained
 * [Logback](https://dzone.com/articles/logback-configuration-using-xml) - Logback config


## Threads and Concurency
* [Handling InterruptedException](http://www.ibm.com/developerworks/library/j-jtp05236/) - Handling InterruptedException
* [Thread Interruption](https://dzone.com/articles/understanding-thread-interruption-in-java) - How to interrupt threads in Java  
* [Executor Service](http://www.baeldung.com/java-executor-service-tutorial) - ExecutorService explained
* [Thread Pools](http://jvns.ca/blog/2016/03/27/thread-pools-how-do-i-use-them/) - ExecutorService perils
* [Executor Service 10 tips&tricks](http://www.nurkiewicz.com/2014/11/executorservice-10-tips-and-tricks.html) - Executor Service 10 tips&tricks
* [Analyze Thread dumps](https://dzone.com/articles/how-analyze-java-thread-dumps) and [How to read a Thread dump](https://dzone.com/articles/how-to-read-a-thread-dump)- Threads explained, what are the thread states and how to analyze thread dumps.
* [Solving a real problem](http://www.nurkiewicz.com/2016/10/small-scale-stream-processing-kata-part.html) - Solving a real complex problem with a step by step guide and the reason behind it.

## Maven
 * [Maven Profiles](http://www.petrikainulainen.net/programming/tips-and-tricks/creating-profile-specific-configuration-files-with-maven/) - Maven Profiles
 * [Maven cheatsheet](https://zeroturnaround.com/rebellabs/maven-cheat-sheet/)
 * [Maven scopes explained](http://howtodoinjava.com/maven/maven-dependency-scopes/)

## Debugging
 * [JVM Internals](http://www.cubrid.org/blog/dev-platform/understanding-jvm-internals/) - Classloader, JVM bytecode internals   

## Caching
 * [JCache API](https://dzone.com/refcardz/java-caching) - Refcard for JCache API and generic terms explained

## Bytecode Manipulation

* [Annotation-driven Java runtime code generation](http://zeroturnaround.com/rebellabs/how-my-new-friend-byte-buddy-enables-annotation-driven-java-runtime-code-generation) - Using ByteBuddy to generated code at runtime

## General
 * [Handling InterruptedException](http://www.ibm.com/developerworks/library/j-jtp05236/) - Handling InterruptedException

## NIO
 * [NIO Socker Selector Channel](http://www.baeldung.com/java-nio-selector) - Using NIO Socker Selector instead of one-thread-per-connection approach
 * [Video Series simple thread per connection to a full NIO server](http://www.javaspecialists.eu/tutorials/006.01-Transmogrifier-Java-NIO-and-Non-Blocking-IO--Introduction.html) - Excellent video Series starting from a simple thread per connection to a full NIO server, going through a deep  explanation of Executors. Done by Dr. Heinz Kabutz.

## JMX
 * [All the thing you can do with JMX](https://www.ctheu.com/2017/02/14/all-the-things-we-can-do-with-jmx/)

## Generics
 * [Generics interview](http://www.baeldung.com/java-generics-interview-questions)

# Software Patterns & Design
* [Github patterns repository](https://github.com/iluwatar/java-design-patterns) - Implementation and explanation of the most common design patterns.
* [Patterns with Java8](https://www.youtube.com/watch?v=-k2X7guaArU) - Patterns re-analised and implemented with Java8
* [Decorator with Lambda](http://www.javaadvent.com/2015/12/decorator-design-pattern-using-lambdas.html) - Decorator Design Pattern using lambdas

## SOLID
* [SOLID](https://dzone.com/articles/the-solid-principles-in-real-life) - SOLID explained
* [SOLID](https://android.jlelse.eu/solid-principles-the-definitive-guide-75e30a284dea#.7hx1anwdd) - Another article on SOLID 

# Docker
* [Practical Tips](http://www.smartjava.org/content/10-practical-docker-tips-day-day-docker-usage) - Docker tips

## Docker networking
* [Docker Networking official](https://docs.docker.com/engine/userguide/networking/dockernetworks/) - Docker networking
* [Docker Networking explained](https://medium.com/@joatmon08/container-networking-faq-for-the-developer-63a295cd3f9e#.9swmzefln)

# DBs

## Connection Pools


## JPA
* [JPA Native query](http://www.thoughts-on-java.org/jpa-native-queries/) - JPA native query
* [JPA Auditing](http://www.baeldung.com/database-auditing-jpa) - JPA Auditing of entities - track createdBy, creationDate, lastUpdateDate
* [JPA Locks](http://vladmihalcea.com/2015/01/12/a-beginners-guide-to-java-persistence-locking/) - JPA entities Locking concept 

## JTA
* [JTA with Spring](https://spring.io/blog/2016/11/30/spring-tips-jta)

# Git
* [Git tips](http://www.alexkras.com/19-git-tips-for-everyday-use/) - Git Tips
* [Git flow](https://danielkummer.github.io/git-flow-cheatsheet/) - Git flow visual chart

# Distributed systems 
* [Distributed Log - Kafka](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying) - Kafka distributed log concept explained.

# Linux
## Linux general stuff
* [Commands glosary](http://cb.vu/unixtoolbox.xhtml) - List of Linux commands helpful for solving specific problems. 
* [Cron](https://sanctum.geek.nz/arabesque/cron-best-practices/) - Crontab best practices
* [SSH](https://blog.logentries.com/2016/06/ssh-from-the-ground-up/) - Explains ssh keys, ssh-agent, ssh tunnels and proxy, etc.
* [Memory Management](https://www.ibm.com/developerworks/library/j-nativememory-linux/) - Indepth guide about memory management in Linux and relation with Java allocation.
* [Memory consumption](https://jvns.ca/blog/2016/12/03/how-much-memory-is-my-process-using-/) - Memory consumption Linux
* [Understanding syscalls](https://d0hnuts.com/2016/12/21/basics-of-making-a-rootkit-from-syscall-to-hook/) - [Advanced] - understanding syscalls by writting a rootkit
* [Linux network commands](https://likegeeks.com/linux-network-commands/)
* [iptables commands](https://dzone.com/articles/linux-iptables-firewall-simplified-examples)

## Security
* [Linux network commands](https://likegeeks.com/linux-network-commands/)
* [Basic Security](http://blog.mailgun.com/security-guide-basic-infrastructure-security/) - Basic infrastructure security, SSH, IPTABLES
* [Linux Security Tricks](https://dzone.com/articles/useful-linux-security-tricks-to-harden-your-system) - Another post on securing your servers.
* [SSH Best practices](https://blog.0xbadc0de.be/archives/300) - SSH best practices
* [Log management](https://dzone.com/articles/linux-syslog-server-and-log-management)

# Machine learning

* [Using neural nets to recognize handwritten digits](http://neuralnetworksanddeeplearning.com/chap1.html) - Hands-on intro to neural networks, actually a chapter in the free online book [NeuralNetworks and DeepLearning](http://neuralnetworksanddeeplearning.com)
* [Practical introuction to deep learning](http://adilmoujahid.com/posts/2016/06/introduction-deep-learning-python-caffe/) 
* [NeuralNets](http://deeplearning4j.org/neuralnet-overview.html) - Intro to neural nets and deep learning from the **dl4j** library.
* [Matrix calculus required for DL](http://explained.ai/matrix-calculus/index.html)
* [Washington University DL course](https://github.com/jeffheaton/t81_558_deep_learning)
* [Convolutional Neural Networks for Visual Recognition](https://cs231n.github.io/)
