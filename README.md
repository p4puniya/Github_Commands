# Getting Started with GIT & Github

### Use the link below to download Git:
- Git: https://git-scm.com/downloads

### After the download is complete, install the downloaded file.

# Git Commands

Some important git commands and their uses:
1. git add -A: Select all files present in your current repo.
2. git commit -m "*Message*": Commit all the changes and add a message for your commit.
3. git push: push your changes.

**NOTE**:
If you are pushing the changes for the first time, the *git push* command may throw the following errors:
- git push --set -upstream: This command tells a remote repository to create a new branch to support the new branch and commit history that is about to be pushed to it.

- Using Git push without initializing the username/email:
```
fatal: unable to auto-detect email address(got 'username@hostname.(none)')
```
To resolve them, you can set your username and email for committing changes globally with:
``` 
git config --global user.name "Your-User-Name";
git config --global user.email "your.email@example.com"
```
After setting these two, you should be able to push the changes.

4. git branch: See all branches related to your repository.
5. git checkout *Branch-Name*: Change the branch you are working on.
6. git checkout -b *Branch-Name*: create a new branch with the given name.
7. git merge *name*: merge the said branch on the current branch.
8. git branch -d *name*: delete the said branch.
