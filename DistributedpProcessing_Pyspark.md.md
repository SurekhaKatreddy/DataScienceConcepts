# Advent of Bigdata - Hadoop
With the advent of big data, there arised a need to process the data in parallel. Hadoop is one such framework for distributed processing.
With master-slave architecture, the work is distributed to the worker / slave nodes by the leader / name - node. The key feature supported
by this architecture is partitioning the data across multiple nodes unlike the traditional architectures where in data is stored in one 
single node resulting in high latency.


# Throughput vs Latency

# Hadoop processing Engines - Map Reduce vs Spark

# CAP Theorom
Availability is compromised in Spark architecture

# Spark - Polyglot - supports scala, python
* In-memory computation
* Distributed processing using parallelize
* Can be used with many cluster managers (Spark, Yarn, Mesos e.t.c)
* Fault-tolerant
* Immutable
* Lazy evaluation
* Cache & persistence
* Inbuild-optimization when using DataFrames
* Supports ANSI SQL

# Pyspark - RDD vs DataFrame

# Things to remember
 * Spark is originally written in Scala
 * The main difference is pandas DataFrame’s are not distributed and run on a single node

