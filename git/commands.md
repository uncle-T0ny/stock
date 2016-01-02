##merge without autocommit
git merge v1.0 --no-commit --no-ff

## tree view
git log --graph --pretty=oneline --abbrev-commit

## show changed files in commit
git show --pretty="format:" --name-only revision-number

## checkout restore file from branch or revision number.
git checkout 'branch or revision number' 'relative path to file'
git checkout origin/master proftrading/src/main/java/com/pfsoft/backoffice/actions/UserAction.java

## add repository 
git init 
git remote add origin https://github.com/uncle-T0ny/test.git

## create remote branch
first, you create branch locally
git checkout -b your_branch
The remote branch is automatically created when you push it to the remote server.

git push "remote name" <branch name>
"remote name" - is typically origin