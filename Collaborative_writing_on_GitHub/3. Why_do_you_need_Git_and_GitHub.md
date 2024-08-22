# 3. Why do you need Git and GitHub?

The philosophy of Git and GitHub is based on the fact that we do not work alone; instead, several people work on the same project (or even several people work together on several projects), and the changes are saved in a central repository. 

The local version of the environment is called Git, whereas the central cloud-based repository is called GitHub.

Typically, you work on your local repo and send your changes (push) to GitHub. This usually happens even if many people work on the same project: developers and content creators work locally on their own computers, and after completing their work, they send their changes to GitHub.

To avoid conflicts in the content, every time we start our work in the local repository on our computer, we request from Github with a pull command any changes that someone made in the meantime until we last opened the repository on our machine.

Also, to avoid content/code conflicts, we push the changes to GitHub whenever we finish work on our local machine, thus maintaining the latest code in the cloud repo (GitHub).

It is best to follow this working method and get used to this kind of workflow since, in most cases, we do not work on the content alone but in collaboration, which significantly facilitates successful joint work.

Please note that the statements made here are elementary, and the Git workflow itself can be much more complicated than this. However, to start working on a specific project, the most important thing is to understand the Git Push and Git Pull commands so that data conflicts do not arise and your cooperation with others can be successful.

The diagram below from the [**DataCamp**](https://www.datacamp.com/tutorial/github-and-git-tutorial-for-beginners?utm_source=google&utm_medium=paid_search&utm_campaignid=19589720824&utm_adgroupid=143216588537&utm_device=c&utm_keyword=&utm_matchtype=&utm_network=g&utm_adpostion=&utm_creative=675429089965&utm_targetid=dsa-1947282172981&utm_loc_interest_ms=&utm_loc_physical_ms=9063043&utm_content=dsa~page~community-tuto&utm_campaign=230119_1-sea~dsa~tofu-tutorials_2-b2c_3-row-p2_4-prc_5-na_6-na_7-le_8-pdsh-go_9-na_10-na_11-na-oct23odp&gclid=EAIaIQobChMI3oq8uZThgQMVnpqDBx0fcg7tEAAYASAAEgLUz_D_BwE) website represents very well what kind of ‘transitions’ there can be between local and remote content and how we can always store the latest content in the central location.

![](http://hdoc.csirt-tooling.org/uploads/upload_310df5b430ebccd0494a52b452480888.png)
 
Nevertheless, you do not need to follow the above process: you may collaborate without using Git and the Git workflow. 

Likely, most collaborators will only use GitHub by forking the project, making changes and improvements to it, and then creating a pull request (also within GitHub itself) to send their changes for acceptance to the project administrators.

There are several collaboration methods and workflows for writers to collaborate on the open-source **OSD4ISO** GitHub project.

The purpose of this series of articles is to present these options and allow collaborators to choose the most suitable one for them.
