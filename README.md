# gitCommands

In order to explore different commands in Git, you need to have a github account.  

Follow the below link to create a new account in github.  

https://help.github.com/articles/signing-up-for-a-new-github-account/


## How to create a Repository in GIT ?

- Click on the new repository link and create a repo in Git.

![](https://github.com/dilipthelip/gitCommands/blob/master/images/git-1.png)

## How to start using the new Repo?

Step 1:  

- Clone the new repo.

```

```

## FORK:

### Steps to Fork and keep the forked repo in sync:

Follow this link for the steps that need to be followed.  

https://help.github.com/articles/fork-a-repo/


## How to stop git tracking files/folder?  

 For Example:  

 If we want to stop ignoring the **.idea**  folder then add the below line in the **.gitignore** file .

**.gitignore file:**  

```
.idea/
```

**Folder :**  

If the folder is already a part of the git repo then run the below command to remove it from the git repo.  

The below command will remove the folder from the git repo.  

```
git rm -r --cached <folder>
```
For Example : To remove the **.idea** folder run the below command.  

```
git rm -r --cached .idea/
```

**File :**

If the file is already a part of the git repo then run the below command to remove it from the git repo.  

```
git rm --cached <file>
```

## How to remove untracked files ?

Folder:    
This will delete the untracked folder.  

```
git clean -fd
```
## How to  Unstage the staged files ?

The below command will unstage the staged files.

```
git reset HEAD
```
