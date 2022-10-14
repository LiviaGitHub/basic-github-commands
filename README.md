# basic-github-commands
Basic github commands to get started.

1. create a new repository
    - Best practices for names example: ​​basic-github-commands
        * use lower case.
        * use dashes.
        * create a .gitignore

2. `git clone`

3. `git add` [changes] or `git add .`
    * can be used with dot or not.            

4. `git status`  

5. `git branch`
    * list local branches

6. `git branch -D` [branch-name]
    * Force delete the specified branch, even if it has unmerged changes. 

7. `git branch -d` [branch-name]
    * Delete the specified branch. This is a “safe” operation in that Git prevents you from deleting the branch if it has unmerged changes.

8. `git branch -m` [branch-name] 
    * rename branch

9. `git branch -a`
    * list all remote branches.

10. `git branch -vv`
    * check if your local branch is behind, ahead. 
    * Example:   
        - master       58ec21ac [origin/master] update changelog
        - test-branch  58ec21ac update changelog

11. `git checkout` [branch-name]
    * switch between branches

12. `git checkout -b` [branch-name]
    * create new branch 

13. `git commit -m` "any-comment"

14. `git commit --allow-empty -m` "any-comment"
    * allow empty commits, no changes

15. `git pull origin` [branch-name]
    * update local branch. ex: git pull origin master

16. `git push origin` [branch-name]
    * used to publish local changes to a central repository.

17. `git merge origin/master`
    * update local branch with master   

18. `git restore` [file-name] and `git restore .` 
    * remove file or changes before `git add .`  

19. `git restore --staged` [file-name] and `git restore --staged .`
    * It will discard any local, uncommitted changes. 
    * Exemple: To remove changes after execute `git add .`  

18. `git clean -f - d` [file-name]     
    * delete untracked files

20. `git log`
    * show commit logs     

21. `git reset –hard` [commit]    
    * This command discards all history and goes back to the specified commit.
    * `git reset --hard HEAD^` going back to the commit before HEAD.
    * `git reset --hard HEAD~2` going back two commits before HEAD.

22. `git rebase -i HEAD~4` 
    * HEAD means where you are working [current_branch].
    * have 4 commits, but you haven’t pushed anything yet and you want to put everything into one commit.
    * 4 is the number of commits, can be any number.
    * all commits above: commit [commit-mumber] (origin/main, origin/HEAD)
