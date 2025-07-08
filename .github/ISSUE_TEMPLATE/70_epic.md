---
name: Epic
about: A feature or other process spanning multiple issues and PRs
title: 'EPIC: '
type: Epic
assignees: ''
---

### Description

Write a description of the feature or process.

Typically, this includes:

* The target audience for the feature.
* The problem the feature is trying to solve.
* An overall description of the functionality of the feature. Avoid repeating contents of sections.

### Requirements

* Write requirements for the overall feature.
* In the epic description, keep these relevant to the feature at large. Put subfeature requirements in their dedicated issues.
* Requirements must be clear and unambiguous, and usually objectively evaluable.
* Good examples:
    * User can perform XYZ action via the frontend
    * Application verifies XYZ condition and provides feedback to user if necessary
    * XYZ computation is performed with 6 significant digits of precision
* More information on writing requirements: https://github.com/AeromonOy/aeromon/blob/main/dev-process.md#writing-requirements

### Tasks

* Create bullet points for tasks.
* Create issues as soon as planning converges and link them here like:
* #12345
* AeromonOy/repo-name#123
* Make the tasks concise - more than 1-2 sentences should go in the issue body and not the list.
    * If multiple nontrivial subtasks can be intuitively grouped into one issue, make them indented bullet points under the issue.
    * These nested items are not for explanation either, keep them for listing the subtasks of the issue.
* When the issue title is well-written, just `#123` suffices - GitHub will expand the title in its place.
* If useful, you can group tasks with fourth-level headers (`####`) e.g. based on inter-dependencies or scope.

### Out of scope functionality

* If some related things are out of scope for the project, include them here as bullet points.
* You can include reasoning or brief future intentions for the omission.
* If there are none, remove this section.
