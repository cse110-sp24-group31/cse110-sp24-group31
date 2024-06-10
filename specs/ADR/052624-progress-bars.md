---
# These are optional elements. Feel free to remove any of them.
status: More Detail Needed
date: 2024-05-26
deciders: Newton
consulted: Nikhil, Zilin
informed: Everyone
---
# Progress Bar Functions

## Context and Problem Statement
* What progress bars will people use to track progress on their projects/tasks?
* How will each of these progress bars function?

## Considered Options

* "Check" Progress bar - **Approved**
  * Based off of task lists' "Click to Mark Complete" features. Click once to mark the task/project as complete.
  * Bar behaves like a button that only needs to be pressed once, and is disabled after pressed.
  * Design: Space Theme
    * *Progress Bar Images Will be 45x360 Pixels unless otherwise stated*
    * Incomplete tasks will display a cartoonish rocket docked on land, under a blue sky.
    * Complete tasks will show that rocket in outer space.
* "Slider" Fill Progress bar - **Rejected**
  * Bar functions as a slider with range from 0 - 100, representing the percent of completion.
  * When slider is moved to 100, the project is marked as complete.
  * Design: Space Theme
    * Idea: Rocket moving through space with fire behind the rocket. - **Approved**
  <img src="https://github.com/cse110-sp24-group31/cse110-sp24-group31/blob/main/assets/ProgressBarDemo.png" width="360" height="45">
* Automatic Fill Progress bar - **Needs Detail**
  * Bar includes a range from 0 - 100, representing the percent of completion. User is unable to directly edit the progress.
  * Bar's progress updates automatically based on an algorithm. It is undecided what this algorithm entails.
  * Design: Space Theme
    * Using the same display as the "Slider" Bar
* "Multi-Step" Progress bar - **Rejected**
  * Progress bar behaves similarly to "Check" bar, but instead of one button, there are multiple buttons divided into the different subtasks needed to complete the project.
  * Design: Space Theme
    * Shares the same Incomplete/Complete pictures as the Check bar, but split up into different parts. Each part that the user presses will become "Complete", and the project isn't considered complete until all parts are pressed and marked complete.

## Decision Outcome

Chosen option: Check and Automatic Fill bars, for simplicity and due to time constraints for implementing the project.

<!-- This is an optional element. Feel free to remove. -->
### Consequences

* Good, because it retains the most important features of the app without allocating too much time 
* Bad, because fewer features(It makes sense though since we do not have time.)

<!-- This is an optional element. Feel free to remove. -->
### Confirmation

* The "Check" bar has been implemented successfully
* More information is needed in order to begin work on the Automatic Fill Bar.

## Final Update
* Both User-Interactive progress bars have been scrapped.
 * It was decided that each project's progress should be decided by the tasks required to complete the project.
 * The project's progress will be shown as a percentage of (number of completed tasks) / (number of tasks)
 * The rocketship visual is still approved.
