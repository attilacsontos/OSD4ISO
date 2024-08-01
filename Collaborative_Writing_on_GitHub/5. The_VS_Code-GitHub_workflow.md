# 5. The VS Code – GitHub workflow

## 1.	Clone a repository

There are several ways to clone a repository. If you do not like using terminals, you may clone (copy) your GitHub repository (remote repo) to your computer using the [**GitHub Desktop**](https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop)’s user interface.

Another option can be to use a tool like **[Visual Studio Code](https://code.visualstudio.com/)** and add the GitHub Repositories extension to it. First, download VS Code, then click on the extensions tab on the left:

![](http://hdoc.csirt-tooling.org/uploads/upload_a7e7164ef580854bb6162a94e8606d22.png)

Choose the ‘GitHub Repositories’ extension. This extension allows you to open and edit remote repositories quickly and conveniently.

![](http://hdoc.csirt-tooling.org/uploads/upload_a7047112fb4e1a1cee2c8f0b5abfd1db.png)

Once the extension is installed, click on the GitHub button in the lower left corner so that the below options appear in the top search bar:

![](http://hdoc.csirt-tooling.org/uploads/upload_536eb3180adfe1f9235ad5e4283a8001.png)

Next, choose the option ‘Open Repository from GitHub’.

![](http://hdoc.csirt-tooling.org/uploads/upload_b8723cea8c5397baca2595014154ae61.png)

Finally, choose the repo you are looking for from the list of your GitHub repos. In our test case, we are looking for the repo we just created on GitHub (TestRepo):

![](http://hdoc.csirt-tooling.org/uploads/upload_d099610851919c8d86ca8ee49dac6eaf.png)

Your remote repository opens up locally within your Visual Studio Code:

![](http://hdoc.csirt-tooling.org/uploads/upload_fcf55cb833fb0baf5b22362bf6ac0ad5.png)

The same repository looks this way on GitHub:

![](http://hdoc.csirt-tooling.org/uploads/upload_5636cf987c976caf2ccbaa9ce34f6327.png)

Congratulations, you have created the link between the local copy of your repository and the one in the cloud on GitHub. 

## 2.	Push changes to GitHub

I made some changes in the local machine and sent them (by using the push command) to GitHub. I added a new line, which says “Now I am making some changes :- ).” 

This change can be seen on different parts of the screen (the modifications are marked on the screen with the numbers below):

1.	After the name of the file, the capital ‘M’ indicates the change
2.	On the left pane, the Source Control button shows a change (there is one change)
3.	The branch indicator at the bottom of the screen also shows with an asterisk that there is a change
4.	In the text area, you can also see the change (the application indicates the modification with a light blue vertical wavy line in front of the change):

![](http://hdoc.csirt-tooling.org/uploads/upload_7253b419edccaeaff4c4303633f2562d.png)

What was changed becomes visible if you click on the light blue vertical wavy line. It can be beneficial in case there are many changes in the file so that you can easily compare the versions:

![](http://hdoc.csirt-tooling.org/uploads/upload_193211bdbac5a6082d771daa346c086a.png)

Click on the Source control button on the left:

![](http://hdoc.csirt-tooling.org/uploads/upload_c60163cd323090003fcbbc6df53f098f.png)

Navigate to the message field (which is circled in red in the figure below):

![](http://hdoc.csirt-tooling.org/uploads/upload_160a77c8a04ad896685bfa6adadb2094.png)

And make a clear and descriptive message about the change you made. Then, click on Commit and Push:

![](http://hdoc.csirt-tooling.org/uploads/upload_b360c474cb95678e2a457471784a0e27.png)

The Source Control button becomes inactive, just like the ‘Commit ＆ Push’ field:

![](http://hdoc.csirt-tooling.org/uploads/upload_a9ae227efe882564a31ef0c45689a329.png)

It means that you committed (sent) your changes to GitHub. These changes become visible once you log in to GitHub and open your repository. 

Your comment message is visible next to the filename that contains the change (README.md). The file itself is open in the lower section of the screenshot, and the text change is also visible:

![](http://hdoc.csirt-tooling.org/uploads/upload_514b4951a8b3eba6bdf139bea4413245.png)

## 3.	Fetch changes to your local machine

When you fetch changes, the process is the opposite of what was described above: changes may have occurred on GitHub (if you are not working alone on a specific project, there is a real chance of this happening). 

In the case of fetching changes, you open Git or a terminal (i.e. Visual Code Studio) and query whether changes have been made on GitHub. If so, you copy those changes to the local repository.

To mimic the process, I intentionally made changes to the test repository (TestRepo) on GitHub, saved those changes, opened the local repository with Visual Code Studio and copied the changes to my local machine.

First, go to your repository on GitHub and open the file you want to change. There are several ways to do that: you may click on the filename to open the file or click on the pencil icon to edit it:

![](http://hdoc.csirt-tooling.org/uploads/upload_afa372272f9230fcd63025b2dbd418c9.png)

Then, on the next page, click on the pencil icon: 

![](http://hdoc.csirt-tooling.org/uploads/upload_252f896c41d3ab779d2a3413a63ed6e4.png)
In the editor, make some changes to your file. Once you are ready with your modifications, click on the ‘Commit changes’ button:

![](http://hdoc.csirt-tooling.org/uploads/upload_f07c29bfbeab8712de8c795012658287.png)

The commit changes window pops up, and GitHub auto-populates the ‘Commit message’ field with the ‘Update your filename’ message. 

You can keep this text, but it is worth entering a clear, short text that better describes the changes and can be understood later, even by you or your colleagues (or other GitHub users). So, instead of the below,

![](http://hdoc.csirt-tooling.org/uploads/upload_150532d19738038cbfe8ba85e1f5fd2b.png)

You may use something similar to this:

![](http://hdoc.csirt-tooling.org/uploads/upload_2bb863b470a929d52c6b405ba65b9661.png)

Next, click on ‘Commit changes’. You may leave the radio button on ‘Commit directly to the main branch’ since you do not want to create a new branch at this stage. In the new screen, you can read the text of your commit:

![](http://hdoc.csirt-tooling.org/uploads/upload_102e9c27894d3ffc99c9dd082d56883d.png)

With a commit, you save the changes and form a point on the theoretical timeline of content creation, which you can return to at any time during the content development.

If you log in to Visual Studio Code, the changes become visible (circled in red):

![](http://hdoc.csirt-tooling.org/uploads/upload_bfd2f28d35c282a3526ab23dfed410f7.png)

What if VS Code is open while a change is made on GitHub? To model this scenario, I added a new sentence to my file:

![](http://hdoc.csirt-tooling.org/uploads/upload_853f2f075426d4fd9e361495040ddb16.png)

And saved (in ‘Git and GitHub language’ committed) my changes:

![](http://hdoc.csirt-tooling.org/uploads/upload_27e041bf896eabb8a300b0c7390d73f9.png)

To make the changes in VS Code visible, the only thing you should do is open the repository (which has been changed) and click on the Refresh button:

![](http://hdoc.csirt-tooling.org/uploads/upload_e9ea93f1ea66cf121ee8625c3d2e36a0.png)

Do not worry if you do not know which repository was changed: by clicking the Refresh button, the editor (VS Code) will indicate which repository was changed.

