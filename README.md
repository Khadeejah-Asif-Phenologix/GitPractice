# GitPractice

<!-- //To clone a repository -->
git clone "repository link"

<!-- //To check the status of the git files  -->
<!-- Untracked - U -->
<!-- Modified - M -->
git status

<!-- //To add files in the git -->

<!-- To add a specific file  -->
git add <filename>

<!-- To add all the files that you have worked on -->
git add .

<!-- //Commit Changes to the repository -->
git commit -m "Commit message"

<!-- //Push the files to the github -->
git push
git push origin <branchName>

<!-- To get information of the commits made so far -->
git log

<!-- To get information of commits made so far in short form -->
git log --oneline

<!-- .gitignore -->
Add the filenames that are confidential in this file and that we don't want to commit in GitHub

<!-- To check in which branch we are currently in -->
git branch

<!-- To create a new branch -->
git branch <branchName>

git checkout -b <branchName>

<!-- To switch branch -->
git switch <branchName>

git checkout <branchName>

<!-- To add an upstream branch -->
git push --set-upstream origin <branchName>

<!-- To make a new branch & then switch into it -->
git switch -c <branchName>

<!-- To merge data from a branch of a Github -->
git merge <branchName>

