# Git & GitHub

Git is a free and open source distributed version control system.

## Instalation git

For Instalation [Click here to download](https://git-scm.com/downloads)

## Create Profile on GitHub

Link to [GitHub ](https://git-scm.com/downloads)

#### 1. Create repository in GitHub

From top main navigation click on plus icon and from dropdown menu chooese New Repository<br />
![Create new repository](./assets/images/add.jpg "Click on new repository")

#### 2. Type repository name sf-homework

<br />

![Create new repository](./assets/images/create_1.jpg "MarineGEO logo")

#### 3. Choose a repository visibility - Private or Public

#### 4. Add README.md file \* optional or leave it as it is

#### 5. Add .gitignore \* optional or leave it as it is

#### 6. Choose a license \* optional or leave it as it is

### 7. Click CREATE REPOSITORY

<br />

![](/assets/images/create_2.jpg "Created repository")

## Cloning

You can clone your repository to create a local copy on your computer and sync between the two locations.
Open your repository.
![Click on Code button and copy url](./assets/images/clone.jpg "github cloning")

## Create a new repo from scratch and connect to github.

Open your terminal in desire location and create folder

    mkdir sf-homework

![create new folder](./assets/images/cmd_1.jpg "create folder")

    cd sf-homework

![](./assets/images/cmd_2.jpg "cd into")

    git init

![](./assets/images/cmd_3.jpg "init")

---

    create README.md file
    git add . too add all files in working directory or use git add file1 file2
    git commit -m "inital push" // write commit message
    git branch -M main
    git remote add origin https://github.com/username/sf-homework.git
    git push -u origin main

---

### Basic git commands

$ **git config --global user.name** youname

<br />

Setup an username

---

$ **git config --global user.email** example@example.com
Setup an email address that will be associated with each history marker

---

$ **git status**
Gives information on the current content status of a git repository and its contents

---

$ **git init**
Create new repository, Before we can do anything git-related, we must initalize a repo first.

Example - create new folder **myfirstrepo** open the folder via cmd and type **git init**

    mkdir myfirstrepo // create folder
    cd myfirstrepo // accees the foolder
    git init // initalize a repo

Output:
Initialized empty Git repository in **C:/path/to/the/reposity/myfirstrepo/.git/**

---

$ **git log**
Shows a default output for quickly reviewing the commit history

---

##### Example

Author: Darko <example@example.com>
Date: Sun Feb 19 01:19:41 2023 +0100

    readme file added in git

### Git add & commit

$ **git add --all** // will add all files changes in staging
Example:

    $ git add --all

$ **git add file1 file2 file3** // will add only file we specify to staging phase

    $ git add file.txt file2.txt file3.txt

$ **git commit -m "you commit message"** // after we add files in staging phase we have to add commit message
**Example**

    : $ git commit -m "login page functionality created"
