__Git__ is a distributed version control system that tracks changes in source code during software development.  
It is designed for coordinating work among programmers, but  it can be used to track changes in any set of files.  
Its goals include speed, data integrity, and support for distributed, non-linear workflows. 

#### Key Concepts

__Repository (Repo)__: A collection of files and their revision history. It can be local (on your computer) or remote (on a server).  
__Commit__: A snapshot of your project at a specific point in time. Each commit has a unique ID, a message describing the changes, and a timestamp.  
__Branch__: A parallel version of your project. Branches allow you to work on new features or bug fixes without affecting the main codebase.
__Merge__: The process of combining changes from one branch into another.  
__Pull__ Request: A request to merge changes from one branch into another. It is a way to review and discuss changes before they are merged.

###### Basic Workflow
Initialize a repository: __git init__  
Add files to the staging area: __git add <file>__  
Commit changes: __git commit -m "Commit message"__  
Create a branch: __git checkout -b <branch_name>__  
Switch to a branch: __git checkout <branch_name>__  
Merge a branch: __git merge <branch_name>__
Push changes to a remote repository: __git push origin <branch_name>__  
Pull changes from a remote repository: __git pull origin <branch_name>__  

__Advanced Concepts__

Rebase: An alternative to merging that creates a linear project history.  
Stashing: Temporarily save changes that you don't want to commit yet.  
Tags: Mark specific points in your project history, such as releases.  
Hooks: Scripts that run automatically before or after certain Git events.  
