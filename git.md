# Git

### Git is a VCS (Version Control System) where you can view, apply, and remove changes. It's working "under the hood" and we can give it commands utilizing GitHub, the terminal, and VS Code. It stores data in a file system made out of snapshots (the stages of your workflow).

### Other facts about Git:
- There are 3 states: Committed, Modified, and Staged
- The most recent commit is called the "Head", indicating where you currently are
- This VCS allows for multiple developers and teams to work on the same code at once

Steps of Revision between GitHub and the Terminal:
1. GitHub: Create and clone the repository

Terminal:
1. Add the URL of the repo: git clone "https://..."
1. cd learning-journal/
1. git remote -v
1. git status: to know if you have anything to commit
1. code . : to open the file in VS code
1. After making a change to the repo on VS code, you save it.
1. git status: "Changes not staged for commit"
1. git branch: tells you where you are, i.e. "Master"
1. git add README.md
1. git commit -m "to see changes" : this is the comment you leave about why you made changes
1. The terminal then responds with a unique ID code for the snapshot
1. git status
1. git push : Then changes are pushed to GitHub

