# basic-github-commands
Basic github commands to get started.

##### create a new repository
    - Best practices for names example: ​​basic-github-commands
        * use lower case.
        * use dashes.
        * create a .gitignore

##### `git clone`
    * SSH
    * HTTPS

##### `git fork`

##### `git status`  

##### `git branch`
    * list local branches

##### `git branch -D` [branch-name]
    * delete branch

##### `git branch -vv`
    * check if your local branch is behind, ahead. 
    * Example:   
            - master       58ec21ac [origin/master] update changelog
            - test-branch  58ec21ac update changelog

##### `git checkout` [branch-name]
    * switch between branches

##### `git checkout -b` [branch-name]
    * create new branch 

##### `git commit -m` "any-comment"

##### `git commit --allow-empty -m` "any-comment"
    * allow empty commits, no changes

##### `git pull origin` [branch-name]
    * update local branch. ex: git pull origin master

##### `git push origin` [branch-name]
    * used to publish local changes to a central repository.

##### `git merge origin/master`
    * update local branch with master   

##### `git diff`
    * This command shows the differences between the files in the staging area and the latest version present.

##### `git restore` [file-name]
    * remove file or changes before `git add .`  

##### `git restore --staged` [file-name]
    * It will discard any local, uncommitted changes. 
    * Exemple: To remove changes after execute `git add .`  

##### `git clean -f - d` [file-name]     
    * delete untracked files

##### `git log`
    * show commit logs 

##### `git reset` [commit]
    * This command undoes all the commits after the specified commit.

##### `git reset –hard` [commit]    
    * This command discards all history and goes back to the specified commit.
