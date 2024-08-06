# How to use Git andd GitHub for collaboration

## 1. Introduction

Collaborating on writing projects using GitHub can be a powerful way to work together efficiently, track changes, and manage versions. There are two ways for authors to collaborate on content on GitHub. 

### 1.1.	Using Git and GitHub for collaboration

One way is to use Git (either by creating the content there or copying it from GitHub to the local machine) and the changes are sent to the repository on GitHub using Git. This is perhaps the most widespread method since most people use Git for version tracking and content (or code) development. It allows us to work locally, on a machine, without depending on being constantly online.

### 1.2.	Using only GitHub for collaboration

GitHub's user interface allows authors to collaborate on content development using only GitHub without any application installed on their machine. Some content creators like using Git, while others prefer making changes directly to the GitHub user interface. 

Exclusive collaboration on GitHub has two possible options depending on whether you have access to the particular repository you want to modify or not.

* Forking a repo (you do not have write access)

If you do not have write access to a repository, you must fork it to be able to modify it. By forking a repo, you make a copy of it on GitHub. You can then make changes and create a pull request to offer your modifications to be accepted by the owner of the repository.

This way, forking allows you to modify projects without affecting the original repository, also known as the "upstream" repository.

* Making direct changes as a contributor (you have write access)

If the owner of the repository invites you to collaborate on a project, you can become a contributor who can make changes directly within the repository. 

The owner of the repository can still create settings that can be used to monitor your proposed changes and the merge will only be created (the changes you offer will only be part of the repository) if the owner of the repository accepts your changes.

It is entirely up to you whether you send us the pull request related to the project via GitHub or Git installed on your machine.


## 2. Step-by-step guide : How to use Git and GitHub for collaboration?

Here is a step-by-step guide on how writers can collaborate on GitHub to create a joint project using Git:

### 2.1. Set up a GitHub repository:

You should create a new repository on GitHub. You can do this by logging into GitHub, clicking on the "+" sign in the top-right corner, and selecting "New repository." Give the repository a name, and a description, and choose whether it should be public or private.

After creating the repository, you can invite other team members to collaborate by navigating to the "Settings" tab, selecting "Manage access," and inviting collaborators via their GitHub usernames or email addresses.

If you receive an invitation, you may clone the repository and make changes on your local machine. If you accidentally found this repository and want to cooperate and develop its content, then simply fork it (make a copy of it on GitHub on your account), make changes, and create your pull request for a review. 

### 2.2.	Clone the repository:

Each team member should clone the repository to their local machine using Git. Type the following in the Git command line (use your GitHub username and the name of the newly-created repository):

**git clone https://github.com/username/repository-name.git**

### 2.3.	Create branches:

Team members should work on separate branches to avoid conflicts. Branches can be created using the git checkout -b command followed by the branch name. For example:

**git checkout -b feature-branch**

### 2.4.	Create content:

Team members can write or edit documents using their preferred text editor or word processor. Changes should be saved locally (Git clients save changes automatically).

### 2.5.	Add and commit changes:

Once changes are made, team members should add them to the staging area using the git add command followed by the file name (this step can be skipped and the commit command can also be used). For example:

**git add filename.md**

After adding changes, they should commit them to the local repository using the git commit command with a descriptive commit message. For example:

**git commit -m "Added introduction section"**

### 2.6.	Push changes to GitHub:

After committing changes locally, team members should push their branches to the GitHub repository using the git push command. For example:

**git push origin feature-branch**

### 2.7.	Create pull requests:

Once changes are pushed to GitHub, team members can create pull requests (PRs) to merge their branches into the main branch (e.g., main or master).

They can do this by navigating to the GitHub repository, selecting the "**Pull requests**" tab, and clicking on the "**New pull request**" button. After creating a pull request, they should provide a descriptive title and description, review changes, and request reviews from other team members.

### 2.8.	Review and merge pull requests:

Team members can review pull requests by examining the changes, leaving comments, and requesting modifications if necessary. Once a pull request is approved, the repository owner or a designated team member can merge it into the main branch. Merging can be done by clicking the "**Merge pull request**" button on GitHub.

### 2.9.	Resolve conflicts:

If conflicts arise during the merge process, they need to be resolved before merging the changes. Team members can resolve conflicts by editing the conflicting files, marking conflicts as resolved, and committing the changes.

### 2.10.	Continuous collaboration:

Collaboration on GitHub is an ongoing process. Team members should continue to create branches, make changes, create pull requests, review each other's work, and merge changes as needed.

By following these steps, writers can effectively collaborate on writing projects using GitHub, ensuring version control, efficient workflow, and seamless coordination among team members.
