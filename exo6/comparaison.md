# Comparison: Merge vs Rebase

## Exercise 5 - Merge

- Uses "git merge".
- Creates a merge commit.
- Preserves the complete branch history.
- The history is not linear.

## Exercise 6 - Rebase

- Uses "git rebase".
- Does not create a merge commit.
- Replays feature commits on top of the latest main branch.
- Produces a clean and linear history.

## Conclusion

Merge preserves the true history of branches, while rebase rewrites the feature branch history to make the commit history cleaner and easier to read.