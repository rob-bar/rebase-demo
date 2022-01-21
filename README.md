Let's go over the git guidelines once more [10mins]

- rewrite history of your feature branch

1. git rebase -i {COMMIT HASH RIGHT BEFORE THE COMMIT WE WANT TO SQUASH UPON}
2. The interactive editor opens (choose commits)
3. when ok, form message

- rebase your feature branch upon the main (so you are up to date)
- resolve conflicts during a rebase session (conflicts can always happen)

Every commit in our local branch gets compared with the commits on the branch which we are rebasing on

-> Fix conflict

rebase --continue
rebase --abort

- revisit your git alias & config files
