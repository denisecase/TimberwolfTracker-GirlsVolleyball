# Notes 

These are for those with the ability to deploy the skill.

## Git Remotes

There are 2 git remotes:

- the AWS deployment site (origin)
- the GitHub repo (github)

Create the first one from within the Alexa Developers console.

Then (just once) open a bash shell and run:

`git remote add github https://github.com/denisecase/TimberwolfTracker-GirlsVolleyball.git`

## Branches 

The origin remote has 2 branches (at least): master and prod.

The github remote has just main.

Switch between branches to push to both places. 

To push change to GitHub as well, change branch, verify, push, and return to master:

```
git branch -M main
git branch
git push github main
git branch -M master
git branch
```
