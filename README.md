# PUSGS-2-Electric-Boogaloo

## Commits and PRs
  * Each feature has it's own branch, derived from the develop branch.
  * **Everything we merge should be merged with develop**.
  * I've created Git Hooks, that will force us to use a prefix for commits:
    * PSG - denotes the project.
    * 123 - number corresponding to a feature.
    E.g. "PSG-123: Some useful commit message"
  * Each PR should consist of a prefix along with the name of the ticket we're working on.
  * PR's can be merged when 2 people review the PR and approve of it.

## Branching strategy
Each branch is derived from **develop**.
To create a branch for a feature, type in the following:
```
$ git checkout develop
$ git branch <branch-name> // branch has to named with the same convention as mentioned above, E.g. PSG-123, where the number denotes the ticket number
```
If the corresponding ticket needs a subticket, when creating a branch, derive the branch from the parent branch, the same as you would for a ticket.

Made by Marko