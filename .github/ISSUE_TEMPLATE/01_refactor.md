---
name: Code refactor
about: I wish to see a code change that doesn't affect functionality
title: ''
type: Refactor
labels: refactor
assignees: ''
---

### Description

Write a description of the change you're looking for. Avoid duplicating the content from the sections below.

Typically, this includes:

* The problem the refactor is trying to solve.
* A description of the refactor steps, with a level of detail suitable to the level of planning already done.

### Requirements

* Write requirements for the change.
* Requirements must be clear and unambiguous, and usually objectively evaluable.
* Good examples:
    * XYZ dependency is replaced with ABC
    * Performance of XYZ improves noticeably
    * XYZ condition is still checked
    * XYZ computation produces the same results within float accuracy
* More information on writing requirements: https://github.com/AeromonOy/aeromon/blob/main/dev-process.md#writing-requirements

### Acceptance criteria

The change is accepted when it fulfills the requirements listed above and has been verified by:

* [ ] Field team member(s)
* [ ] Data analysis team member(s)
* [ ] Other development team member(s)
* [ ] Other: **(please specify)**

### Documentation needs

Choose one, and elaborate if necessary. For projects not in production use, this section can be removed.

* [ ] No user-facing changes are expected that require explicitly informing users
* [ ] User-facing changes are expected and must be adequately documented in: **(describe where)**

### Handling of previous versions

Choose all that apply, and elaborate if necessary. This can be copied from the issue description, if it's already filled in. For projects not in production use, this section can be removed.

* [ ] This change will unconditionally replace the current production version and does not require further considerations
* [ ] This change will require manual action beyond deployment, such as recomputation of existing results **(describe below)**
* [ ] This change will require special deployment considerations, such as firmware upgrades across a fleet of devices **(describe below)**
* [ ] This change is intended to be used in parallel with previous versions **(describe below)**
* [ ] This change will require other deployment considerations **(describe below)**
* [ ] Deployment considerations are currently unknown
