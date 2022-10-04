# Reset author from any commit and after
git rebase -r <[COMMIT_HASH|--root]> --exec 'git commit --amend --no-edit --reset-author'