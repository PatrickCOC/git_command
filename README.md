# git_command
Mandatory push

    git push -f
    git --force

Merge pull 

    git pull --rebase   

Checkout

    git checkout [branch name]   

Undo Commit

    git reset --soft HEAD~
#    
    TIP: Add a number to the end to undo multiple commits. 
    For example, to undo the last 2 commits 
    (assuming both have not been pushed) 
    run :
    git reset --soft HEAD~2
#
    NOTE: git reset --soft HEAD~ is the same as git reset --soft HEAD^ which you may see in Git documentation.

Localbranch 

    git checkout -b [new branch name]
## gitHub push requir username and password
    git remote set-url origin git@github.com:username/repo.git
    git remote -v

Tag

    git tag
    git tag -l "v1.8.5*"
   
    git tag -a v1.4 -m "my version 1.4"
   
    git show v1.4
   
    git push origin v1.5
    git push origin --tags
   
Remove
    rm -fr .git
