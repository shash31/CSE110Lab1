Quoting text

# CSE 110 Lab 1

## Shashwat Dudeja's User Page

**<ins>Table of contents:</ins>**
1. Introduction: ([Jump to](#Introduction))
2. Installing VSCode and extensions: ([Jump to](#Installing-VSCode-and-extensions))
3. Getting familiar with git and version contol: ([Jump to](#Getting-familiar-with-git-and-version-control))

### Introduction
**Hello!** My name is Shashwat Dudeja. I am a third year international student studying Math-CS.
I grew up in Mumbai, India. In middle school and high school, I used to really enjoy coding up games and/or other projects spending hours losing my mind debugging.
In my free time, I love to 
- Play basketball 
- Weightlift
- I also play a lot of chess and some piano occassionally.

### Installing VSCode and extensions



### Getting familiar with git and version control

**Working with <ins>command line</ins>:**

Before we start anything, we have to make sure that git is installed on our computer. If not, we can install [git here](https://git-scm.com/downloads).

Today, to get familiar with git, we will 

- [] Cloning repository
- [] Cding into repository and creating new branch and switching into it
- [] Modify README file
- [] Adding new changes
- [] Committing files
- [] Pushing changes to remote repo


First step is cloning the repository.

_Cloning repository:_

```
git clone <github_link>
```

![git clone command](/screenshots/git_clone.png)

- [x] Cloning repository
- [] Cding into repository and creating new branch and switching into it
- [] Modify README file
- [] Adding new changes
- [] Committing files
- [] Pushing changes to remote repo

Now, we 'cd' into the folder.

![cd command](/screenshots/cd_img.png)


Creating a new branch in the repo.

```
git branch <name_of_branch>
```

![git branch cmd](/screenshots/creating_branchimg.png)

Switching into that new branch using 'git checkout'. 

![git checkout cmd](/screenshots/switching_branchimg.png)

- [x] Cloning repository
- [x] Cding into repository and creating new branch and switching into it
- [] Modify README file
- [] Adding new changes
- [] Committing files
- [] Pushing changes to remote repo

We modified the README file so now we add the changes.

```
git add <files_changed>
```

![git add cmd](/screenshots/git_addimg.png)

- [x] Cloning repository
- [x] Cding into repository and creating new branch and switching into it
- [x] Modify README file
- [x] Adding new changes
- [] Committing files
- [] Pushing changes to remote repo

Now, we take a snapshot of the staged changes using the 'git commit -m <commit_message>' command.

![git commit cmd](/screenshots/git_commitimg.png)

- [x] Cloning repository
- [x] Cding into repository and creating new branch and switching into it
- [x] Modify README file
- [x] Adding new changes
- [x] Committing files
- [] Pushing changes to remote repo

Now, we push our current state of the repo that we snapshotted to the remote repository.
We use the 'git push' command with the '--set-upstream' flag as we made our changes in a different branch in which we haven't pushed anything before.

```
git push --set-upstream <repo> <branch>
```

![git push cmd](/screenshots/git_pushimg.png)

- [x] Cloning repository
- [x] Cding into repository and creating new branch and switching into it
- [x] Modify README file
- [x] Adding new changes
- [x] Committing files
- [x] Pushing changes to remote repo

**HOORAY!!**

**Working with version control in the <ins>VSCode UI</ins>:**

Now, we get familiar with version control through the VSCode UI instead of just the command line.
We can find documentation for version control in the VSCode UI [here](https://code.visualstudio.com/docs/sourcecontrol/overview#_git-support).


After consulting the documentation, we create a new branch in which we make a few modifications to the repo.
1. Modify the README file
2. Create a new file called _PRIVATE.txt_.
3. Create a _.gitignore_ file where we add _PRIVATE.txt_ to it.

We can look at the made changes here.

![staged commit](/screenshots/staged_commit_and_msg.png)

![current branch](/screenshots/current_branch.png)


### Conclusion:

Here's an image to a wolf.

[wolf](wolf.jpg)











