---
status: "completed, potentially bugged"
date: {2024-06-11}
deciders: {Nikhil, Brian, Ishan, Zilin, Newton}
informed: {everyone}
---
# Final Progress Bar Status Report

## Context and Problem Statement

Needed a simple way for users to track progress on their projects.

## Considered Options

* Option 1 - A progress bar that the user presses once to mark the project as complete. Recommended for projects whose progress can't be broken down in a simple way.
  * Declined, as this is covered by the third option.
* Option 2 - A slider progress bar that the user drags to self-report how much progress they believe they have.
  * Declined, as the group agreed that tying progress to completed tasks would be more helpful in breaking down what needs to be done within the project.
* Option 3 - A progress bar that fills automatically based on user-inputted "tasks" that need to be completed for the project.
  * Approved, as this keeps the functionality simple while also helping the user remember what needs to be done and track their progress more carefully.

## Decision Outcome

Chosen option: "Option 3", because this keeps the functionality simple while also helping the user remember what needs to be done and track their progress more carefully.

### Explanation of Feature
When the user creates a project, the progress bar will show up defaulted at 0%.<br>
<img src="https://github.com/cse110-sp24-group31/cse110-sp24-group31/blob/main/assets/ProgressBar-Doc-img1.png" width="280" height="300">

The user clicks "View", then adds tasks and marks them complete.<br>
<img src="https://github.com/cse110-sp24-group31/cse110-sp24-group31/blob/main/assets/ProgressBar-Doc-img2.png" width="280" height="300">

The progress bar updates according to the (# of completed tasks)/(# of total tasks)<br>
<img src="https://github.com/cse110-sp24-group31/cse110-sp24-group31/blob/main/assets/ProgressBar-Doc-img3.png" width="280" height="300">
