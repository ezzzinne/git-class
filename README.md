
# git-class

## Version Control

**Version control**, also known as source control, is the practice of tracking and managing changes to files. It is a system that records changes to a file or set of files over time so that specific versions can be recalled later.

## Difference between Git and GitHub

**Git** is a version control system that allows developers manage and track changes in their source code history while **GitHub** is a cloud-based hosting service for managing git repositories.

## Alternatives to GitHub

1. **GitLab**
2. **Bitbucket**
3. **Azure DevOps**

## Difference between `git fetch` and `git pull`

The **`git pull`** command can copy changes from a remote repository directly into your working directory and also to your local git repository while the **`git fetch`** command only copies changes into your local git repository.

## Git rebase

The **`git rebase`** command allows developers to easily change a series of commits, modifying the history of the repository. Developers can reorder, edit, or squash commits together. **`git rebase`** is typically used to: 
1. Edit previous commit messages.
2. Combine multiple commits into one (squash).
3. Delete or revert commits that are no longer necessary. 
The **command** is: `git rebase main`

## Git cherry-pick

The **`git cherry-pick`** command is a command that lets developers copy a specific commit from one branch and apply it to another branch.
The **command** is: `git cherry-pick<commit-hash>`
