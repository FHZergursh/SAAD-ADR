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

## Pros and Cons of the Options

Password Hashing

<!-- This is an optional element. Feel free to remove. -->
{example | description | pointer to more information | …}

* Good, because {argument a}
* Good, because {argument b}
<!-- use "neutral" if the given argument weights neither for good nor bad -->
* Neutral, because {argument c}
* Bad, because {argument d}
* … <!-- numbers of pros and cons can vary -->

Captchas

{example | description | pointer to more information | …}

* Good, because {argument a}
* Good, because {argument b}
* Neutral, because {argument c}
* Bad, because {argument d}
* …

Password Minimum Requirements

{example | description | pointer to more information | …}

* Good, because {argument a}
* Good, because {argument b}
* Neutral, because {argument c}
* Bad, because {argument d}
* …

<!-- This is an optional element. Feel free to remove. -->
## More Information

{You might want to provide additional evidence/confidence for the decision outcome here and/or document the team agreement on the decision and/or define when/how this decision the decision should be realized and if/when it should be re-visited. Links to other decisions and resources might appear here as well.}