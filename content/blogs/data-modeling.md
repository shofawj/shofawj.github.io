---
title: "Data Modeling"
date: 2023-07-23T10:35:45+07:00
draft: False
author: "Shofa Jannah"
tags:
  - Data Modeling
  - Level Data Modeling
  - Conceptual
  - Logical
  - Physical
image: /images/post.jpg
description: ""
toc: 
---

This reading is all about data modeling and the different types of data models. Data models help keep data organized and make it easier for people to understand how data is structured. Knowing the basics of data modeling helps analysts and other team members make sense of their data and use it effectively.

Important Note: As a junior data analyst, we won't be expected to create data models from scratch. However, we might encounter existing data models that our organization already uses.

### What is Data Modeling?
Data modeling is the process of creating diagrams that visually show how data is organized and structured. These visual representations are called data models. Imagine data modeling as a blueprint for a house. Just like electricians, carpenters, and plumbers use the blueprint to understand the house's structure, different users of data models have different needs but all rely on the data model to grasp the overall structure.

### Levels of Data Modeling
Data modeling has different levels of detail:
![data](/blogs/LD.png)

1. Conceptual Data Modeling: Provides a high-level view of data structure, showing how data interacts across the organization. It's like defining the business requirements for a new database without getting into technical details.
2. Logical Data Modeling: Focuses on technical details like relationships, attributes, and entities in a database. It defines how individual records are identified but doesn't include specific table names.
3. Physical Data Modeling: Depicts how a database operates and includes all entities, attributes, table names, column names, and data types used.

Here we compare these three types of data models. The table below compares the different features:

{{< table id="sample" class="bordered" data-sample=10 >}}
|Feature|Conceptual|Logical|Physical|
|------|------|------|------|
|Entity Names|v|v||
|Entity Relationships|v|v||
|Attributes||v||
|Primary Keys||v|v|
|Foreign Keys||v|v|
|Table Names|||v|
|Column Names|||v|
|Column Data Types|||v|
{{</ table >}}

### Data Modeling Techniques
There are various approaches to developing data models, but two common methods are the Entity Relationship Diagram (ERD) and the Unified Modeling Language (UML) diagram. ERDs visually show the relationship between entities in the data model. UML diagrams are more detailed, describing a system's structure, entities, attributes, operations, and relationships. As a junior data analyst, we should know about different data modeling techniques, but we'll likely use the one our organization already follows.

We can learn more about ERD, UML, and data dictionaries in this data modeling techniques article.

### Data Analysis and Data Modeling
Data modeling helps we explore the high-level details of our data and how it's related across the organization's systems. Sometimes, data analysis is required to understand how the data fits together, so we can map it effectively. Data models make it easier for everyone in our organization to understand and work with our data, which is essential for we and our team.

