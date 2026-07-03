# git-workflow
Steps 1-7 are in the local repo\
Steps 8-9 are on Github\
Steps 11-13 are back in the local repo
1. git clone <url to ORI repo> or git init
2. git branch
3. git checkout -b new-branch-name
4. Implement new features in this branch
5. git add .
6. git commit -m "insert message here"
7. git push origin new-branch-name
8. compare branches
9. create pull request for new-branch-name
10. merge (which also deletes branch in the repo)
11. git checkout main
12. git pull origin main
13. git branch -d new-branch-name
