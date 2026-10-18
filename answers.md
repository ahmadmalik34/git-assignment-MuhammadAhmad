# Git Assignment — Answers
<br/>

# PART 1
# QUESTION .1
## 1.  What is a terminal? How is it different from clicking through folders in a file explorer?

#### A terminal is a text base interface that takes commands (in the form of text) as input and execute the instructions and give us the output.

#### It is different from the usual clicking through folder because, we have to type what instructions to execute. For example we want to move the a desired folder, in direct clicking we can directly click and go inside that folder but in a terminal we have to type "cd" command followed by the name of the folder.

---

## 2. Write the terminal command to: (a) list all files including hidden ones, (b) create a folder called project , (c) move into that folder.

#### (A) "ls" is command to listall the files inside the current directory including hidden files.

#### (B) To create a folder named project we have to type command "mkdir project". mkdir is command to make new directory/folder and project is our desired name.
#### (C) To move inside the project folder we have to type type "cd project". cd is command to change diretory and project is the name of that directory/folder. That folder or directory must be present in the current directory from which we are moving.
---

## 3. What does the cd .. command do? What about cd ~ ?

- #### "cd .." goes one working directory back to the parent folder of the present working directory. For example the present working directory is  "C:\Users\pc11\Desktop\Git-Github>"  then using "cd .." command in that directory will make "C:\Users\pc11\Desktop>"  as our present working directory.
- #### "cd ~" makes our present working directory goes two directories back. or example the present working directory is  "C:\Users\pc11\Desktop\Git-Github>"  then using "cd ~" command in that directory will make "C:\Users\pc11>"  as our present working directory.

<br/>

# QUESTION .2
## 4. Explain what version control is in your own words. Give one real-world analogy (not Google Docs — pick your own).
#### Version control means a system that allows us to track the changes and versions of the thing we are rying to track. It can be a folder containing different files full projects and codebases.

## 5. What is the difference between Git and GitHub? Can you use Git without GitHub?
#### Git is alocal software or a tool that we install locally to trackc changes in our directories and projects. Where as Github is an online service that allows us to keep our  directories online on a cloud base platform. Github is built around Git.
#### We can use Git independently without Github, it is a system that we can run locally on our system without having an internet connection where as Github requires internet connection.

## 6.Name three features GitHub provides that Git alone does not.
#### It provides Cloud Hosting for our Git repositories and make it easy for us to acces the repos anywhere.
#### It allows multiple users to collborate and contribute to one single project.
#### It provides us a web interface where we can visually see changes of our repo.

## 7. What is a repository? What is the difference between a local repository and a remote repository?
#### A repository is a folder that has a feature to track changes in it.
#### **Local Repository:** A repositry that is located on our computer and is completely offline.
#### **Remote Repository:** A remote repository is a online repository hosted on a cloud plaform and it can be shared easily with someone using the link of that repository.
<br>

# QUESTION .3

## 8. Explain what HEAD means in Git. What happens to HEAD when you switch branches?
#### A HEAD is a pointer that tells us the current location of our repository. For example when we apply some change in out repository and we move the new version of our project. Our HEAD moves from that older verison pointer to the latest version and when we go back to the older version our HEAD moves the pointer of that location.
#### When we switch between branches our HEAD deattaches from the previous branch because every branch has it's own starting point and a HEAD cannot go before a starting point and when we amke a branch it means we are seperating our code into a new branch and having a new seperate starting point.

## 9.  What is a .gitignore file? Write a .gitignore that ignores: all  .log files, a folder called node_modules/ , and any file ending in .env .
#### A .gitignore is a file that knows the names of all the files and we are not intending to track. We write then name of the files in the .gitignore file and Git does not track those files.
#### **.log files:** *.log
#### **node_modules/:** **/node_modules/
#### **any file ending in .env:** *.env



