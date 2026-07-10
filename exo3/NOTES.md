git reset --soft removes the last commit but keeps changes staged for a new commit.
git reset --mixed removes the last commit and keeps changes unstaged in the working directory.
git reset --hard removes the last commit and deletes the changes completely.
--soft is useful for editing commits, --mixed for reworking changes, and --hard for discarding work.