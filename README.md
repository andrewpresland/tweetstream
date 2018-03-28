# Tweet analysis with reactive realtime streams  
Spark, Akka, Cassandra and Kafka are four of the five members of a stack known by the acronym SMACK. When combined with the fith member, Mesos, they provide a complete opensource Big Data platform. This project demonstates how they can be used to construct reactive streams to construct a realtime tweet analyisis pipeline providing sentiment and hashtag analysis.

## Kafka
Kafka is a distributed horizontally scaleable and fault-tolerant Message Broker used for building realtime data pipelines and streaming applications with large data volumes. Because Kafka partitions data and saves it in an Append-Only-Log it can handle Terabytes of data without impact on performance.

## Akka
Akka is an implementation of the Actor model that allows the construction of highly distributed reactive applications. Combining with Scala as the development language many useful aspects of functional programming can leveraged to proivide concise solutions. Since Akka 2.4 REST services are also supported.

## Spark
Spark is an open-source cluster computing framework. Spark supports batch-processing and stream-processing (micro-batch) and allows Lamba architectures to be efficiently implemented since the Stream and Batch APIs are the same and single data-logic implementation can be used for both. Sparks Scala API is highly performant so that applications built on Akka and Spark can be develoope with the same tools and philisophy. It supports all relevant NoSQL and SQL solutions. 

## Cassandra
Cassandra is a column-oriented databank that is distributed, linearly scaleable to the number of machines in the computing cluster. Cassandras integrates seamlessly with Spark so that distributed operations can be executed local to the data. This data-locality means that IO operations are minimized and the CPUs only process data found locally on disk. 
