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
A Pull Request is a method to ask to merge a user's changes into another branch in Git.
First, a user makes a new branch from the main branch. A user does his or her work in that branch so the main branch remains safe and unchanged.
After finishing his or her work, a user commits his or her changes and pushes the branch to the remote repository.
Then, a user creates a Pull Request. In the Pull Request, a user explains what he or she changed and why he or she made that changes. This enables other team members to read a user's code, leave comments, or request improvements. If they request changes, a user can fix the code in the same branch and push again. The Pull Request will update automatically.
When everyone agrees that the code is correct, the Pull Request is merged into the main branch. After merging, the feature branch will be usually deleted.
In short, a Pull Request is a safe way to review and merge code in a team.

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

Step 3: Fill Out PR Details

*Include:*

Clear title

What you changed

Why you changed it

**Part 2: Reviewing a Pull Request**

As a collaborator or reviewer:

Step 1: Open the Pull Requests

Repository → Pull Requests → Click the Pull Request

Step 2: Review the Code

Click Files changed tab.

Step 3: Submit Review

Click Review changes (top right)

**Part 3: Making Changes After Review**

If changes are requested:

* Makes edits locally
* Commit again:

[git add

git commit -m "Fix requested changes"

git push]

**Part 4: Merging a Pull Request**

Once approved

+ Click **Merge Pull request**

+ Confirm merge

+ Optionally delete the branch


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
1.Git Commands

Git commands are instructions a user use to manage changes in his or her code.

git init begins a new Git repository.

git clone makes copies of an existing repository to a use's computer.

git add prepares changes to be saved.

git commit saves a snapshot of a user's changes.

git push uploads your changes to a remote repository.

git pull downloads the latest changes from a remote repository.

Each commands helps you track, save, and share your work safely.

2.Cloning vs. Forking Repositories

Cloning is about copying a repository to  a user's local computer so that he or she can work on it. It connects to the original repository.

Forking means making a user's own copy of someone else's repository on GitHub (or another platform). It enables him or her to make changes without affecting the original project.

In short, clonig is for working locally, and forking is for contributing to projects a user doesn't own.

3.Branching Strategies

Branching means making separate versions of a user's code to work on new features or fixes.

A common strategy is:
Maintaining main (or master) stable.
Creating a new branch for each feature or bug fix.
Merge the branch back into main when it is ready.
Branching keeps the main code safe while a user experiments or develops new features.

4.Creating and Resolving Pull Requests

A pull request (PR) is a request to merge a user's branch into another branch.

Creating a PR:
Push a user's branch. Open a pull request. Describe what a user changed.

Resolving a PR:
Review comments. Fix issues if needed. Merge the branch after approval.

Pull requests enables teamwork and code review before changes become official.

5.Submitting and Reviewing Pull Requests

Submitting a pull request is about asking others to check a user's work before merging it.

Reviewing a pull request means reading the code changes, checking for mistakes, making suggestions for improvements, and approving of or requesting changes.

This process makes code quality better and helps teams collaborate very effectively. 



**Create a Repository**

GitHub repository = central storage for your project

*Significance:*

+ Acts as the main project folder online

+ Keep all files organized

+ Tracks every activities that has been made

+ Allows collaboration

**Clone the Repository**

*Significance:*

+ Creates a local copy on your computer

+ Lets you work offline

+ Connects your computer to the remote repository

**Create a Branch**

*Significance:*

+ Lets you work independently

+ Prevents breaking the main project

+ Allow multiple team members to work at the same time

**Add/ Stage Changes**

*Significance:*

+ Selects which changes you want to save

+ Prepares files for recording

**Commit Changes**

*Significance:*

+ Saves a snapshot of your work

+ Creates a clear history

+ Allow tracking who changed what and when

**Push to GitHub**

*Significance:*

+ Uploads your work to GitHub

+ Shares changes with teammates

+ Backs up your work online

**Create a Pull Request**

*Significance:*

+ Requests to merge your work into the main branch

+ Allows review and discussion

+ Reduces errors

**Merge**

*Significance:*

+ Combines your experiment with the main project

+ Updates the final version

**Pull Updates**

*Significance:*

+ Syncs your local copy with the latest version

+ Prevents conflicts

### Common Challenges and Troubleshooting Techniques
