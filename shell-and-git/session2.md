## Create new branch:

git switch -c branch-name

## upload the updates and the new branch(but for first time):

git push -u origin branch-name

## Delete a branch locally after merging:

git branch -d branch-name

## Check the current status of the repository:

git status

## Stage all changes before committing:

git add .

## Commit changes with a message:

git commit -m "Added notes on GitHub and Markdown"

## Push changes to GitHub:

git push origin branch-name

# Pull Requests (PRs) Workflow

#### Push your branch to GitHub.

#### Go to the repository on GitHub and create a Pull Request (PR).

#### Share the PR link with your team for review.

#### Make updates if needed and push again to update the PR.

#### Merge the PR once it is approved.

## Update your local main branch:

git checkout main
git pull

#### Delete the branch locally and on GitHub if no longer needed.
