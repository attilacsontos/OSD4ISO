# 7. Using GitHub exclusively – Forking

## 1. What is the difference between forking and cloning?

**Forking**

The purpose of forking is to create a personal copy of someone else's repository in your own GitHub account.

This usually happens when you want to contribute to a project but do not have write access to the original repository. By forking, you are free to make changes and then push those changes back to the original repository.

Process:

1.	Click the "Fork" button on the repository you want to fork.
2.	GitHub creates a copy of the repository under your account.

**Cloning**

The purpose of cloning is to create a local copy of a repository on your computer. You must have access rights to a repository to be able to clone it. You can clone any repository, whether it is your own, a forked repository, or someone else's repository to which you have access.

Process:
1.	Run the command git clone <repository_url> in your terminal or command prompt.
2.	This copies all the repository files and history to your local machine.

**Summary**

* **Forking creates a copy of a repository on GitHub under your account.**
* **Cloning creates a local copy of a repository on your computer.**

These two actions are often used together: you might fork a repository to have your own copy on GitHub, then clone it to work on it locally.

## 2. Forking a project

In this case, you want to contribute to an existing project you cannot access. When you fork a project, GitHub creates a copy of the project, which will be entirely yours, and you can work on it as you see fit.

Project owners do not have to worry about adding users as collaborators and give them push access: GitHub users can fork any of the projects they can find on GitHub. 

You can quickly check whether anyone forked (copied) your repository. On the main page of the repository, there are several places where GitHub indicates whether your repo was copied or not: 

![](http://hdoc.csirt-tooling.org/uploads/upload_ceacb1bffe58f3c8c2e9b86c4a7896f4.png)

Forking a project is very easy: visit the main page of the repository (project page) and click on the ‘Fork’ button:

![](http://hdoc.csirt-tooling.org/uploads/upload_1c69f21fca779cf73cabe7cb6c29af8c.png)

Before forking, you usually search among the repositories. When you come across a repository that might interest you, you can copy it to your local machine with one click (Fork). The above repository is the [MISP](https://github.com/MISP/MISP) project of CIRCL.
You can see how many people are following (Watch), forked (Fork) and liked (Star) the repo:

![](http://hdoc.csirt-tooling.org/uploads/upload_bde6df4dfa6b4978fc41b5ba5121d8fa.png)

These data clearly show how significant and popular the given project is.
