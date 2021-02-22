+++
title = "Big Data"
outputs = ["Reveal"]
weight = 3

+++

{{% reveal-titlepage figure="/dsacapstone-resources/images/bigdata/bigdata.jpg" %}}

---

## Performance and scalability

{{% fragment %}} How much data do you work with? {{% /fragment %}}

{{% fragment %}} What happens if your data doubles in size tomorrow? {{% /fragment %}}

{{% fragment %}} Is your system scalable? {{% /fragment %}} 

{{% fragment %}} How performant is your system? {{% /fragment %}} 

---

## How to achieve performance and scalability

{{% fragment %}} <p align='left'> * Storage </p> {{% /fragment %}}

{{% fragment %}} <p align='left'> * Algorithms </p> {{% /fragment %}}


---

### Tools for big data

{{% fragment %}} Tools for working with a distributed file system:{{% /fragment %}}

{{% fragment %}} **Hadoop**

* Apache Hadoop is the most prominent and used tool in big data industry with its enormous capability of large-scale processing data. 

* Open source framework and runs in an existing data center or on a cloud infrastructure. 

* Hadoop consists of four parts: 

-- Hadoop Distributed File System or HDFS, it is a distributed file system compatible with very high scale bandwidth.
-- MapReduce: A programming model for processing big data.
-- YARN: It is a platform used for managing and scheduling Hadoop’s resources in Hadoop infrastructure.
-- Libraries: To help other modules to work with Hadoop.
{{% /fragment %}}

---

### Tools for big data

{{% fragment %}} **Spark**

* Apache Spark Spark can handle both batch data and real-time data. 

* As Spark does in-memory data processing, it processes data much faster than traditional disk processing. 

* Apache Spark is flexible to work with HDFS as well as with other data stores, for example with OpenStack Swift or Apache Cassandra.  

* Spark is an alternative to Hadoop’s MapReduce. Spark can run jobs 100 times faster than Hadoop’s MapReduce. 
{{% /fragment %}}

[Top 10 Open Source Big Data Tools in 2020](https://www.whizlabs.com/blog/big-data-tools/)

---

### Tools for big data

Other tools: 

{{% fragment %}}  **Gluster**

GlusterFS is a scalable network filesystem suitable for data-intensive tasks such as cloud storage and media streaming. 

GlusterFS is free and open source software and can utilize common off-the-shelf hardware

[Gluster](https://docs.gluster.org/en/latest/)

{{% /fragment %}}

{{% fragment %}} **Google Big Table** {{% /fragment %}}

{{% fragment %}} **Google Big Query** {{% /fragment %}}

---

### Algorithms for Big Data

Many, in many categories: classification, regression, SVMs, neural networks, etc.

**How do you run your scripts? On a single machine or on multiple machines?**

**Can you parallelize?**



