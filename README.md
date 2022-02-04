# hello-world
Hello World repository for Git tutorial
This is an example repository for the Git tutoial on https://www.w3schools.com

This repository is built step by step in the tutorial.

It now includes steps for GitHub. It's awesome!

Practice makes perfect 🦖

List of useful commands:
- git commit -a -m "commit message" (git add + git commit)
- git checkout -b newBranchName
- git branch -a
- git branch -r
- git status --short
- git log origin/master
- git diff origin/master
- git restore --staged fileName
- git fetch + git merge = git pull
- git remote -v (check remote)
- git remote rename origin upstream (rename origin from original project to upstream)
- git remote add origin https://...
- ssh-keygen -t rsa -b 4096 -C "test@w3schools.com" (create new SSH key pair)
- git remote set-url remote-name git@github.com:username/repository.git (change a remote origin from HTTPS to SSH)

Other tips:
- Branching is the key concept in Git. And it works around the rule that the master branch is ALWAYS deployable
- When you make a new branch, you will (almost always) want to make it from the master branch.
- Use descriptive names for new branches!
- Each commit should have a message explaining what has changed and why. Each commit becomes a part of the history of the branch, and a point you can revert back to if you need to.
- When a Pull Request is made, it can be reviewed by whoever has the proper access to the branch. This is where good discussions and review of the changes happen.
- According to Git naming conventions, it is recommended to name your own repository origin, and the one you forked for upstream
- It's possible to have additional -gitignore files in subdirectories


