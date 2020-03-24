# How to undo commits

Commits can be undone with `git reset --hard`.

To undo the last commit, one can use `git reset --hard HEAD^`
To undo the X (1, 2, 3...) last commits one can use `git reset --hard HEAD~X`

To undo the commit but keep the changes, the `--hard` switch can be ommited from the commands.
