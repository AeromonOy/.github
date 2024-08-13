---
name: Bug report
about: Something isn't working as it should
title: ''
labels: bug
assignees: ''
---

### Description

Write a brief description of the issue you've hit.

Avoid duplicating the content from the sections below - typically this fits on one line.

### Steps for reproducing

1. If possible, write clear steps for reproducing the issue.
2. Steps may include, among other things, any specific accounts or resources that reproduce the issue.
3. Please also test the steps yourself, if possible.
4. At minimum, note down what you did when experiencing the issue.

### Expected behavior

Describe what behavior you expected from the application.

### Observed behavior

Describe the behavior you actually observed. Screenshots or error tracebacks also belong here.

### Requirements

* If there are any extra requirements for the bug fix, write them here. Otherwise, you can remove this section.
* Requirements must be clear and unambiguous, and usually objectively evaluable.
* In particular, **DO NOT** just duplicate "Expected behavior" here.
* Good examples:
    * Current behavior must be available with a flag (for XYZ reason)
    * Migration created to update incorrect data caused by this
* More information on writing requirements: https://github.com/AeromonOy/aeromon/blob/main/dev-process.md#writing-requirements

### Acceptance criteria

The change is accepted when it fulfills the requirements listed above and the issue has been verified to be fixed by:

* [ ] Issue reporter
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

### Additional information

This section can include e.g. additional screenshots. Keep the information clearly useful, or remove this section
if it's unnecessary.
