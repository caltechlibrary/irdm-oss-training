# Day 4: Advanced Repository Hygiene

## Morning: Advanced Git & GitHub

* 9:00 AM – 10:15 AM — Git History Visualization & Submodules
    * Visualizing complex repository histories and commit trees with graphical interfaces like `gitk`.
    * Managing Git submodules in large software projects.
* 10:15 – 11:15 PM — Interactive Rebasing
    * Mastering `git rebase -i` to squash intermediate commits, reword commit messages, and clean branch history.
    * Cherry-picking and other advanced Git history operations.
    * Adhering to InvenioRDM commit standards (linear, atomic, properly formatted commits) required by core maintainers.
* 11:15 – 12:00 PM — Pull requests
  * how to combine everything from the past 2 days of Git education into a pull request

## Lunch, provided: 12 - 1pm

## Afternoon: Testing & Deploying

HOW CHANGES FLOW INTO DOWNSTREAM PROJECTS -- HOW CHANGES YOU MAKE EVENTUALLY GETS MERGED, RELEASED, ARCHIVED

* 1:00 – 2:15 PM — Software Testing
  * Writing unit and integration tests for Python/Flask web applications.
* 2:15 – 3:15 PM — Continuous Integration (CI/CD) Pipelines
  * Setting up local `pre-commit` hooks for automatic linting.
  * Configuring GitHub Actions workflow YAML files to execute automated test suites.
* 3:15 - 3:45 PM — Coffee/tea Break
* 3:45 – 4:30 PM — Releases on GitHub with Zenodo Integration
  * Concept of releases and preparing for a release.
  * Linking GitHub repository releases to Zenodo via `invenio-vcs` for automatic long-term software archiving and DOI minting.
* 4:30 – 5:00 PM — 