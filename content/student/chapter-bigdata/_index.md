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

### Scrum Framework

**People are the focus of Scrum.**

{{% fragment %}} **Scrum Teams** include people with diverse skillsets; each team has all of the capabilities necessary to deliver a piece of functionality from idea to delivery. {{% /fragment %}}

{{% fragment %}} **Sprint** is a short (one to four weeks long) timeframe during which the team works on some chunks of the product. 
{{% /fragment %}}

---

### Scrum Team

Scrum Team includes three roles: **Scrum Master, Product Owner, and Development Team**. 

{{% fragment %}} The **Scrum Master** helps the Scrum Team perform at their highest level. They also protect the team from both internal and external distractions. Scrum Masters hold the Scrum Team accountable to their working agreements, Scrum values, and to the Scrum framework itself.
{{% /fragment %}}

{{% fragment %}} The **Product Owner** defines the what--as in what the product will look like and what features it should contain. Product Owner helps build and clarify the product backlog and ensures that everyone knows the priorities.
{{% /fragment %}}

{{% fragment %}} The **Development Team** decides how to accomplish the work set forth by the Product Owner. Development Teams are structured and empowered to organize and manage their own work.
{{% /fragment %}}
 
---

### Sprint

{{% fragment %}} **Sprint** is a short (one to four weeks long) timeframe during which the team works on some chunks of the product. 
{{% /fragment %}}

{{% fragment %}} * Each sprint begins with a plan followed by building and then testing the code, and ends with a review of the work completed and an additional review of the way in which the team worked together (retrospectives). 
{{% /fragment %}}

{{% fragment %}} * During each sprint, the team completes one or more increments of the project. Each completed increment must be fully tested and fully approved by the end of the sprint (potentially deliverable).{{% /fragment %}}

 {{< figure src="/dsacapstone-resources/images/scrum/sprint.png" width=500 >}}
 
 
---

### Scrum Values

{{% fragment %}} **Commitment**: Scrum teams work together as a unit, members trust each other to follow through on what they say they are going to do. 
{{% /fragment %}}

{{% fragment %}} **Courage**: Scrum teams must feel safe enough to say no, to ask for help, and to try new things. 
{{% /fragment %}}

{{% fragment %}} **Focus**: It means that whatever Scrum teams start they finish. 
{{% /fragment %}}

{{% fragment %}} **Openness**: Scrum teams consistently seek out new ideas and opportunities to learn. 
{{% /fragment %}}

{{% fragment %}} **Respect**: Scrum team members respect each other’s ideas, give each other permission to have a bad day once in a while, and recognize each other’s accomplishments. They show respect to one another, to the product owner, to stakeholders, and to the ScrumMaster. 
{{% /fragment %}}

---

### Scrum Artifacts

{{% fragment %}} The **Product Backlog** is an ordered list of everything that is known to be needed in a product. 
{{% /fragment %}}

{{% fragment %}} The **Sprint Backlog** is a list of everything that the team commits to achieve in a given Sprint. Once created, no one can add to the Sprint Backlog except the Development Team. If an item needs to be dropped from the Sprint Backlog, they must negotiate it with the Product Owner. 
{{% /fragment %}}

{{% fragment %}} At the end of every Sprint, the team must complete a **potentially releasable product increment** meaning that it is done as agreed upon. 
{{% /fragment %}}

---

{{< slide class="side-by-side" >}}

### Tracking Progress

**Burndown Chart** Sprint burndowns are a graphical way of showing how much work is remaining in the sprint, typically in terms of task hours.
As the work progresses, the amount of work remaining should steadily decrease and should trend toward being complete on the last day of the sprint. 

{{% fragment %}} {{< figure src="/dsacapstone-resources/images/scrum/sprintburndownchart.png" height=270 >}} 
 {{< figure src="/dsacapstone-resources/images/scrum/sprintburndownchartstudents.png" height=270 >}} {{% /fragment %}}

---

### Daily Scrum

<div style="width: 50%; margin-left: auto; margin-right: auto;">
{{< youtube kKIc1NFO-AU >}}
</div>
    
---

### Daily Scrum

What do you see in the clip?

{{% fragment %}} * **Scrum Team** 
Members stand up in circle facing everyone. Also, someone else just "observing". Meeting is less than 15 minutes long. 
{{% /fragment %}} 

{{% fragment %}} * **Scrum Master** 
Scrum Master starts the meeting. Makes sure everyone talks in order from left to right. 
{{% /fragment %}}

{{% fragment %}} * Each member answers to **3 questions** regarding meeting the sprint goal: 
{{% /fragment %}}

{{% fragment %}}       1. What did I worked on since last meeting? 
{{% /fragment %}}

{{% fragment %}}       2. What I am working on now? 
{{% /fragment %}}

{{% fragment %}}       3. Do I see any impediments? 
{{% /fragment %}}

