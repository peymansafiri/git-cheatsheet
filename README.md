# git-cheatsheet

## This Document is for My DevOps exerscises ,  I want to answer some question about git:

### why do we use version control tools like git?
Programming projects usually have multiple developers working in parallel. So a version control system like Git is needed to ensure there are no code conflicts 
between the Code developed by multiple developer. in addition we have timline for project and we can revert to an older version of the code.

### What is the meaning of repository and what files are important to create  ?
2- in version control sstem is a data structure stores files , source codes , directories and meta data . a good repositor has 3 files : READEME.md , LICENSE , .gitinore.

### What are the parts of a good document?
in readme file we introduce the project , show how to use and how to contribute it.

### What does git clone command do in git ?
git clone command is used to point to an existing repository and make a copy of that repository in local repository.

### How to upgrade and sync local repository with remote repository ? 
we use "git pull" command to update local repository and sync it with remote repo. 

### what is difference between reset, revert and checkout ? 
reset: git reset is a command that is used to undo local changes to the state of a Git repo and creates a new commit 

checkout: git checkout is used to switching between different versions of a target entity , such as another branch or another commit.

revert: git revert is used to create new commit to reverse the effect of some earlier commits.
  
### what is difference between merge and rebase ? 

merge : git merge the codes in multiple branch and creates new commit.in another word combines some commits into one unified history of commits.

rebase : git rebase integrate changes from one branch into another .rebase moves a feature branch into a master but does not create new commit.
  
### which command shows history of commits ? 
git log

### How do you see the files changed in a commit?
The git diff command displays the differences between files in two commits or between a commit and your current repository. 

### what is tag and how to use it ?
tag is used for a marked version release.

### How to contribute a project in git ?
1) create feature branch and then merge with master
2) create organization , fork from it by teams and then merge by project manager to master branch.
    
### What are branches and how to merge it ?    
git branches are a pointer to a snapshot of changes , we can merge it with master.   
   


[@dwsclass](https://github.com/dwsclass) dws-dev-005-git


