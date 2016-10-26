# GitHub Tutorial

_by Luis Cordero_

---
## Git vs. GitHub
The difference between Git and Github 
  
Git is basically taking a snapshots of 
code and it doesn't require GitHub. 
But Github requires Git. Github uses 
the [cloud](https://www.thecloud.net/),
an online server to store your work. 


---
## Initial Setup
Go to [github.com](https://github.com/) sign up. Make sure you sign for **free account**.
After doing three step setup, you have just made a github account.  

Keep in mind to remember your **password** and **username** for your github account. 

![alt text](Screenshot_2016-10-24-11-44-29.png)

SSH keys are a way to identify trusted computers without involving passwords. 

---
## Repository Setup
How to create your first repo, only take a few steps. 
 
 First create a new repo on your github account,
 as seen on the images below. After giving the repo a name, 
 keep in mind the folder name of that repo has to be same (_case sensitive_)
 within your workspace of that specific folder you'll be working on. 
 
 
![alt text](github-tutorial.jpg)
![alt text](dream.jpg)

So now since we're in our workspace within [c9.io](https://c9.io/).
Lets create a file called README.md with the use of `touch` command.
But before you create file `cd` into your file. By the time you cd into your file master branch must appear within bash. This tells the user that the file is a repository or another way you could have create a repository would be `git init`.

![alt text](github-learning.jpg)

After creating the file, open the file and edit it. 
Since you modified your file up to the staging area, in other words `git add [file]`. Git add, adds file to the staging area.

![alt text](add.jpg)

Now, `git commit -m "[message]"` in order to take a snapshot of any changes to the file/folder. Your last `git push` use the existing repository from the command line or the image above.

`cd` - change directory


`touch` - create file(s)


`git init`- create a repo


---
## Workflow & Commands

`git add [file]` - adds file(s) to staging area 
to make sure modified files are read already just like this image below 

![alt text](add.jpg)

`git push` - to push updated files to remote


`git commit -m "[message]"`- to take a snapshot with a message attached based 
on the modified file you "saved"/ snapped. 


`git status`- bascially asks the computer for changes you've made to anything in your repo.

Changes will be in red that aren't on staging area, but if they are in green they are modified files that are on stage.

![alt text](add.jpg)


If you use all these commands constantly, you pratically can ask what types of changes you've done. Then add all changes, now you can save them. Next your able to push them on to you repository. Anyways, you can constantly 
keep updating you remote online and local workspace, just dont forget to **`git add, git push,  git commit`**. Last tip always 
use **`git status`**. 