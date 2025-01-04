-How to Remove Branches
-Locally
git branch -d test
-Remotely
git push origin --delete dev
_________________________________
-Annotated Tags and Lightweight Tags
Annotated Tags: Git objects that store metadata like the tagger's name, email, date, and a message
Lightweight Tags: pointers to a specific commit. don't store additional metadata
_________________________________
-Rebase
Rebase is useful to keep a clean, linear commit history. Use it when you want to incorporate upstream changes into your branch before merging.
Use `git rebase` instead of `git merge` 
_________________________________
-List tages
git tag
-Delete tag
## Locally
git tag -d v1.7
## Remotely
git push origin --delete v1.7
![luv](./luv.jpg)
