---
# These are optional metadata elements. Feel free to remove any of them.
status: "Accepted"
date: {2024-12-9}
decision-makers: {Flinn Hancock}
---

# {short title, representative of solved problem and found solution}

## Context and Problem Statement

There's a number of ways that the application can be structured. Deciding on which one is best is important to make sure the right choice is being made

## Considered Options

* Monolithic Application
* Microservices Application

## Decision Outcome

Chosen option: "Monolithic", because it is faster to create and deploy, which is significant with the dev time available. 

### Consequences

* Good, because the application will be functional quicker than Microservices and much more secure thanks to being centralised instead of spread out. 
* Bad, because the application will be more difficult to scale up, which is important for AML to keep up with user demands. 

### Confirmation

The construction of a monolithic application is something I have prior experience with, so it should be more than do-able to implement. 

## Pros and Cons of the Options

Monolithic:
* Good, because building the application will be a faster process under Monolithic, which will help meet the deadline.
* Good, because data stored on the single application will be more secure than data stored through microservices.
* Bad, because it hampers scaleability, making it harder to meet the needs of more users. 

Microservices:
* Good, because it will be able to scale up to meet AML's increasing user demand. 
* Good, because if any part runs into an error or gets disabled, the rest of the application will still be able to run without it
* Bad, because it is more complicated to implement, test and maintain than monolithic applications