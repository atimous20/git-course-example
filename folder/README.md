# Example Git Repository

We are learning how to make commits.

1. make some changes
2. git add -- "stage" the changes that we want to persist to our git history
3. git commit -m "adding ..." -- creates a commit

We are about to make a commit without best practices.

# Word of advice -- Commit early, commit often in software development

hi

goodbye

docs

# created the repo locally
local repository -> "remote" repository (git add remote <name> <URL>)

# created the repo remotely
git clone <URL>

# create a branch locally
git checkout <branch>
git checkout -b <new branch name>
git add ...; git commit -m "..." (several times)
git push --set-upstream origin <new branch>
git pull

# create a new branch remotely
using the Github UI to create <branch>
git fetch -- all
git checkout <branch>
