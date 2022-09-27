# basic-github-commands
Basic github commands to get started.

1. create a new repository
    - Best practices for names example: ​​basic-github-commands
        * use lower case.
        * use dashes.
        * create a .gitignore

2. `git status`  

2. `git branch`
    * list local branches

2. `git branch -D` [branch-name]
    * delete branch

1. `git branch -vv`
    * check if your local branch is behind, ahead. 
    * Example:   
            - master       58ec21ac [origin/master] update changelog
            - test-branch  58ec21ac update changelog

2. `git checkout` [branch-name]
    * switch between branches

2. `git checkout -b` [branch-name]
    * create new branch 

2. `git commit -m` "any-comment"

1. `git commit --allow-empty -m` "any-comment"
    * allow empty commits, no changes

2. `git pull origin` [branch-name]
    * update local branch. ex: git pull origin master

2. `git push origin` [branch-name]
    * used to publish local changes to a central repository.

1. `git merge origin/master`
    * update local branch with master   

2. `git diff`
    * This command shows the differences between the files in the staging area and the latest version present.

3. `git restore` [file-name]
    * remove file or changes before `git add .`  

3. `git restore --staged` [file-name]
    * It will discard any local, uncommitted changes in the corresponding files and thereby restore their last committed state. 
    * Exemple: To remove changes after execute `git add .`  

2. `git clean -f - d` [file-name]     
    * delete untracked files

1. `git log`
    * show commit logs 

    ------ 

4. `git reset` [commit]
    * This command undoes all the commits after the specified commit and preserves the changes locally.

5. `git reset –hard` [commit]    
    * This command discards all history and goes back to the specified commit.
