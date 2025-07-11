---
name: Feature request
about: I wish to see new functionality or a change to existing functionality
title: ''
type: Feature
assignees: ''
---

### Description

Write a description of the feature you're looking for. Avoid duplicating the content from the sections below.

Typically, this includes:

* The target audience for the feature.
* The problem the feature is trying to solve.
* A description of the functionality of the feature, with a level of detail suitable to the level of planning already done.

If this change doesn't add new functionality, please use the **Code refactor** or **Documentation update** templates as applicable.

### Requirements

* Write requirements for the change.
* Requirements must be clear and unambiguous, and usually objectively evaluable.
* Good examples:
    * User can perform XYZ action via the frontend
    * Application verifies XYZ condition and provides feedback to user if necessary
    * XYZ computation is performed with 6 significant digits of precision
* More information on writing requirements: https://github.com/AeromonOy/aeromon/blob/main/dev-process.md#writing-requirements

### Acceptance criteria

The change is accepted when it fulfills the requirements listed above and has been verified by:

* [ ] Field team member(s)
* [ ] Data analysis team member(s)
* [ ] Other development team member(s)
* [ ] Changes the laboratory information management system, requires validation **(describe validation steps below)**
* [ ] Changes the laboratory information management system, validation passed **(describe validation results below)**
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
