# How to collaborate to create and manage a successful open-source GitHub project?

## 1.	Introduction

Creating and managing an open-source GitHub project can be a rewarding venture that offers opportunities for collaboration, innovation, and community growth. However, success in the open-source world requires effective collaboration and project management strategies. 

In this guide, we'll explore the key collaboration steps and best practices for building and managing a successful open-source GitHub project.

## 2.	Why contribute to open-source?

A few people may wonder what is the point of joining and working on open-source projects. Although those who read these lines most likely already know why they want to join such a project, in the introduction it is worth giving some ideas to those who are still completely new to this kind of collaboration.

There are so many examples, but the bottom line is that contributing to open-source can be a rewarding way to learn, teach, and gain experience in almost any skill you can imagine. You can improve your existing skills, meet people who are interested in similar things, you may learn new things, and the list goes on and on.

Since the goal of our joint, open-source project is to help freelancers and small businesses to be as prepared as possible for cybersecurity challenges, those joining the project will likely be united by similar thinking and interest.

We welcome those who show an interest in this topic, who want to support and provide each other with information and who contribute to ensuring that as many members of the target audience as possible are better prepared for cybersecurity challenges.

## 3.	What does it mean to contribute to open-source projects?

If open-source projects are new to you and you have never contributed to any of those, then the process can be intimidating.

There are many misconceptions about contributing to open source: perhaps one of the most common is that you have to contribute code. But you don't have to worry! On the one hand, there is no need to add code: the essence of the whole project is to clearly explain and build up how to create value in this topic (cybersecurity) without coding since we will create textual content together.

Instead of coding, let's focus on how to cooperate in creating written content: this document was written to describe this procedure and help with this.

Contributing to open-source projects means following these rules, sharing your ideas, and proposing changes (deletion, changes, addition) to make the content even better.

In the following sections of the document, we introduce the project participants (community roles) and describe the rules of the game, by following which everyone will cooperate much more effectively and be better able to move the project forward.

## 4.	GitHub Collaboration – building communities

In this chapter, we are looking for the answer to the question of who can be the actors of the open-source project, what the contributors should pay attention to, and how the maintainers of the repository can manage and moderate the contributions.

### 4.1	The organizational structure of an open-source project

Although every open-source community is different, most open-source projects follow a similar organizational structure. Understanding the different community roles and general processes helps you quickly navigate any new project and can make cooperation between different actors more effective.

A typical open-source project has the following types of roles:

* **Author**: The person or organization who created the project.
* **Owner**: The person/s who has administrative ownership over the organization or database (not always the same as the original author).
* **Maintainers**: Those individuals who are accountable for shaping the vision and overseeing the organizational aspects of the project (they can also be the authors or owners of the project).
* **Contributors**: Everyone who contributed something to the project.
* **Community members**: Individuals engaging with the project, participating actively in discussions, or offering their insights on the project's trajectory.

### 4.2	Guidelines for repository contributors

To make the job of project contributors easier, we created a file containing the contribution guidelines in the root of the project repository, in the docs, or in the .github folder (this is the file you are reading).

When a contributor opens a pull request or creates an issue, they will see a link to that file. The link to the contributing guidelines also appears on the repository's contributing page. Probably the best example of a Contributing Guide is the one for [**GitHub Docs**](https://github.com/github/docs/blob/5b0904080228ab08a25ff8f2454f41fc2fd807a0/.github/CONTRIBUTING.md).

These guidelines help both repository owners and contributors to successfully create, manage and improve their mutual project:

* For the repository owners, contribution guidelines are a way to communicate how people should contribute.
* For contributors, the guidelines help ensure that they submit well-formed pull requests and open useful issues.

Because of the above, contribution policies save both owners and contributors time and effort caused by incorrectly created pull requests or issues that need to be rejected and resubmitted.

Repository maintainers can set specific guidelines for issues or pull requests by creating an issue or pull request template for the repository (see: [**About issue and pull request templates**](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates)).

**Contribution guidelines can include:**

* Steps for creating acceptable issues or pull requests.
* Links to external documentation, or a code of conduct.
* Community and behavioural expectations.

### 4.3	How to manage and moderate repositories

GitHub provides tools to aid repository maintainers in establishing and upholding standards of conduct within their GitHub.com communities. GitHub also offers a general code of conduct for everyone who uses GitHub.com. For more information, see "[**GitHub Terms of Service**](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service)" and "[**GitHub Community Guidelines**](https://docs.github.com/en/site-policy/github-terms/github-community-guidelines)." 

The community's behavioural norms encourage a pleasant and productive environment: effective moderation builds trust in the community and helps contributors feel safe and welcome. For relevant information, please read the article on GitHub [**About community management and moderation**](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/about-community-management-and-moderation).

It is worth reading these notes as a contributor because we will also follow these guidelines in managing and moderating our project repositories.

### 4.4	Tools for moderating the community

Repository maintainers can author guidelines for contributing to a project and share them in the project's repository. GitHub offers a community profile checklist to help repository maintainers author and publish community health files. 

Potential contributors can review the community profile checklist to learn about the community's standards and decide whether they want to contribute. For more information, see "[**Setting up your project for healthy contributions**](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions)."

When disruptive behaviour occurs in the community, GitHub offers tools for repository maintainers to apply their code of conduct and de-escalate conflict. Not only repository maintainers, but contributors can also report disruptive content to GitHub Support.

Our goal is not to exclude people from the project, but to enable everyone to contribute to the growth of it: we are happy to see new ideas and topics to achieve and implement the project's goals.

## 5.	Community profiles for public repositories

Maintainers of repositories have the option to examine the community profile of their public repository, enabling them to discover ways to foster community growth and provide assistance to contributors. On the other hand, contributors can review the community profile of a public repository to decide whether they want to contribute to the project.

The community profile checklist verifies that a project contains recommended community state files, such as README, LICENSE, CONTRIBUTING, or CODE_OF_CONDUCT, in a supported location. For more information, please read the "[**About community profiles for public repositories**](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/about-community-profiles-for-public-repositories)" article on GitHub Docs.

Repository maintainers can use the community profile checklist to see if their project meets the recommended community standards to help people use and contribute to their project.

As a potential contributor, use the community profile checklist to see if a project meets the recommended community standards and decide if you want to contribute. For more information, see "[**How to contribute**](https://opensource.guide/how-to-contribute/#anatomy-of-an-open-source-project)" in the Open Source Guides.

## 6.	Top-level documentation of a repository

The contents of a repository can be anything in principle: files of any kind can be created and stored there, which comply with GitHub's guidelines. Although the content varies, for most projects the following files are always present in the repository's main directory:

* **README**: The README is the user guide/instruction manual that welcomes new community members to the project. It explains why the project is useful and how to get started.
* **CODE OF CONDUCT**: It defines basic rules for the behaviour of participants and helps to create a friendly, welcoming environment. While not all projects have a CODE_OF_CONDUCT file, its presence indicates that this is a welcoming project to contribute to.
* **CONTRIBUTING**: While READMEs help users utilize the project, contributing docs guide individuals in making contributions. They specify the types of contributions needed and explain the process. Although not every project has a CONTRIBUTING file, having one indicates that the project welcomes contributions.
* **LICENSE**: Open source licenses allow others to use, modify, and distribute the project in your repository freely. Every open-source project needs to have an [**open-source license**](https://choosealicense.com/).

## 7.	How to create and manage a successful open-source project?

The following list is primarily intended for authors, owners and repository maintainers, how to start a project, how to make it successful and how to maintain and increase the successes achieved in the long term.

### 7.1	Define project goals and scope:
* Define the goals and scope of your project. What problem are you aiming to solve? Who is the target audience?
* Contact potential contributors early to gather feedback and ensure alignment with community needs and interests.
### 7.2	Setup the project repository
* Create a GitHub repository for the project.
* Choose an appropriate license to determine how others can use, modify, and distribute the content of the repository.
* Add a README file that provides an overview of the project, installation instructions, usage examples, and contribution guidelines.
* Document the project goals, scope, and schedule in the project README file to provide clarity to potential contributors.
### 7.3	Establish contribution guidelines
* Develop clear contribution guidelines outlining the process for submitting new content, reporting issues, and proposing new topics.
* Define version control practices, and documentation requirements to maintain consistency and quality across contributions.
* Encourage contributors to adhere to best practices (such as writing clear commit messages) and following proper pull request etiquette.
### 7.4	Create a welcoming community and good atmosphere
* Create a welcoming and inclusive environment where contributors feel valued and respected.
* Provide guidance and support to new contributors by offering them mentorship and resources to get them started.
* Provide constructive feedback and guidance to help contributors improve their contributions.
### 7.5	Leverage GitHub collaboration tools
* Utilize GitHub's collaboration features such as issues, pull requests, and project boards to facilitate communication and coordination among contributors.
* Encourage active participation in discussions and decision-making processes to foster a sense of ownership and shared responsibility.
### 7.6	Implement Effective Review and Feedback Mechanisms
* Establish a systematic content review process to ensure content quality, consistency, and security.
* Encourage constructive feedback and facilitate discussions to promote continuous improvement and learning.
* Recognize and appreciate contributions from all contributors.
* Be responsive to community feedback and address issues on time.

### 7.7	Promote your project
* Promote your project to attract users and contributors.
* Share it on social media, forums, and relevant communities.
* Participate in conferences and meetups to showcase your project and connect with potential contributors.
### 7.8	Continuously improve your processes
* Strive for continuous improvement and solicit feedback from users and contributors to identify areas for improvement.
* Regularly review and refine project goals, priorities, and roadmap based on community feedback and evolving needs.
* Celebrate achievements by recognizing the collective efforts of the project community to drive progress and success.

## 8.	Conclusion

Collaboration to create and manage a successful open-source GitHub project requires a combination of effective communication, inclusive community building, and transparent governance. 

By following these guidelines and best practices, project maintainers can develop a vibrant and thriving community of contributors that drives innovation and impact in the open-source ecosystem.
