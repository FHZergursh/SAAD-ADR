---
# These are optional metadata elements. Feel free to remove any of them.
status: ""
date: {2024-12-09 when the decision was last updated}
decision-makers: {Flinn Hancock}
---

# {short title, representative of solved problem and found solution}

## Context and Problem Statement

Storing user information securely is an important part of the project, and it's important to prevent the theft of any information. There's a number of ways this data can be protected, deciding which ones are useful is important.

## Considered Options

* Password Hashing
* Captchas 
* Password Minimum Requirements

## Decision Outcome

Chosen option: "Hashing & Password Minimum Requirements", because the combination of the two will result in a very difficult to crack password

### Consequences

* Good, because the password will be difficult for any hackers to break the encryption on a hashed password. 
* Bad, because the password requirements may annoy users who have to create a new password to meet the requirements. 

### Confirmation

{Describe how the implementation / compliance of the ADR can/will be confirmed. Is there any automated or manual fitness function? If so, list it and explain how it is applied. Is the chosen design and its implementation in line with the decision? E.g., a design/code review or a test with a library such as ArchUnit can help validate this. Note that although we classify this element as optional, it is included in many ADRs.}