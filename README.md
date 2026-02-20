# group_project
This is a project on how to use git and GitHub.

## Practical Workflow Demonstration
### Git Commands
Commands are text instructions that you give to Git to perform specific actions.

Think of commands like: telling Git exactly what to do.

In Git, every command starts with the word git, followed by an action

git init: Initializes a new local repository to start tracking a project.

git clone: Creates a local copy of a project that already exists on GitHub.

git status: Shows which files have been modified and what is ready to be saved.

git add: Moves changes to the "Staging Area" to prepare them for a save.

git commit -m "...": Permanently saves the staged changes with a descriptive message.

git push: Uploads your local saves to the shared repository on GitHub.

git pull: Fetches and merges updates from your teammates into your local computer.

### Cloning v.s. Forking repositories


### Branching strategies (feature branches, development branches)


### Creating and resolving pull requests


### Submitting and reviewing pull requests
**Part 1: Submitting a Pull Request**
A Pull Request is how you propose changes to a repository. It lets other able to review your code before merging it.

Step 1: Create a New Branch

*Using terminal:*

[git checkout -b feature/your-feature-name]

*Make changes, then:*

[git add

git commit -m "Add new feature"

git push origin feature/your-feature-name]

*Make sure:*

Never work directly on **main**

Step 2: Create the Pull Request on GitHub

Go to the repository on GitHub

Click "Compare & Pull request" (appears after push) or Click Pull Requests tab

Click New pull request

*Make sure:*

Base (a base ref) → main

Compare (a head ref) → feature/your-feature-name




## What we learned
### What is Git/GitHub?

#### Git is a version control system.

Git is a local tool that tracks changes in your code over time.
It acts like a "save game" system. Git allows you to revert to a previous working version.

It helps you:
- Track changes in your files over time
- Save different versions of your project
- Go back to previous versions if something breaks
- Work safely without losing your work
- Collaborate with other people

Think of Git like: a history tracker for your project.

#### Github is a cloud platform that hosts Git repositories.

It allows you to:

- Store your code online
- Collaborate with others
- Share projects
- Backup your work
- Contribute to team projects

Think of GitHub like: Google Drive for code, powered by Git

### Our Group Experience

### Why Git and GitHub are Useful Tools


### Intro of Our Project Scenario


### The Significance of Each Step


### Common Challenges and Troubleshooting Techniques
During login validation GitHub not allow you to use any password so you require to create key on your GitHub that allow to access GitHub connection