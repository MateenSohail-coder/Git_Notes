<mark style="background-color: lightgreen ; padding:11px">Features Branch</mark>

# Git Notes
* **Clone** : To Open any repository.
<br>

>  git clone [link of repository]()   

---

<br>

* **Status** : To check the status of repository.
<br>

1. *Untracked* : New files that  git does not yet track.
2. *Modified* : Changed.
3. *Staged* : File is ready to commit.
4. *Unmodified* : Unchanged.
<br>

>  git status 
<br>

---

<br>

* **Add** : Adds new or changed files in your working directory to git staging area.
<br>

>  git add [File name]()  

---

<br>

* **commit** : It's the record stage.
<br>

> git commit -m "any relevent message "   

---

* **Push_Command** : To upload local repository content to remote repository.
<br>

> git push origin [Branch Name]()   

---

* **Pull_Command** : To upload remote repository content to local repository.
<br>

> git pull origin [Branch Name]()   

---

* **Init_Command** : Use to create a new git repository.
<br>


1. > git init  

    **To add folder into local repo of git**
2. > git remote add origin [link of repository]()

    **To add folder into remote repository of git** 
3. > git verify remote

    **To verify remote repository**
4. > git branch

    **To check the current branch**

5. > git branch -m **branchName**

    **To rename branch**
6. > git push origin [Branch Name]() 

   **Add changes to any specific branch**

---


* **Git_Branches** : Use to work with many clients.
<br>

1. > git branch

    **To check current branch**
2. > git branch -m [Branch Name]()

    **To rename branches** 
3. > git checkout [Branch Name]()

    **To switch any branch**
4. > git branch

    **To check the current branch**

5. > git checkout -b [Branch Name]()

    **To create new branch**
6. > git branch -d [Branch Name]() 

   **To delete any branch** 

---

* **Merging_Code** : Use to merge many different branches code .
<br>

1. *Way1*
>  git diff [Branch Name]()

**To find difference between branches**#

>  git merge [Branch Name]()

**To merge branches code**

2. *Way2*

*Create a **PULL Request** from github*
---

<br>

* **Git_Log** : To saw all commits on termial.
<br>

> git log 

---

* **Resolving merge conflicts** : An event that takes place when git is unable to automatically resolve difference in code between the commits.
<br>


---

* **Undoing_Changes** : To restore our undoing change.
<br>
1.Case1: Staged Changes --> To restore add changes.


> git reset [File Name]() 

**For specific file**

>git reset

**For all files**

2.Case2: Commited Changes --> To restore only one commit change.


> git reset Head~1

3.Case3: Commited Changes --> To restore many commit change.

> git reset [Commit Hash]() 

**Commit hash from *git log* command**

>git reset --hard [Commit Hash]() 

**Restore changes on file in vscode**

---