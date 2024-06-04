---
Status: Accepted
Date: 2024-05-24
Deciders: Charlotte, Nikhil
Consulted: Nikhil, Charlotte, Zhami
Informed: Entire team
---

# Calendar Setup 

## Context and Problem Statement

Needed a method of keeping self organize journal and create easy reference points. Keeping track of the days was also an essential in terms of tracking deadlines or due dates. 

## Considered Options

A calendar was a fully encompassing solution to this issue. However we had a few ideas on how to implement.

1. The first idea was to link to a seperate page which would have entires for each day. The pro of this idea was that it would be extremely easy to visualize all the necessary information and keep track of everything. The con was that this moved essential information of the home page, which would be a detraction for the general user looking to utilize our product.
2. The other idea was to shrink the calendar and remove the notes from the direct view of the user, but maintain the location on the main page. The tradeoff we made was to create a popup window which would take the journal entry in and store it by title. To access the notes, the user would have to click on a dropdown.

## Decision Outcome & Justification

Chosen option: Keep the calendar on the main page and use a dropdown option to view the notes.

- This strongly improve the initial view of the homescreen, where the user has access to all features on one page. Furthermore to keep track of the exact date and utilize the calendar for more than just notes, its location on the main page is pivotal. Considering that the notes could be opened with a simple button click, we thought this tradeoff was optimal for the end users.

### Consequences

- **Positive**: Allows user to see days and avoid lag of loading another webpage.
- **Positive**: Utilizes the space on the homepage better to create a more appealing website, staying competitive with other products
- **Negative**: User does not have immediate access to notes for a certain day when they click a date (still extremely quick)

### More information

Due a time constraint, we were forced to drop the edit feature of each entry. This means that when a user saves a journal entry for a specific date, they will be unable to change it. This is a feature we would like to implement if we have the time, but have currently left as whatever the user saves being final. However they can add as many notes as they want and delete them, so if an edit were truely wanted to be made, there are still workarounds.
