# 6. Using GitHub exclusively

##  1.	What if you do not want to use the command line (Git)?

Not everyone likes to use the command line since you have to learn commands to use it. With an intuitive and well-designed user-friendly interface, many activities can be solved with a couple of mouse clicks without typing command lines.

If the terminal is difficult to use or you are averse to it, there is an option for you to create, manage and develop content without command lines through the GitHub interface.

This chapter is about creating and managing content on the GitHub interface alone, without using a terminal (or any type of editor, like VS Code), and how to share content with others and develop it collaboratively.

I use the same test repository (TestRepo) to demonstrate the above goals.

### 1.1. How to create a new file?

Open your repository, click the ‘Add file’ button and choose the ‘Create new file’ option.

![](http://hdoc.csirt-tooling.org/uploads/upload_cf3f25382c60d8b7dc8f06eae2a8245f.png)

A new window opens, where you can name your file (1), create content (2) and save your changes (commit changes (3).

I also added the extension ‘md’ to create a markdown file. Next to the name, you can see that the file was created in the ‘main’ branch. Above the editing area, you can find the ‘Edit’ and the ‘Preview’ buttons. 

You are in ‘Edit’ mode while you are editing your file. If you want to see your changes, please click the ‘Preview’ button.

![](http://hdoc.csirt-tooling.org/uploads/upload_f32f37ec6a0b886dda32314828f499c3.png)

After you are done with the changes to make, click on ‘Commit changes’, write a commit message and write an extended description if the description of changes requires a longer explanation:

![](http://hdoc.csirt-tooling.org/uploads/upload_8fc073dedaf2e0d5559c5020513b3098.png)

Once you click ‘Commit changes’, you are redirected to the repository’s main page showing all the files and folders (if any):

![](http://hdoc.csirt-tooling.org/uploads/upload_23562a6b7f8e18fd33adaf0f69ec73e3.png)

### 1.2. How often should you make commits?

The answer to the question is more complicated than it seems at first. Perhaps we could understand and answer this question in the simplest way if we looked for the answer to why it is necessary to commit in Git and GitHub. Similar to saving a file, a commit takes a snapshot of the current state of the file.

Although GitHub automatically saves changes, there should be often points during the development of content that can be returned for some reason.

So, the answer to the question is that it is necessary to commit when creating some logical element or idea in the content has been completed. That is, you can close some logical unit, or some goal has been achieved.

What kind of logical content or what goal can be set during content development is influenced by what the content itself is.

If, for example, we are coding on the GitHub interface and the goal is to create a specific feature. It is worth committing (i.e. adding a point in the development process where we can go back and check later whether it works or the code needs to be developed) if the given feature has been coded.

If the task is to write an article or prepare a report, then the logical unit after which it is worth committing is the completion of a chapter or, in the case of a report, the preparation of a statement.

Git assigns each commit a unique ID, called a SHA or hash, which identifies the changes since the previous commit. If you commit every time you change a line of code (when you are coding) or after each paragraph (in case you write an article), it will be hard to read the commit log and determine precisely when and what happened and which previous version could be reverted to if we wanted to fix something.

If you are working on a project alone, it does not matter how often you commit. But even in this case, the description of the commit should be meaningful so you can remember what change you made when you read it.
