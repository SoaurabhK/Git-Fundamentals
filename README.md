# GitCourse

This will explain git fundamentals

Your username shouldn't be an email address, but your GitHub user account: pete.
And your password should be your GitHub account password.

You actually can set your username directly in the remote url, in order for Git to request only your password:
```
cd C:\Users\petey_000\rails_projects\first_app
git remote set-url origin https://pete@github.com/pete/first_app
```
View the repository name with 
```
git remote -v
```
And you need to create the fist_app repo on GitHub first: make sure to create it completely empty, or, if you create it with an initial commit (including a README.md, a license file and a .gitignore file), then do a git pull first, before making your git push.

Reference - http://stackoverflow.com/questions/25337199/remote-repository-not-found-fatal-not-found

