# 8. Using GitHub exclusively – Forking - Step-by-step Guide

In this article, we show step by step how to fork a repository. The process will have two participants: the repository admin (me) and a GitHub user (Test-Collaborator-1) who does not have write access to the repository called Test-Forking.

## 1.	The owner of the repo creates a new repo for testing purposes

To demonstrate the forking workflow, I created a new repo called ‘Test-Forking’:

![](http://hdoc.csirt-tooling.org/uploads/upload_b37e4423ac44986e44e6c68751a1fac4.png)

Then I created a Markdown file and for testing purposes, I wrote a pancake recipe:

![](http://hdoc.csirt-tooling.org/uploads/upload_6fd808622c94e30483803d920813ffb6.png)

I committed my changes so the file appeared on the main page of the Test-Forking repository:

![](http://hdoc.csirt-tooling.org/uploads/upload_440d4723449fa32c98b0d3c808ce2132.png)

## 2. The test user (Test-Collaborator-1) finds my repo

I created a second account so I could test the workflow. Let me switch to this account (Test-Collaborator-1). This user has not created any repositories yet:

![](http://hdoc.csirt-tooling.org/uploads/upload_f402b24815819dbf04d2251906262f1c.png)

Let’s assume that the user Test-Collaborator-1 is searching for a pancake-related repository on GitHub, and finds the one I just created. 

![](http://hdoc.csirt-tooling.org/uploads/upload_58fd4dda9eb01edcfaa4ff82e0ac34ca.png)

## 3. The test user (Test-Collaborator-1) forks my repo

Test-Collaborator-1 user opens the Pancake.md file and decides to fork the repo. The repo has not been forked yet by anyone (0 forks can be seen in the above screenshot). 

Forking is straightforward: the test user clicks either on the ‘Fork’ link or on the down-pointing arrow and chooses the ‘+ Create a new fork’ link.

![](http://hdoc.csirt-tooling.org/uploads/upload_15c1d74d9ddf9b9cf9270485298c9c45.png)

Either way, the following screen appears:

![](http://hdoc.csirt-tooling.org/uploads/upload_f93d1e968234d70a0baea3c08cb4ba24.png)

The screen informs the test user (Test-Collaborator-1) that the ‘Test-Forking’ repository name is available. Certainly, the test user can rename it and also change the description of the repository.

The test user can also choose not to copy the main branch (this is the default option) but the whole repository. Since the upstream repository (the original repo the test user is forking now) has only a readme file and a pancake.md file and only a main branch, removing the checkmark from the checkbox in front of the option (copy the main branch only) does not make any difference.

If the test user does not want to make any further changes, the test user should click on the ‘Create fork’ button.

The next screen informs the test user that the repo has been forked and the forked repo is up to date with the original repo’s main branch.

![](http://hdoc.csirt-tooling.org/uploads/upload_885b56ba491c43ce31baea4e3e57a351.png)

## 4. The test user (Test-Collaborator-1) makes changes on the forked repo

Now, the test user can make the changes without affecting the original repository. The test user opens the pancake.md file and makes the changes (by clicking on the pencil icon and getting into the editing mode).

In the ‘Ingredients’ section, the test user uses bullet points instead of a hard-to-read list whereas in the ‘Instructions’ section the test user uses a numbered list instead of bullet points (because the order of the steps is important).

![](http://hdoc.csirt-tooling.org/uploads/upload_1ebe48e8a65dd66e8d3bdb1e48278ca0.png)

Before committing the changes, the test user clicks on the ‘Preview’ button at the top of the editor and visually checks the changes:

![](http://hdoc.csirt-tooling.org/uploads/upload_099f3e35fb7b571fde9ba27278399c0d.png)

## 5. The test user (Test-Collaborator-1) commits the changes and creates a pull request

The test user thinks that everything is correct, so commits the changes. Once the commit is made, the test user goes to the ‘Pull requests’ tab and clicks on the button ‘New pull request’:

![](http://hdoc.csirt-tooling.org/uploads/upload_b2d312303e71c905ae3ec97a75607c64.png)

On the ‘Comparing changes’ screen, the test user can compare the changes (between the original and the forked version). As per GitHub, the merge is possible (there are no merge conflicts).

![](http://hdoc.csirt-tooling.org/uploads/upload_f6711f58c0b898029f089e3e448a7b8e.png)

Since there are no merge conflicts, the test user can click on the ‘Create pull request’ button. On the open pull request screen, the test user can add a description (what the test user changed and why).

![](http://hdoc.csirt-tooling.org/uploads/upload_e1ef2769d043f0f27fb3b8fc3838fcfc.png)

The last step for the test user is to click on the ‘Create pull request’ button. With this action, the test user proposes changes for the admin of the repo from where the forking was made.

## 6. The owner of the repo checks the pull request

Let me switch the account and log in as the owner of the Test-Forking repo (the repo which was forked by the test user).

At the top of the screen, I can see that there is a new pull request (the ‘Pull requests’ tab shows the number of new pull requests).

Once I navigate to the Pull requests screen, I can see additional information about the proposed changes (who proposes changes and regarding which file: proposed changes to the Pancake recipe by Test-Collaborator-1).

![](http://hdoc.csirt-tooling.org/uploads/upload_50c003a41cb326549cc15154194b21c8.png)

By clicking on the ‘Proposed changes to the Pancake recipe’ link, I can read the commit message of the test user. The example below clearly shows why it is important to write a concise and easy-to-understand commit message, as we can help the repository owners work with this.

The repository owners can more easily and quickly understand where and what changes have taken place and, therefore, can more easily decide whether these changes are legitimate or not.

![](http://hdoc.csirt-tooling.org/uploads/upload_a5f4e49880696bf434916ce821c19f4c.png)

Since the commit message is straightforward, I can easily decide whether the changes will improve the quality of the content of my repository. There are no merge conflicts, the proposed changes are good, so I merge the pull request into my repo.

So first, let’s click on the ‘Merge pull request’ button in the lower left-hand corner:

![](http://hdoc.csirt-tooling.org/uploads/upload_0a2fc066caaf66dc7c1e87cc40c0e7f8.png)

Then I should confirm the merge.

![](http://hdoc.csirt-tooling.org/uploads/upload_22308f60bc2f6dfea61527d76b55df47.png)

I can check the changes by clicking on the ‘Code’ tab 

![](http://hdoc.csirt-tooling.org/uploads/upload_68c42fea822ee40b775f7bcc10336971.png)

and by clicking on the Preview button I can see the content of the file:

![](http://hdoc.csirt-tooling.org/uploads/upload_a72f5927f8e5d0aa416c8421d53dc516.png)

The file has been updated, and the content improved, so I am satisfied with the changes.

Please note that this process is an iterative one: if a new change is made then the process should be accomplished again.
