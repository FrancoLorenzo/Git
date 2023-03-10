# Git commands

| Git command | Description |
|---|---|
| `.gitignore` | Git to ignore the file. |
| `$ git tag -a v1.2 <Tag ID>` | It allows you to tag an existing commit. |
| `git add <file>` | Update the file you want to commit. |
| `git branch <BRANCH-NAME>` | This command creates a new branch. |
| `git checkout  <BRANCH-NAME>` | It switches to the branch you need. |
| `git checkout -- <file>` | Unstage/unmodify the file you need. |
| `git commit -a` | Commits every tracked file. |
| `git commit -amend` | Undo commits. |
| `git commit -m "<Your message>"` | Commit the staged changes with a message. |
| `git commit` | Commit the staged changes. |
| `git diff --cached` | It shows your staged changes. |
| `git diff` | It shows the exact lines you added or removed. |
| `git init` | To initiate the working folder. |
| `git log --oneline --decorate --graph --all` | It prints your commit history. |
| `git log --pretty=format:"%h - %an, %ar : %s"` | Summarizes the commits in your repository with format. |
| `git log --pretty=format:"%h %s" --graph` | Summarizes the commits in your repository with format. |
| `git log --pretty=oneline` | Summarizes the commits in your repository. |
| `git log` | Lists the commits in your repository with abbreviated stats. |
| `git merge <BRANCH-NAME>` | It merges the branch you need. Make sure to checkout to the main/master branch first. |
| `git pull` | Fetches and merges a remote branch. |
| `git push origin [tagname]` | `git push` doesn't automatically push tags, so you need to push them manually. |
| `git push origin master` | Push changes to your master branch |
| `git remote -v` | List the shortnames for each of your remote repositories with URL. |
| `git remote rename` | Rename remote repositories. |
| `git remote rm` | Remove remote repositories |
| `git remote show [remote-name]` | Show information about a particular remote repository. |
| `git remote` | List the shortnames for each of your remote repositories. |
| `git reset` | It resets your staging area changes. |
| `git rm <FILE_NAME>` | Removes your file. |
| `git show` | Show the the tag data. |
| `git status -s` | Provide a short status description. |
| `git status` | To get the current status of the working folder. |
| `git tag -a` | Create new tags. For example, `git tag -a v1.0 -m "my version 1.0"` |
| `git tag` | List available Git tags. |
| `git branch --merged` |Filter the list of merged branches.|
| `git branch --no-merged` |Filter the list of branches that aren't merged.|
| `git branch -d <BRANCH-NAME>` |It deletes your branch.|
| `git branch -v` |Displays the last commit for each of your branches.|
| `git fetch origin` |Search and update any data you don't have from your remote server.|