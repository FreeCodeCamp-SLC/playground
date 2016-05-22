Terms:
  - WorkArea - the working directory where you'll code the changes
  - Staging - where you'll place modified files ready to be committed
  - Local - Local repository
  - Remote - Remote repository

Create a local Repository from playground
  - git clone https://github.com/FreeCodeCamp-SLC/playground

Your local respository
  - git status (list new or modified files you haven't committed)
  - git diff (show changes to files not yet staged)
  - git diff <commit1> <commit2> (show differences between two commit ids)
  - git log (show the change history for the branch your working on)

Working with Branches
  - git branch (show all local branches)
  - git branch -av (show all local and remote branches)
  - git branch <new branch name> (create a branch to work on ... the name should describe what you plan to do)
  - git checkout <branch name> (switch to a branch to work on it ... note: do this so you're not working on the master branch)
  - git branch -d <branch name> (delete a branch.  Generally will do this after the changes you made in the branch have been
                                 committed to the master branch)
  - git merge <branch1> (merge changes from another branch into currently active branch)

Making changes
  - git add <filename> (add a moddified file to the staging area)
  - git commit -m "commit message" (commit the staged files.  comment message describes what you modified with the commit)

Synchronizing
  - git fetch (fetch latest changes from the origin ... doesn't merge)
  - git pull (Fetch and merge latest changes from origin)
  - git push (push local changes to origin)

Help
  - git command --help (get help with git)
