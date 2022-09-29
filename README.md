# basic-github-commands
Basic github commands to get started.

1. create a new repository
    - Best practices for names example: ​​basic-github-commands
        * use lower case.
        * use dashes.
        * create a .gitignore

2. `git clone`

3. `git add`
    * can be used with dot or not.            

4. `git status`  

5. `git branch`
    * list local branches

6. `git branch -D` [branch-name]
    * delete branch

7. `git branch -vv`
    * check if your local branch is behind, ahead. 
    * Example:   
        - master       58ec21ac [origin/master] update changelog
        - test-branch  58ec21ac update changelog

8. `git checkout` [branch-name]
    * switch between branches

9. `git checkout -b` [branch-name]
    * create new branch 

10. `git commit -m` "any-comment"

11. `git commit --allow-empty -m` "any-comment"
    * allow empty commits, no changes

12. `git pull origin` [branch-name]
    * update local branch. ex: git pull origin master

13. `git push origin` [branch-name]
    * used to publish local changes to a central repository.

14. `git merge origin/master`
    * update local branch with master   

15. `git restore` [file-name]
    * remove file or changes before `git add .`  

16. `git restore --staged` [file-name]
    * It will discard any local, uncommitted changes. 
    * Exemple: To remove changes after execute `git add .`  

17. `git clean -f - d` [file-name]     
    * delete untracked files

18. `git log`
    * show commit logs 

19. `git reset` [commit]
    * This command undoes all the commits after the specified commit.

20. `git reset –hard` [commit]    
    * This command discards all history and goes back to the specified commit.

21. `git rebase -i HEAD~4` 
    * have 4 commits, but you haven’t pushed anything yet and you want to put everything into one commit.
    * 4 is the number of commits, can be any number.
