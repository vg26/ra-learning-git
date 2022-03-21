- git branch (to check on which branch i'm on)
- git pull (to make sure the main branch is up to date)
- git checkout -b feat/git-exercise-3 (created new branch and check it out)
- git branch (to confirm that i'm on the newly created branch)

Created new folder named git-exercise-3 and a readme file with description in it

- git add . (to stage the changes)
- git status (to check if the changes are staged)
- git commit -m "Created new branch and added description"
- git push --set-upstream origin feat/git-exercise-3 (pushed the changes to remote)

 Updated the readme file

- git branch (check if i'm on the feat/git-exercise-3 branch since i have to create the new branch from it)
- git checkout -b fix/git-exercise-3 (created the new branch)
- git add . (to stage the changes)
- git status (to check if the changes are staged)
- git commit -m "Modified the readme file"
- git checkout feat/git-exercise-3
- git merge fix/git-exercise-3

 