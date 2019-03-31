## GIT Distributed version control system. ( Nambiappan - Learnt today)

# GIT Important commands

The following are important GIT Commands 

1. git init <repository name> 
   init creates repository under the current directory
  
2. git add <file name>
    add sub command adds the file for the git tracking.
  
3. git config --global user.name <<name>>
  using config and --global , we can set the user name of the contributor
  
4. git config --global user.email <<email>>
  using config and --global , we can set the user email of the contributor
 
5. git status
    status command gives the files which are untracked , staged etc. we can view the details and perform necessary action
 
6. git commit -m  "commit message"
    using the commit command with -m flag , we can commit to changes to file and with the commit message
    
    
7. git branch <branch name>
    git branch creates a new branch with name provided as input.
  
8. git rm  <file name>
    rm sub command removes files from git tracking
  
9. To ignore any files to be tracked not shown in the status everytime, create a .gitignore file and add the files name ,which            needs to be not tracked by git. These files are mostly compiled / binaries of source code , which is not required to be t  racked.

10. git clone  <path of orginal> <cloning Repo location>
   git cloning supports over ssh , http(s) and locally
   a. over https --> git clone https://github.com/nambiappan/repo_name <local repo path>
   
11.After local work is completed use the below command to push the changes to orgin master
   git push orgin master
   
12. git branch <branch name>
    To create new branch
   
13. git checkout <branch name>
   to start working on the new branch

14. git push orgin --all
   push branches to orgin
   
15. get merge <target branch>
   bring branches together

