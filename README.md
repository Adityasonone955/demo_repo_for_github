# This is demo Local repo 

# Install git (One time setup) 
    download git from: 
    https://git-scm.com 

    Check installtion : 
    1. open git bash and add command 
        git --version  

# configure git (Runs One)

Set your username and email : 
        git config --global user.name "your-github-username" 
        git config --global user.email "your-email@gmail.com"

check status : git config --list 

# Some vs Code Intruction 
     
1. check git version
    git --version 

2. github repo clone 
    git clone <--some Link-->
 
3. check file status (modified/untracked = if any file we can't modified whem make clone they shows untracked / staged = ready to commit)
    git status 

4. add modified files 
    git add <--file name--> or . (dot means all modifide file)

5. commit file 
    git commit -m "message"

6. Push local repo content to remote repo 
    git push origin main or git push -u origin repo (this for when we have to push on same branch)


# Workflow of project add to github 
1. make github repo 
2. clone repo in vs 
3. changes or modified 
4. add 
5. commit 
6. push to github 
7. refresh github to see changes 

# new project when add use this command 

1. after writing all code  
    1. Make new repo on github   
    2. connect repo to project 
        git remote add origin <-link->
    3. git remote -v (to verify remote repo)
    4. git branch    (to check branch)
    5. git branch -M main (to rename branch / its optional because default is branch main) 
    6. git push origin main or git push -u origin main (if it use then you have make any changes that time you only give command "git push")

# When devloper, testers and other pofessional work on one project for creating feature use this 
    1. git branch (to check branch)
    2. git branch -M main (to rename branch)
    3. git checkout <-branch name-> (to naviate in branch) 
    4. git checkout -b <-new branch name-> (to create new branch) 
    5. git branch -d <-branch name-> (to delete branch)

# merge Branch and code 
1st way 
    1. git diff <-branch name->   (to compare commits, branches, files & more) 
    2. git merge <-branch name-> (merge 2 branches) 

2nd way 
    In github account 

# git 