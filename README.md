# git-commands

# …or create a new repository on the command line
echo "# springboot-JWT" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kaushleshtripathi/springboot-JWT.git
git push -u origin main
# …or push an existing repository from the command line
git remote add origin https://github.com/kaushleshtripathi/springboot-JWT.git
git branch -M main
git push -u origin main

===========================================
git init -b main
# or
git init
git add .
# or 
git add <file>: Add Specific file
git commit -m "<message>"
git remote add origin https://github.com/kaushleshtripathi/spring-batch-job.git
git push -u origin HEAD:main
# or
git push -u origin main

git status
git log: see history of commit
git branch: list the branches
git branch --all: list all branches local and remote
git branch -d <branchName>: delete a branch
git diff
git remote -v

git rm --cached <filename>
git commit -m "<message>"

git clone https://github.com/kaushleshtripathi/spring-batch-job.git --branch main

git tag -a v1.0 -m "<message>"
git push origin v1.0


git switch -c <branchName>: create a new branch
git switch <branchName>: switch to a branch

Merge
git pull origin main
git switch main
git merge feature: this will merge changes from main to feature branch

git stash: Save changes without commiting
git stash list
git stash apply
