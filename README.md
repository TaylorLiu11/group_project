# group_project
This is a project on how to use git and GitHub.

## Practical Workflow Demonstration
### Git Commands


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


### Submitting and reviewing pull requests


## What we learned
### What is Git/GitHub?


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

