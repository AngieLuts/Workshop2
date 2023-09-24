# GIT Instruction

![gitlogo](git_logo.png)

First of all you need to install **GIT** 

1. Download from the official [site](https://git-scm.com/download/win)

2. Install on PC

3. Set initial configuration: 
   
    * git config --global user.name "YourName"
    * git config --global user.email 'your_email@example.com'

----
### **GIT commands**

> **git init** - initialize - creating an empty repositary in a selected folder 

> **git add .** - adding **all** the file to repository **git add filename** - only *selected* file



green hightlighting signaling about unsaved modified info in order to fix it you need understand what has been modified  you need to use this:

> **git diff** - difference

> **git log** - log of all the commits

> **git checkout** - you can go to any commit you did before

> **git status** - check your current sitiation, check if there is something to commit



In case you need more commands I'm inserting a link to [Git_cheat_sheet](https://education.github.com/git-cheat-sheet-education.pdf)


### Working with branches 

> **gitbranch** - all the branches in a repository
>> **git branch BranchName** - check if there such a branch, if not then create such.   
*Note: you cannot create branches with same name, each name should be unique in a repository.*
>> **git branch -d BranchName** - check if there such a branch, if not then delete a branch 
>> **git checkout-b branch_name** - creating&switching at the same moment

> **git merge** - merging branches, that means info from both branches will be transfered to the current. If there is some conflicts you need to resolve it first

> **git log -graph** - log shown with graphics


#### *In order to delete a branch you can use these commands:*
 + *git branch -d* - this command checks if the branch was previously merged and then deletes it

 + *git branch -D'* - this command doesnt check merging. It just deletes selected branch

# Lecture 3


<**git clone** - cloning some repository

<**git pull** - pulling updates from  gitHub

< **git push** - pushing updates to gitHub