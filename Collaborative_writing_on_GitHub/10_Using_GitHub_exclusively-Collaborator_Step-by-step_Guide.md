# 10. Using GitHub exclusively – Collaborator - Step-by-step Guide

In this section, you can read a detailed, step-by-step guide about how to use only GitHub for collaboration. To demonstrate this, I created a new user called ‘Test-Collaborator-1’ and invited this user to collaborate and make a suggestion to improve a fictional piece of content. "Collaborator" is a specific status in Github. We use the word in line with the status as it is defined by Github.

In this section, I will mostly speak in the first person singular to show what and how I did to make this article as simple and easy to follow as possible.

## 1.	Create a repository

First, I logged in to my GitHub account, navigated to the repositories tab, and clicked on "New" to create a new repository.

![](http://hdoc.csirt-tooling.org/uploads/upload_2a675e0c3b85639f00262a58e89b6c00.png)

I filled in the necessary details such as the repository name, and its description, and chose to make it public. 

![](http://hdoc.csirt-tooling.org/uploads/upload_c35c84cd939f79f7e585abc983db2c0c.png)

I chose to add a README file to my repository but I did not want to create a gitignore file or choose a license yet. 

![](http://hdoc.csirt-tooling.org/uploads/upload_0c8bdf50a38b4ea85d89632167031302.png)

Once everything was set, I clicked on the ‘Create repository’ button in the lower right-hand corner of the screen, so the repository is now created:

![](http://hdoc.csirt-tooling.org/uploads/upload_1f36b701991c714a24b7400e8bdcb24c.png)

When creating joint projects, it is worth agreeing at the beginning regarding the creation of repositories, and which settings (for example, under which license) should be used to create them.

It’s also important to define in advance a naming convention for files and folders, to ensure consistency. One key aspect is to avoid using spaces in filenames. Hyphens or underlined characters should be preferred.

## 2.	Invite a collaborator

As the repository owner, I could invite collaborators by navigating to the repository's settings (1), then selecting the ‘Collaborators’ link on the left panel (2), and finally, clicking on the ‘Add people’ button in the lower part of the main screen. 

![](http://hdoc.csirt-tooling.org/uploads/upload_04a33603f563379f4850c99180cc1c97.png)

At the top of the screen, you can change the settings of your public repository. On the right, you can see how many collaborators the repository has.

![](http://hdoc.csirt-tooling.org/uploads/upload_7bc9a6f6d94a0c20820c06ce98ecc343.png)

You can add a collaborator to your repository by searching for the collaborator’s GitHub username, full name, or email address.

![](http://hdoc.csirt-tooling.org/uploads/upload_3e17fc9797807f3040073748aa738121.png)

As I stated at the beginning of this section, I created a test user ‘Test-Collaborator-1’ to demonstrate this process. By typing the name of the test user, the fields were populated:

![](http://hdoc.csirt-tooling.org/uploads/upload_1550f59ec01774451f8180e2be0c0bde.png)

I hovered my mouse over the test user’s avatar so the field became highlighted. Then I clicked on the avatar. The collaborator became highlighted:

![](http://hdoc.csirt-tooling.org/uploads/upload_0edbe0ea241803397135338f9ebfe19d.png)

As the final step, I clicked on the ‘Add Test-Collaborator-1 to this repository’ button. 

![](http://hdoc.csirt-tooling.org/uploads/upload_49c6ee31f2822b4add05bfd5f9db7aa6.png)

Then I was redirected back to the settings page of my repository. In the ‘Manage access’ field I could invite further collaborators (by clicking on the ‘Add people’ button) if I wanted to.

![](http://hdoc.csirt-tooling.org/uploads/upload_bc391f763f4e0362915131d60894becc.png)

The invite was sent to the ‘Test-Collaborator-1’. You can see its status (Pending invite). You can also revoke your invitation simply by clicking on the ‘Remove’ button (which becomes active if you hover your mouse over it:![](http://hdoc.csirt-tooling.org/uploads/upload_fda957c9b440183f86d61c1db58edebd.png)).

## 3.	The collaborator’s workflow

**Let’s log in to the account of ‘Test-Collaborator-1’:**

Once I logged in as the GitHub user named Test-Collaborator-1, I saw on the Dashboard that there was an unread notification (The user Test-Collaborator-1 also received an email message about the invitation).

![](http://hdoc.csirt-tooling.org/uploads/upload_fc24fc87cb3c95711ed917cea5bc0d18.png)

After I clicked on the icon, I was redirected to the Notifications page. I could see that there was an email in the test user’s Inbox and I could also see the pending invitation to join the Collaboration-test repository as a contributor. The test user could also see that I invited him/her to become a collaborator for this repository.

![](http://hdoc.csirt-tooling.org/uploads/upload_5ecc94f1ba047d2ef27e80d875e268ff.png)

I clicked on the invitation, so on the next screen, I could accept the invitation or decline it. I could also block the user in case I think that the invitation was spam mail or malicious content:

![](http://hdoc.csirt-tooling.org/uploads/upload_f22f0ba6e02f54f67b2afab2ac43b4f1.png)

In most cases, invitations are sent by people you already know. In this case, it is not spam and you probably discussed on another channel that your help would be needed in this project (repository).

If you don't know the person, you can get more information about them by clicking on the link of their GitHub username, you can see what repository/repositories they have, and if the information is filled in their profile page, you can collect more information about them.

Since I invited myself for testing purposes, I clicked the button ‘Accept invitation’. The following screen informed me (as the ‘Test-Collaborator-1’ user) that from now on I had ‘push access’ to the Collaboration-test repository:

![](http://hdoc.csirt-tooling.org/uploads/upload_81a8a9fba7eb1664904114ff11c9e4c2.png)

This is a very important message. In other words, it means that from now on the test user can also work on this repository.

**Let’s switch back to my account and add a new file:**

I logged in to the repository (collaboration-test), clicked on the ‘Add file’ dropdown menu and chose the option ‘+Create new file’.

![](http://hdoc.csirt-tooling.org/uploads/upload_9f75dd50e8feaf07b2d59d244512c4f5.png)

I decided to write a recipe for making pancakes. Since I am not a good cook, I asked my fictitious friend (Test-Collaborator-1) to help me finalise it. First, I named the file ‘Pancake.md’. It is a markdown file and it is very important to collaborate on GitHub by using this file format (for more details, please consult the [**GitHub Flavoured Markdown Specifications**](https://github.github.com/gfm/).

I did not have branches, so I saved my file in the ‘main’ branch. To save my changes, I clicked on the ‘Commit changes…’ button.

![](http://hdoc.csirt-tooling.org/uploads/upload_93adf464a2f913b9447d20a6f12d3964.png)

The Commit changes popup appeared. GitHub auto-populated the Commit message, I just added ‘file’ after the pre-populated message ‘Create Pancake.md’. 

The commit message is compulsory, whereas the ‘Extended description’ is not mandatory (but this is the place where you can type what you changed and why to inform other collaborators and make their work easier). 

It is essential to properly document actions, so that they can be revisited months or years later when needed, and the reasoning that led to them is still available through this documentation.

I did not want to create a new branch, so I committed my changes directly to the main branch and then clicked on the button ‘Commit changes’. 

![](http://hdoc.csirt-tooling.org/uploads/upload_a0eeb79ce576b198f7a1841eba13d8fb.png)

Once I clicked the ‘Commit changes’ button, the repository page appeared. I can see a new file in the ‘Name’ column of the file list of the repository. I can read the last commit message (Create Pancake.md file) and the time when the file was committed (32 minutes ago). I could also see in the top left-hand corner of the screen, that I created this file in the main branch.

![](http://hdoc.csirt-tooling.org/uploads/upload_0ef1bd2e2a6e88dde6da766d6ff06d5e.png)

I did not want to create a new branch at this time. If I wanted to create a new branch, I would have had to click the link ‘Branch’ and then while on the Branches page, I should have clicked on the button ‘New branch’:

![](http://hdoc.csirt-tooling.org/uploads/upload_543a7230270f3950a2f6ecd70660fa4c.png)

In case you want to create a new branch, you need to name your branch. I made a screenshot only for demonstration purposes: I can create a new branch and call it ‘Pancake’ – if I wanted to.

![](http://hdoc.csirt-tooling.org/uploads/upload_05c85b649fdd3b1f865b45aeba50771f.png)

The usual practice is to click on the name of the file you want to modify, make the modifications and then commit the changes into a new branch (so you, as a collaborator, do not make unwanted changes till the modifications are not accepted (and merged into the main branch). To demonstrate this

**Let’s switch back to the account of ‘Test-Collaborator-1’:**

I went to the repository and clicked on the name of the file I wanted to modify as a collaborator. This is what the file looked like:

![](http://hdoc.csirt-tooling.org/uploads/upload_731ae08dcec1412998c30b9eee85c06c.png)

On the left, I could see the file tree. Since I only had two files (a README and a file called Pancake) I did not need the tree, so I collapsed it. 

Now, I could start checking the content of the file. I thought we might use some bullet points in the Ingredients section to make it more readable. Also, I think some ingredients were missing, so I added them and proposed using a numbered list for the Instructions section since the order of these actions is very important not to mix them.

To make these changes all I had to do was click on the pencil icon in the top right-hand corner of the editor.

![](http://hdoc.csirt-tooling.org/uploads/upload_a22fc3169c1945dbbb59baa8b316e55c.png)

The editor opened up and I could start editing the content:

![](http://hdoc.csirt-tooling.org/uploads/upload_44ef403aa267caf362a7d98dbf6bd205.png)

I made my changes so the file looked like this in Edit mode:

![](http://hdoc.csirt-tooling.org/uploads/upload_9a3be721f4c1317a8608f0817838e56c.png)

The preview mode showed the changes I had made even more spectacularly. Now, I was happy with the changes I made, so I clicked on the ‘Commit changes’ button in the top right-hand corner:

![](http://hdoc.csirt-tooling.org/uploads/upload_e3d1d508453aca6a2a7b15dbfb321e26.png)

Alternatively, I could cancel my changes (Cancel changes button) or change the branch from the main (at the top of the editor).

I wanted to improve/modify this file, so I chose ‘Commit changes…’. In the Propose changes pop-up window, I created a commit message, gave a detailed description of the changes and also chose a different branch than the main.

![](http://hdoc.csirt-tooling.org/uploads/upload_2d77f137c1057cad6d0a9f9916c80ede.png)


This time, instead of directly proposing changes to the main branch, I created a new branch and opened a pull request. 

This is best practice to always create a new branch, make changes there, and create a pull request (so the other person can see what kind of changes we propose and s/he can decide whether s/he approves or declines the changes).

![](http://hdoc.csirt-tooling.org/uploads/upload_0103c0ec168728f54f5bf747818a7f37.png)

At the top of the page, GitHub informed me that a new branch was created (Test-Collaborator-1-patch-1) and there were no merge conflicts, these branches could be merged automatically.

On the right, you can see the ‘Reviewers’ section. In this case, Test-Collaborator-1 was asked to join and improve the content, so I am the reviewer. In the case of more complex projects, there can be several reviewers. At this moment, we do not use labels, project names or milestones.

With a pull request, we propose changes. The reviewer can see the changes and either accept/decline or start a conversation with us.

In the lower section of the page, I could see detailed information on what was changed (1 file was changed, 14 additions and 9 deletions were made).  GitHub also visually helps us to see exactly which lines have been changed: those marked in red are deleted, and those marked in green are added lines:

![](http://hdoc.csirt-tooling.org/uploads/upload_a612c4a0f1bb4ec9879b9bcbb65b37f5.png)

At this point, you can still create a draft pull request. Click on the downward pointing arrow to the right of the ‘Create pull request’ button and choose the ‘Create draft pull request’ option:

![](http://hdoc.csirt-tooling.org/uploads/upload_703194b8c98f60abeeb518462f4d63c9.png)

In case you are firm that you do not want to change anything else at this point, simply click on the ‘Create pull request’ button (by default, you create a pull request by clicking on this button).

![](http://hdoc.csirt-tooling.org/uploads/upload_5858ff9b8f3893fa1d18d30cc70f36c1.png)

Now, the user Test-Collaborator-1 can merge the pull request (by clicking on the ‘Merge pull request button).  By using the downward pointing arrow, further options become available:

![](http://hdoc.csirt-tooling.org/uploads/upload_160d07fbe3427923900df490d03823a1.png)

Normally, the repository owner (or the person who invited you to collaborate) or other dedicated team members can merge changes because they should review the proposed changes and discuss whether they approve the changes or decline them. Therefore, 
 
**Let’s switch back to the repository owner’s account.**

I logged in and saw that there was a pull request waiting to be managed:

![](http://hdoc.csirt-tooling.org/uploads/upload_0fda7b579f78c47b13bbcfb4f9181f0a.png)

I clicked the ‘Pull requests’ link at the top. The screen showed that the markdown file ‘Pancake’ had been updated by Test-Collaborator-1.

![](http://hdoc.csirt-tooling.org/uploads/upload_e2ec05c35f692428378d8d1cf32bdfde.png)

By clicking on the ‘Update Pancake.md – collaboration’ link I could see the same screen as before. As a repository owner, I merged the pull request. GitHub informed me who merged what and into which branch:

![](http://hdoc.csirt-tooling.org/uploads/upload_09a29fa6ed2ace9768258b7f6d462af3.png)

The next screen showed that the commit (ID:7c5279e) had been merged into the main branch so the pull request was successfully merged and closed.

![](http://hdoc.csirt-tooling.org/uploads/upload_5e411db7f3cf98a2c13a467417735c70.png)

GitHub also suggests deleting the Test-Collaborator branch (since the proposed changes were merged into the main branch and we do not need the Test-Collaborator branch anymore).

By clicking on the ‘Revert’ button, you can still go back to the previous version of the main branch (the one was before merging). By clicking the Delete branch button, you can delete the branch that was merged. GitHub informs us very clearly about the changes made:

![](http://hdoc.csirt-tooling.org/uploads/upload_10f1ae58d520885684b19e3a1befd197.png)

Now, let’s click on the ‘Code’ link at the top of the screen and open the file that was modified to confirm changes visually.

![](http://hdoc.csirt-tooling.org/uploads/upload_932158815f5b9118923f9fe3558b5c75.png)

Everything looks the way we wanted. Great job!
