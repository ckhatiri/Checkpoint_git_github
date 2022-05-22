# Checkpoint_git_github
1-Create a folder called learn_git.
mkdir learn_git
2-cd into the learn_git folder.
cd learn_git
3-Create a file called third.txt.
echo "" > third.txt
4-Initialize an empty git repository.
git init
5-Add third.txt to the staging area.
git add third.txt
6-Commit with the message "adding third.txt".
git commit -m "adding third.txt"
7-Check out your commit with git log.
git log
8-Create another file called fourth.txt.
echo "" > fourth.txt
9-Add fourth.txt to the staging area.
git add fourth.txt
10-Commit with the message "adding fourth.txt"
git commit -m "adding fourth.txt"
11-Remove the third.txt file.
rm third.txt
12-Add this change to the staging area.
git add .
13-Commit with the message "removing third.txt".
git commit -m "removing third.txt"
14-Check out your commits using git log.
git log
15-Change your global setting to core.pager=cat - you can read more about that here.
git config --global core.pager "cat"
16-Write the command to list all of the global configurations for git on your machine. You can type git config
--global to find out how to do this

git config --global --list
