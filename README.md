1. Checked if i have installed everything i need (git,node,VScode)
    -git --version
    -node --version

2. Configured git username and email
    -git config --global user.name "vg26"
    -git config --global user.email "vlad.gulabovski@gmail.com"

3. Created new repository on Github and cloned that repository 
    -git clone https://github.com/vg26/ra-learning-git.git

4. Opened that repository in VScode 

4. Added that description in the readme file and commit and pushed the changes
    - cd Downloads/ra-learning-git/ (go to repository location)
    - git branch (check if we are on the main branch)
    - git status (it shows the readme file as modified)
    - git add . (to stage the modified file)
    - git status (to confirm if the files are staged and ready to commit)
    - git commit -m "Added the description in the readme file" (commited the changes)
    - git push (pushed the changed to remote)

 File has been updated to simulate the git rebase flow