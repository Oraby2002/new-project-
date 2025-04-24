 delete a branch from your local machine:
git branch -d branch-name     # Safely delete (if merged)
git branch -D branch-name     # Force delete (even if not merged)

How to Checkout Another Branch Without Committing Current Changes :
git stash
git checkout other-branch