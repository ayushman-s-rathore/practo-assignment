## Set your username and email in git config
```bash
   git config –global user.name ayushman-s-rathore
   git config –global user.email ayushman.rathore@practo.com
   ```
## Create a new branch named "feature-branch" and switch to it.
```bash
 git checkout -b feature-branch
 ```
## List all branches in the repository.
```bash
  git branch
  ```
  ![alt text](<Screenshot 2024-06-25 at 9.49.58 PM.png>)
## Delete the branch “feature-branch”
  ![alt text](<Screenshot 2024-06-25 at 9.53.13 PM.png>)
## How do you undo the last commit

```bash 
git revert head
```
## Create a new branch names “conflict-branch”
```bash
git checkout -b conflict-branch
```
## Create a another branch named “feature1”
```bash
git checkout -b feature1
```
## Make some changes in to feature1 branch

Merge “feature1” branch into main branch
Make changes in “conflict-branch”, in the same file and line that you had made changes in feature1
Merge master into conflict-branch [Attach screenshot of terminal & file]
Resolve merge conflicts
Add a remote named "origin" pointing to a GitHub repository.
Fork a repository on GitHub and clone it to your local machine.
Create a new branch on your fork, make changes, and open a pull request to the original repository.
Comment on a PR and suggest improvements
Create a Git alias for the command `git log --oneline` named `gitlol`.
Create a pre-commit hook
You have made local changes in your branch, but you need to switch to another branch urgently without committing. How would you handle this situation?
You accidentally deleted a file in your local repository. How do you restore it using Git?
You have committed changes to your branch but forgot to include a file. How do you add the file to the last commit without creating a new commit?
You want to discard all changes in your working directory and revert to the last commit. What Git command would you use?
You need to view a specific commit's changes. What Git command can be used to show the changes introduced by a particular commit?
You want to change a commit message, after you have already committed, how do you do so?
Your colleague has made changes in their branch, and you want to incorporate those changes into your branch without merging. How do you achieve this?
You've made several commits on a branch, but you want to club them into a single commit before pushing to the remote repository. How would you do that?
You accidentally staged a file that you don't want to commit. How do you unstage it?
You don’t want to commit files that have .yml in the end, and also files inside folder config. How do you do that?
You want to see a list of all the files changed in the last commit. What Git command would you use?
You realize that your local branch is outdated, and you want to fetch the latest changes from the remote repository. How do you do this without merging?
You accidentally deleted a branch. How do you recover it?
You want to remove untracked files and directories from your working directory. What Git command would you use?
You have a commit from a feature branch that you want to apply to the main branch without merging the entire feature branch.
You mistakenly committed a change to the wrong branch and need to apply that commit to the correct branch.
There is a series of commits on a feature branch, but you only want to cherry-pick a specific range of commits. 
You want to clone a GitHub repository onto your local machine, but you only need a specific branch. How can you achieve this?
You've made changes to your local repository and want to push them to your fork on GitHub. What Git commands would you use?
You want to create a new branch both locally and on GitHub to work on a new feature. What commands would you use?
You want to see the commit history of a GitHub repository. How can you do this using Git commands?
You've accidentally committed sensitive information and want to remove the commit from both your local and remote repositories on GitHub. What commands would you use?
You want to delete a remote branch on GitHub. What Git command would you use?
Create a git repository for all your assignments and upload them in it. Ask your peers to code review it, and you need to code review your peers assignments
Create a pull request on any open source library on github, attach the pull request link to the readme file of this project’s repository

