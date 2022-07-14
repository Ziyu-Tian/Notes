# README of the Notes Repo 
## 1: Introduction
This Github Repo is used to store the course notes in markdown, which URL is https://github.com/Ziyu-Tian/Notes. For the windows device, the local repo is ~Notes with remote repo named **R_Notes**; for the mac device, it has the same local path with remote repo named **RemoteNotes**.
## 2: Brief instructions of git 
### 2.1: Git instructions on macOS 
* git --version (-v): Check the version of current system 
* git config user.name <your name>/ git config user.email <your email>: Check the username and email of the device. (the name will denote who make the change of each version)
* git config --global user.name <your name> / git config --global user.email <your email>: Change the username and email of the device.
* git init: Initialize the local folder as a local repo. (Generate a '.git' folder)
* git add <file name> / git add <folder name>: Add the folder or file to local repo.
* git commit -m "message": Add commit to the operation 
* git commit -m "message" --amend: Change the last commit with new contents. 
* git diff: Check the change 
* git status: Check the status
* git log: Check the commit logbook.
* git reset --hard <commit>: Reset to the version before <commit> (commit number)
* git revert -n <commit>: Revert the change of commit <commit> (you have to git commit manually)
* git branch -c <branch_name>: create a new branch (**Noted that 'git add' and 'git commit' should be used at least one time to check the branch**)
* git branch: Check the branch in this workspace 
* git switch <branch>: Change the branch
### 2.2: Git instructions on windows
* git branch <branch_name>: Create new branch
* git checkout <branch_name>: Change the branch
## 3: Useful instructions for remote push & pull
### 3.1: Set SSH key for each device
* Find the 'SSH Key' option on Github 'Account Setting'
* Generate the SSH on device:
    * Use 'ssh-keygen -o' to generate the SSH, use 'cat ~/.ssh/id_rsa.pub' to show the key in terminal.(macOS)
    * Use 'ssh-keygen -o' to generate. cd .ssh, use 'cat id_rsa.pub' to show the key.
### 3.2: Use remote repo to manage codes in different devices
* Create a repo on Github:
    * Do not add anything, follow the guide to create a remote repo in your device.
* Connect a remote repo to local:
    * git remote add origin https://github.com/Ziyu-Tian/Notes.git ('origin' is the name for this remote repo, the url is the url of your Github repo page ends with '.git' 
* Clone the github repo to your device (if there is nothing in local):
    * git clone <team-repo-url> --origin <team-repo-nickname> <project-folder> ('-o' can change the name of the repo, 'project-folder' for the location to download the repo in your device)
    * git remote add <my-repo-nickname> <my-repo-url> (add your remote repo for this device)
    * git remote -v (check your remote repo)
* Update the newest version of the repo:
    * git fetch <team-repo-nickname>
    * git merge <team-repo-nickname>/main (merge the changes to 'main' branch)
* Push the changes you made to github:
    * git push <team-repo-nickname>
### 3.3: The use of .gitignore 
* Create a file named '.gitignore' can ignore some system files when doing the push.
* The '.gitignore' modal can be found on github and should be added before add anything to git.