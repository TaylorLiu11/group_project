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
#### Cloning
In this project that we are demonstrating, we are only using the cloning method. Since this is a simulation of a team working together to build up a project, we chose to use the cloning.

Cloning is for **internal collaboration**, which allows us to implement branch creation and management efficiently.

#### Forking
On the other hand, if it is an **open-source project** that welcomes people from everywhere to be a contributor, then that's the scenario for using forking method.

Because that project owners don't usually grant write access to everyone, it is a standard workflow to use fork for open-source projects. Forking allows the owner of the project to better track and verify the changes to the original files.


### Branching strategies (feature branches, development branches)
In this project, we have created a main branch, a develop branch, and branches named "feature/[name]" and "docs/[name]".
Our idea:
1. `Main` branch is fore the real release (production environment) after checking there's no problem at all in develop branch.
2. `Develop` branch is the middle place where all people merge their own feature or docs branches, and verify if there's no other conflicts or issues after solving merge conflicts.
3. The `feature/[name]` and `docs/[name]` branches are for each group member to work on their own parts of the project. The "feature" is for adding more information in the  file we created for a real world development scenario simulation, and the "docs" is for editing the "README.md" file for the documentation of the project.


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
Git and GitHub are useful because they allow the users to track the code changes, and perform sharing and collaborating on code. They are like a time machines, when there is something wrong in the process of developing, the users can utilize Git to simply just revert to the last version that was still correct.

Git and GitHub also help in working on different features simultaneously, whether there is only one or multiple developers. By creating branches, it is clear to see what this change is for, and thus more convenient in developing.


### Intro of Our Project Scenario
Our team built this project to simulate a professional setting of real-world collaboration using Git and GitHub. The main purpose of our project is **to establish the foundational knowledge in implementing Git commands, branching, committing, merging, and pull requests.** That's why we are only using non-coding example file to avoid creating more obstacles to ourselves.

The process:

1. We first have the `main` branch. This is only for the official release (production version), where everything has been checked working correctly.
2. The second branch we have is the `develop` branch. This is the branch that we use as a base to work together and merge with. Starting from this branch, we opened branches for each person to build on their own parts.
3. Each group member created branches named `feature/[name]` for simulating the features, and later on creating pull requests to be successfully merge to develop branch.
4. As for our documentation, we implemented the same concept with branches named `docs/[name]`, and did the pull requests and merging procedures.


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




### Common Challenges and Troubleshooting Techniques
#### Understanding Git and GitHub
The biggest challenge we faced is actually not the technical problems, but to understand and digest the workflow of using Git and GitHub. It is still hard to imagine how this process can be applied to a real-world project.

To address this, some members watched several YouTube tutorials, some used AI tools to help in better comprehension. We also learned by trying to ask questions like:

1. Why do we use this command here?
2. What's the purpose of using Git and GitHub?
3. In what kind of real-world cases do we implement the process?

#### Memorization of the Commands
Another challenge we faced is not able to memorize the commands such as `git add`, `git pull`, or `git switch`, etc. Each time before use we checked again how the commands look like, and are we doing each step correctly.

The is just a small issue due to insufficient practice of using Git. So to address this problem, we did more practices on walking through the process. It is very helpful to try to recall the commands or the usage, before looking up the answers on AI.

#### Credential
There is also one big hard challenge that we faced in **credential** issue, as Cotton's laptop kept getting **"github permission denied 403"** issue when she tried to do `git push`.

This credential problem happened because git does not have our credential at the first time we want to make a push, therefore we need to go to GitHub and generate token:

1. Go to GitHub Account.
2. Click on the profile photo in the top-right corner and select `Settings`.
3. Scroll down and click `< > Developer settings` button.
4. Click on `Personal access tokens` and give the token a name to generate token.

