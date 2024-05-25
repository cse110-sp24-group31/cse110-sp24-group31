---
Status: Accepted
Date: 2024-05-24
Deciders: Kevin
Consulted: Nikhil, Charlotte
Informed: Everyone
---

# Contacts Page Setup 

## Context and Problem Statement

Need to create a contacts page that can contain all relevent information with a nice space theme and some customization.
- Each information section should contain the following information:
  - name
  - gender
  - category
  - relevent links
  - other information

## Considered Options

1.Simple just have it display a list of things similar to a do list but with the information segmented:
  - Pros: Would be simple to implement and would look decent
  - Cons: would be hard to relegate into the theme, might be too basic, very fundamental

2. Just Create a simple form at the top that allows user input and put it into boxes.
  - Pros: A bit more thematic should allow for things like coloring to have a more visually appealing page.
  - Cons: Still sort of basic, users might not like how clumped information can look and the simple grid like perspective might not be the cleanest.

3.Create planets where information with a sun form at the top:
 - Pros: Fits the theme in a really cool way with a good way to fit in an information in a planet-like circle
 - Cons: Much more difficult to implement with constant changes needing to happen when wanting more information, size of planets, etc.

## Decision Outcome & Justification

Chosen option: Create planets where information with a sun form at the top with javascript alowing for editing of boxes, and a dynamic set of entries with planets to place in the space.

- This really well aligns with the theme in which a Sun can be the center of the universe of contacts with each planet being their own person.
- Allows for easy integration with alien figure head to allow for things like categories.
- ALl information is sepearate and distinct with another allowing for a clean appearance.

### Consequences

- **Positive**: Looks really cool, has a nice theme that is useful throughout the entire process and aligns with the rest of the application.
- **Positive**: Everything is really well spaced out where information can be clearly seen at the end, with full re-customization abilities with ediitng.
- **Negative**: Due to how much information is fit into a sphere each sphere takes up a lot of space so the display doesn't actually have much information that can fit on the screen.
- **Negative**: If someone isn't really interested in space the theme can seem like a bit of a drag as the information could be a lot more easily conveyed when looking at a contacts page.
