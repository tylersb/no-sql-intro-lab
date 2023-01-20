![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)

# NoSQL Research Lab

## Explainer

Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

## Questions:

1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?

Non-relational database

1. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 
Document databases offer a variety of advantages, including:


An intuitive data model that is fast and easy for developers to work with.
A flexible schema that allows for the data model to evolve as application needs change.
The ability to horizontally scale out.
Because of these advantages, document databases are general-purpose databases that can be used in a variety of use cases and industries.

Document databases are considered to be non-relational (or NoSQL) databases. Instead of storing data in fixed rows and columns, document databases use flexible documents. Document databases are the most popular alternative to tabular, relational databases. Learn more about NoSQL databases.

1. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vs SQL?



1. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 

SQL table with users, colums - ID, Username, Email, Password

Mongo: 
{
  ID: 1,
  Name: "name",
  Email: "email",
  Password: "pass"
}

1. What is an example situation where a non-relational database makes more sense versus a relational db?

Document databases are general-purpose databases that serve a variety of use cases for both transactional and analytical applications:

Single view or data hub
Customer data management and personalization
Internet of Things (IoT) and time-series data
Product catalogs and content management
Payment processing
Mobile apps
Mainframe offload
Operational analytics
Real-time analytics

1. What are the benefits of SQL databases? NoSQL Databases?

Document databases have many strengths:

The document model is ubiquitous, intuitive, and enables rapid software development.
The flexible schema allows for the data model to change as an application's requirements change.
Document databases have rich APIs and query languages that allow developers to easily interact with their data.
Document databases are distributed (allowing for horizontal scaling as well as global data distribution) and resilient.
These strengths make document databases an excellent choice for a general-purpose database.

A common weakness that people cite about document databases is that many do not support multi-document ACID transactions. We estimate that 80%-90% of applications that leverage the document model will not need to use multi-document transactions.

Note that some document databases like MongoDB support multi-document ACID transactions.

Visit What are ACID Transactions? to learn more about how the document model mostly eliminates the need for multi-document transactions and how MongoDB supports transactions in the rare cases where they are needed.

1. Explain the differences between ACID and BASE models.



## Visual Comparisons

### Structure

![](https://media.git.generalassemb.ly/user/16103/files/65db7f00-afd5-11ea-926a-e51b2fd2be08)

### Relationships

![](https://media.git.generalassemb.ly/user/16103/files/5eb47100-afd5-11ea-8cae-0a65c924be4b)

### Use Cases

![](https://media.git.generalassemb.ly/user/16103/files/7f7cc680-afd5-11ea-82c8-10ed74ee2222)

## Additional Readings

Pick an additional reading to go through with a classmate. Reflect on how the
article changes the discussion. What have you learned?

  _**Note:** You do not have to read about the different types of SQL and NoSQL. We will use PostgreSQL and MongoDB in this course._
- [ACID vs. BASE Explained](https://neo4j.com/blog/acid-vs-base-consistency-models-explained/)
- [PostgreSQL Use Cases](https://www.cybertec-postgresql.com/en/postgresql-overview/solutions-who-uses-postgresql/)
- [MongoDB Use Cases](https://www.mongodb.com/use-cases)
- [What the heck are you actually using NoSQL for?](http://highscalability.com/blog/2010/12/6/what-the-heck-are-you-actually-using-nosql-for.html)
- [A co-Relational Model of Data for Large Shared Data Banks](http://queue.acm.org/detail.cfm?id=1961297&repost)
- [A brief history of databases](http://avant.org/media/history-of-databases)
- [NoSQL Databases: An Overview | ThoughtWorks](http://www.thoughtworks.com/insights/blog/nosql-databases-overview)
- [When to choose CouchDB vs RDBMS?](http://stackoverflow.com/a/2731207/402618)
- [CAP Twelve Years Later: How the "Rules" Have Changed](http://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed)
