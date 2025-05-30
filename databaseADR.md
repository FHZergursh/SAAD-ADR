---
# These are optional metadata elements. Feel free to remove any of them.
status: "Accepted"
date: {2024-12-5 when the decision was last updated}
decision-makers: {Flinn Hancock}
---

# Choosing a database system

## Context and Problem Statement

The program will require a database to properly store the data it will need. There are a number of potential options that would be suitable for the program. 

## Considered Options

* MySQL
* MongoDB

## Decision Outcome

Chosen option: "MongoDB", because the implementation of a NoSQL database is much more scaleable for Advanced Media Libraries

<!-- This is an optional element. Feel free to remove. -->
### Consequences

* Good, because less time will need to be spent learning the system and more time can be dedicated towards other aspects of the project.
* Bad, because SQLite is likely to be a more efifcient system in handling queries. 

<!-- This is an optional element. Feel free to remove. -->
### Confirmation

The implementation of MongoDB was successful in testing

## Pros and Cons of the Options

MySQL:
* Good, because i'm already familiar with the database.
* Good, because the apps and framework to use it are already installed on my devices.
* Bad, because XAMPP can be unreliable with my hardware on occasion.

SQLite

* Good, because it would be easier to scale  upwards than MySQL.
* Good, because it would expand my skillset by learning a new tool.
* Bad, because I would have to learn a new database system, time that could be spent developing the project.