# LearnGit 

### Hello i am Shivam and here we are going to learn "how to install git" and use it on your respective Mac/Windows laptop/pc
### Installing git involves to parts 1.Installing git on local machine 2.Using Github on remote directory
## Installation
## 1.Install Git on your machine:
here you can watch how to install git on [Windows](https://www.youtube.com/watch?v=2j7fD92g-gE) and [Mac](https://www.youtube.com/watch?v=RLTCN0A29Ts).
on Mac you can just run .
```bash
$ brew install git
```
After complete git installation we have to sign up on Github.
## 2.Github Sign up(or sign in if you have a github account)
If you Already have a github Account then sign in [here](https://github.com/login). 
If you don't have a github account then just [Sign up](https://github.com/join) and create a new account.

## 1.Forking:

After Successsfully creating a github account go to the target [Repo](https://github.com/realcapacitor/LearnGit/) and click on the Fork button which is at the top right corner of the page.


![Test Image 4](/Images/fork.png)

The fork button creates a copy of targeted repo on your profile so you can work on it or modify it.

## 2.Cloning
Now go to your profile and click on the forked repo.
Then click on the code button you will get a cloning url copy that url.

![Test Image 5](/Images/clone.png)

Now go to your desktop and create a new folder and name it BasicGit(NOT NECESSARY).
open a terminal tab at that folder. for ex. domain/BasicGit


![Test Image 6](/Images/terminal.png)

Now declare that folder as a git local repo.
 Enter git init and hit enter
```bash
git init
``` 

![Test Image 7](/Images/gitinit.png)

Now to clone your remote repo to the local machine Enter git clone *url*
```bash
git clone https://github.com/*YourName*/BasicGit.git
```

![Test Image 8](/Images/cloned.png)

## Congrats!!! Now you have Successfully cloned a repo
