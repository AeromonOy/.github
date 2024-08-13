### Description

Write a description of the pull request contents. This includes at least:

* Issue(s) resolved (using the syntax "Fixes #123" or "Closes #123")
    * If no issue exists, include a sufficient description of the bug or feature.
* A summary of the changes made in this PR.
    * Can often look something like this for simple changes: "Fixes #123 by frobnicating the frontend API widget."
    * Make sure to mention **ALL** nontrivial changes, to avoid unrelated breakages.
* If you made any non-trivial design decisions, you can include short justifications here, so the reviewer doesn't need to ask.

### Documentation needs

Choose at least one, and elaborate if necessary. For projects not in production use, this section can be removed.

* [ ] No user-facing changes that require explicitly informing users
* [ ] User-facing changes are adequately documented in documentation included in this change
* [ ] User-facing changes are adequately documented in external documentation: **(describe where)**

### Handling of previous versions

Choose all that apply, and elaborate if necessary. This can be copied from the issue description, if it's already filled in. For projects not in production use, this section can be removed.

* [ ] This change will unconditionally replace the current production version and does not require further considerations
* [ ] This change will require manual action beyond deployment, such as recomputation of existing results **(describe below)**
* [ ] This change will require special deployment considerations, such as firmware upgrades across a fleet of devices **(describe below)**
* [ ] This change is intended to be used in parallel with previous versions **(describe below)**
* [ ] This change will require other deployment considerations **(describe below)**
