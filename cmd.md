# Git Command Reference

1. Basic Git Setup
git --version
which git
git config --global user.name "tanuj kumar"
git config --global user.email "taujkumar@gmail.com"
git config --list

2. Repository Initialization
mkdir git-for-devops
cd git-for-devops/
git init

3. File Operations
touch tanuj.txt
touch meera.txt
rm meera.txt
mkdir meera.tx
ls
ls -a
ls -al

4. Adding Files to Staging Area
git add meera.txt
git add tanuj.txt
git add .

5. Removing Files
git rm tanuj.txt
git rm -f tanuj.txt
git restore --staged tanuj.txt

6. Commit Changes
git commit -m "this is demo file"
git commit -m "this is demo file2"
git commit -m "this is of meera's file"
git commit -m "this is sonu file on dev branch"

7. Check Status and Logs
git status
git log
git log --oneline

8. Branching and Switching Branches
git branch
git branch luxmi
git branch dev
git checkout luxmi
git checkout dev
git checkout master

9. Miscellaneous Commands
git --help
cat meera.txt
