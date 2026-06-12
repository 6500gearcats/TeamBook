# Git and GitHub

This section is for students who are new to source control.

`Git` is the tool that tracks changes to files over time.
`GitHub` is the website where our team stores and reviews code.

You do not need to know every Git command to get started.
You do need to understand what problem Git solves and how to work without overwriting other people's changes.

## Our team GitHub

Our team has multiple repositories from different projects and competitions.
You can find our repos here:

- GearCats GitHub organization: <https://github.com/6500gearcats>

## Why we use it

Git and GitHub help the team:

- Keep a history of code changes
- Work on the same project without passing files around
- Review changes before they are merged
- Recover from mistakes more easily

## Basic terms

- `repository`: a project folder tracked by Git
- `commit`: a saved checkpoint of changes
- `branch`: a separate line of work for a new change
- `pull request`: a request to review and merge changes into the main branch
- `merge`: combining approved changes back into the main branch

## What students should learn first

Start with these ideas:

1. A repository contains the team project and its history.
2. You should make changes on your own branch, not directly on the main branch.
3. Small commits are easier to review than one huge commit.
4. A pull request lets other people review your work before it is merged.

## Basic workflow

1. Clone a repository to your computer.
   `git clone https://github.com/6500gearcats/TeamBook.git`
2. Create a new branch for your change.
   `git checkout -b your-branch-name`
3. Make a small change and commit it.
   `git add .`
   `git commit -m "Describe your change"`
4. Push your branch to GitHub.
   `git push -u origin your-branch-name`
5. Open a pull request.
   Open your branch on GitHub and click `Compare & pull request`.
6. Get feedback and make updates if needed.
   `git add .`
   `git commit -m "Address review feedback"`
   `git push`
7. Merge after the change is reviewed and approved.
   Use the `Merge pull request` button on GitHub.


## Resources
Cheatsheet: <https://education.github.com/git-cheat-sheet-education.pdf>

