# Git commands

| Git command                                    | Description                                                  |
|-------------------------------------------------|---------------------------------------------------------------|
| `.gitignore`                                   | Git to ignore the file.                                      |
| `git add .`                                    | Adds every modified files into staging mode.                 |
| `git add <FILE_NAME>`                          | Adds the file to the staging mode.                           |
| `git commit -a`                                | Commits every tracked file.                                  |
| `git commit -m "<Your message>"`               | Commit the staged changes with a message.                    |
| `git commit`                                   | Commit the staged changes.                                   |
| `git diff --cached`                            | It shows your staged changes.                                |
| `git diff`                                     | It shows the exact lines you added or removed.               |
| `git init`                                     | To initiate the working folder.                              |
| `git log --pretty=format:"%h - %an, %ar : %s"` | Summarizes the commits in your repository with format.       |
| `git log --pretty=oneline`                     | Summarizes the commits in your repository.                   |
| `git log`                                      | Lists the commits in your repository with abbreviated stats. |
| `git rm <FILE_NAME>`                           | Removes your file.                                           |
| `git status -s`                                | Provide a short status description.                          |
| `git status`                                   | To get the current status of the working folder.             |