---
# These are optional elements. Feel free to remove any of them.
status: '{proposed}'
date: { 2024-05-12 }
deciders: { ishan, zilin, liam }
consulted: { nikhil }
informed: { everyone }
---

# project cards setup

## Context and Problem Statement

- each project card should fulfill the following requirements:
  - button to open to project details
  - respond to changes in project
  - can add new project card
  - can delete existing project card
  - can edit elements contained in project card and update the data of project accordingly

* … <!-- numbers of drivers can vary -->

## Considered Options

- use static HTML CSS
- use JS to create new project-card element
- Use react to inject project-card element
- … <!-- numbers of options can vary -->

## Decision Outcome

Chosen option: "use JS to create new project-card element", because
it allows dynamic change of element within the allowed framework

<!-- This is an optional element. Feel free to remove. -->

### Consequences

- Good, because it does the job
- Bad, because you need to generate all HTML elements by JS

### use static HTML CSS

- Good, because it is simple
- Good, because it is sensible
- Bad, because it is hard to duplicate
