# git-commands


```sh
docker-compose up -d --build
```

## …or create a new repository on the command line
```sh
echo "# springboot-JWT" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kaushleshtripathi/springboot-JWT.git
git push -u origin main
```

## …or push an existing repository from the command line
```sh
git remote add origin https://github.com/kaushleshtripathi/springboot-JWT.git
git branch -M main
git push -u origin main
```

===========================================
```sh
git init -b main
@@ or
git init
git add .
@@ or 
git add <file>: Add Specific file
git commit -m "<message>"
git remote add origin https://github.com/kaushleshtripathi/spring-batch-job.git
git push -u origin HEAD:main
@@ or
git push -u origin main
```

```sh
git status
git log: see history of commit
git branch: list the branches
git branch --all: list all branches local and remote
git diff
git remote -v
```
## Delete a branch
```sh
git branch -d <branchName>
```

## Remove file
```sh
git rm --cached <filename>
git commit -m "<message>"
```

## Git Clone
```sh
git clone https://github.com/kaushleshtripathi/spring-batch-job.git --branch main
```

```sh
## Git Version
git tag -a v1.0 -m "<message>"
git push origin v1.0
```

## Create a new branch
```sh
git switch -c <branchName>
or
git checkout -b <branchName>
```
## Switch to a branch
```sh
git switch <branchName>
or
git checkout <branchName>
```

## Merge changes from main to feature
```sh
git pull origin main
git switch main
git merge feature: this will merge changes from main to feature branch
```

## Save changes without commiting
```sh
git stash: Save changes without commiting
git stash list
git stash apply
```
