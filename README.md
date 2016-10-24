# GitHub Tutorial

_by Stephen Wang_

---
## Git vs. GitHub

**Git and Github** is two very **different system** throughout coding. 

>**Git** is it own independent variable as it's a version control. Means that it keep "snapshot" of the code you made incase you want to revert back to the original code. This doesn't require Github and it runs on the command line. You have a basic workflow throughout this by:

* Making Directory then "cd" into the directory.
* You can initialized the directory into the respository.
* You can edit the files(Save along the way).
* You can add files.
* You can commit them.

>**Github** is an dependent variable as it's store codes within the cloud. This can be visually track and is easily collaboration with files. But, the catch is that Github is dependent on Git.

Github.com <-- Website (cloud)  
 
>The computer is the local machine (cloud9). It can be run within the command line and you can us the browser (Github.com) to interact with other respository. This can be visually be seen with multiple changes between commits from others. You have a basic workflow between: 

* Intial respository (No existing project on Github)
* OR start from someone else's repository
In other word, forking (Social Coding) and cloning (Copy of the repository). Remember to use push and pull

---
## Initial Setup

Making a Github accounts is essential for loading up cloud save data incase of grave errors or if you want to load up the file from another computer. The essential for Github can also be use to check other people repository and you can fork and clone it. To make a Github account, you:

1. Go on your web browser, (then incognito).
2. Type in github.com.
3. Top right click on signup.
4. It is best to put in your hstat.org username example:
Steven2789
5. Password can be based on your own, but must be remember.
6. Ignore the red bubble when it pop up and click on free account.
7. You click on finish sign up and your done.

---

>In order to create a SSH key for Github and C9, follow these step:

1. Github.com then top right of profile icon, then setting.
2. Go to the left bar and click on SSH and GPG keys
3. Click on "New SSH key"
4. Then head over to c9 tab and top right iis gear-icon.
5. Click. on SSh key tabs then copy/paste the SSH key into your Github (Begin with ssh-rsa).
6. Then add the keyGo over to C9 and open up the IDE.

---
## Repository Setup

There are code withing Github that are use to create alot of essential data. Those type of codes are use for setting up a repository espicially if you want to forward the save directly into the public cloud data. These code are:

* **'init'**
* **'add'**
* **'commit -m "message'**
* **'push'**
* **'git remote add origin'**

You add git before these each code and the order to have the repository updated is **'git add'**, **'git commit -m "message"'**, and **'git push'**.

>To set up a repository, you would have to follow these steps:

1. launch Github.com
2. Then sign up or sign into account (Top right).
3. Click on the plus sign top right.
4. Click on "New Repository."
5. If you have a directory that is intialized, you need to type the exact name from that directory you want to create into a repository. Copy the exact name into "Repository Name."
6. Ignore description and have repository set on public.
7. Once you create the repository, you go to code in the bar.
8. Then you want to go toward SSH keys as using HTTPS require you to type your user/password in.
9. Go down and look for "…or push an existing repository from the command line."
10. Copy the **'git remote add origin'** then the link from the repository you have created.
11. You finally have created a repository. If you want to copy someone else repository, here are the steps below.

---

>To copy/clone someone else repository, you would have to follow these steps:

1. Require the link from that person to access the file their public file.
2. By Typing in _"name/name of file."_
3. Then access their public repository.
4. Next on the top right, you click on fork (Allow you to grab their file).
5. Next, you click on _"clone or download."_
6. Click on SSH keys and copy the link.
7. Go to your workspace then type in **'git clone link'**.
8. Finally you **'cd'** into the files. 

>If you want to make changes or add your code:

9. You can change or add code.
10. Then you can _"New Pull Request"_ (Explained in ongoing workflow & commands).


---
## Workflow & Commands

>There are many essential code that allow your time with Github to be easier. The four codes that is used in Github which is essential is:

* **'git status'**
* **'git add'**
* **'git commit -m "message"'**
* **'git push'**
* **'git init'**
* **'git clone'**
* **'cd'**

>Throughout all these codes are helpful in your time in Github. The following example will be explain below:

* **'git status'** = It is one of the most important code you need to remember. git status analyzes the files that you have change within the directory. This would print out the result in the command line, stating what need to be fix, what is not done, or if its correct.

* **'git add'** = This add the current files entirely into Github, but if there are red files when you type "git status". This mean that the files have not been added into the Github. After add, you can commit the files and then push it into the repository. 

* **'git commit -m "message"'** = The files is commit into the Github, allowing to be push into the repository cloud. Before you do the commit, you need to add the files. Another way for this to mean "taking a screenshot" or snapshot.

* **'git push'** = Pushing the files helps in loading it up into the cloud9 cloud file. It's important to begin with add then commit then do push in order to have the current files into the repository. Essentially, it is a command that is commited from the local files into the cloud files.

* **'git init'** = This intialized the files within the directory. This is important as it intialize it and turn it into a master directory. Warning, don't ever intialized the workspace and if you do, the way to remove it is:

* **'rm -rf .git'** = It forcefully remove the master within the workspace when you type this in the command line.

* **'git clone'** = Cloning a file is a social connection between coding upon two people. But you can also Fork the directory and clone it in the process. Also to get the link, you click :

* **"clone or download"** 

>Then you copy the SSH link, not the HTTP link . You can copy that person directory by clicking on:

* **"New Pull Request"**

>In other word, you are submitting the changes made from your repository to the person with permission to replace it.

* **'cd'** = This allow you to enter into the directory you have made by entering the code. This is important if you want to make changes within the directory.