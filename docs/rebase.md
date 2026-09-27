# Git Rebase Demonstration

The eature/rebase-demo branch was created from main and received two commits.

Main was then updated with another commit.

The feature branch was rebased using:

git fetch origin
git rebase origin/main

This replayed the feature commits on top of the updated main history.
