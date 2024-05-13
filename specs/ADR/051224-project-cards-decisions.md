---
Status: Accepted
Date: 2024-05-10
Deciders: Ishan, Zilin, Liam
Consulted: Nikhil
Informed: Everyone
---

# Project Cards Setup

## Context and Problem Statement

The main homepage requires a dynamic system for managing project cards.

- Each project card on the main homepage should contain the following features:
  - Users should be able to open project details
  - Users should be able to add a new project card
  - Users should be able to delete existing project cards
  - Users should be able to edit the information displayed by the project cards

## Considered Options

1. **Use static HTML and CSS**
   - Pros: Simple to implement, easy to do.
   - Cons: Does not support interactive features or real-time updates.
2. **Use JavaScript to create new project-card elements**
   - Pros: Highly dynamic, supports real-time updates and interactive features.
   - Cons: Requires more complex coding and testing.
3. **Use React to inject project-card elements**
   - Pros: Supports component-based architecture and state management.
   - Cons: Overhead of including a library and learning curve.
4. **Use Web Components for encapsulation**
   - Pros: Encapsulates functionality and styling.
   - Cons: Steep learning curve.

## Decision Outcome & Justification

Chosen option: Use JavaScript to create new project-card elements because it balances dynamic interaction capabilities with relative ease of implementation and maintenance.

- The decision leverages JavaScript's flexibility to manipulate the DOM in real-time.
- JavaScript is familiar to the team, reducing the learning curve and speeding up development.

### Consequences

- **Positive**: Enhances user interaction by allowing dynamic addition, removal, and editing of project cards directly on the homepage.
- **Positive**: Facilitates real-time updates to project details without needing to reload the page, improving user experience.
- **Negative**: Increases complexity in code management. Developers must handle DOM manipulation carefully to avoid performance bottlenecks.


