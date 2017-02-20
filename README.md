# gitCommands

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
