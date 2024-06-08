# ** DevOps Digital Course: Git/Versioning. My Notes. # -----------------------------------------------------------------------------------**
# **States of a file viewd by Git in my words:**
## UNTRACKED: A file that belongs to your workspace but It isn't tracked by the git, this implies that the git don't have the commit history (version control) from this file and It need to be added into staging area (Staged) : "git add 'file'". If you want to ignore a untracked file in your version control, you can use the file ".gitignore". But, remember, you need to add and commit the file ".gitignore" to have it's version control too.
## UNMODIFIED: The file is already tracked by the git and it belongs to the last commit (the newest version).
## MODIFIED: The git knows that the file was modified and If you want It in the next commit, you need to use "git add".
## STAGED: The file that you used "git add", cames to this state (staging area), It is ready to be reviwed before the commit.


# **Essential git comands, quick summary with my words and learning ------------------------------------------------**
* git config - Configures setting at various levels. The settings include user information, default editor, and other.
* git branch - Manages branches in a Git repository
* git checkout - Switches branches
* git merge - Merge two or more branches
* git status - Shows the current state of the working directory and staginf area
* git log - Displays the commit history
* git restore - Restores working tree files (#MODIFIED -> #UNMODIFIED)
* git diff - Shows the differences between commits, branches, files, etc. (DIFFERENCES BETWEEN #MODIFIED AND #UNMODIFIED)
* git remote - Manages remote repositories
* git push - Sends commits to a remote repository
* git pull - Fetches and integrates from a remote repository
* git fetch - Downloads objects and refs from a remote repository (pull changes the local files, fetch just hold and you can see the differences between the repository and the local files with git diff)

* For a deep learn about all of the command, you can use "git help <command>".
## ------------------------------------------------------------------------------------------------------------------ 
