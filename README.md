# git demo

git demo respository

## basic git command

- git init  (initialize an empty git repository)
- git status (show the working tree status)
- git add (add file contents to the index)
- git rm (Remove files from the working tree and from the index)
- git restore (Restore working tree files)
- git commit (Records the changes to repository)
- git log (show commit logs)

## git low level Commands

- git cat-file <SHA1>
 * -t (git object type)
 * -s (git object size)
 * -p (git object content)
- git ls-files
 * -s (Show staged contents' mode bites, object name and stage number in the outputs)


## branch

- git branch (list and branches we have)
- git branch <branch_name> (create a branch with branch_name, if there already have branch with the name you want to create, it will - return error)
- git branch -D <branch_name> (delete branch, can't delete current active branch or branch not existing)
- git checkout (change the current activate branch)
- git checkout -b <branch_name> ( checkout abranch, will create that branch if it doesn't exist)
- git branch -m <old_name> <new_name> (rename branch with new name)


Thanks
