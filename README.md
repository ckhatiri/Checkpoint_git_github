# Checkpoint_git_github <br>
1-Create a folder called learn_git.<br>
mkdir learn_git<br>
2-cd into the learn_git folder.<br>
cd learn_git<br>
3-Create a file called third.txt.<br>
echo "" > third.txt<br>
4-Initialize an empty git repository.<br>
git init<br>
5-Add third.txt to the staging area.<br>
git add third.txt<br>
6-Commit with the message "adding third.txt".<br>
git commit -m "adding third.txt"<br>
7-Check out your commit with git log.<br>
git log<br>
8-Create another file called fourth.txt.<br>
echo "" > fourth.txt<br>
9-Add fourth.txt to the staging area.<br>
git add fourth.txt<br>
10-Commit with the message "adding fourth.txt"<br>
git commit -m "adding fourth.txt"<br>
11-Remove the third.txt file.<br>
rm third.txt<br>
12-Add this change to the staging area.<br>
git add .<br>
13-Commit with the message "removing third.txt".<br>
git commit -m "removing third.txt"<br>
14-Check out your commits using git log.<br>
git log<br>
15-Change your global setting to core.pager=cat - you can read more about that here.<br>
git config --global core.pager "cat"<br>
16-Write the command to list all of the global configurations for git on your machine. You can type git config
--global to find out how to do this<br>

git config --global --list<br>
