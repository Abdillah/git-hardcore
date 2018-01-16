# git-hardcore
Mastering the tricks of git-scm.

## What've done here?

### Checkout feature - Rebase master - Pull rebase - Merge to master
Duplicated commits on Rebase master operation, and continue duplicated when
Merged into master.

### Checkout feature - Rebase master - Pull rebase fast-forward only algo 'ours' - Merge to master
Duplicated commits on Rebase master operation, and continue duplicated when
Merged into master. In addition commits from feature branch reverted,
thus useless :sad:. It maybe due to algorithm choosen to merge: 'ours'.

### Checkout feature - Merge from master - Push feature - Merge to master
Merge from master were successful and vice versa. The push clean and tidy.
But the commit message from master retained in last "Merge to master",
thus a bit cluttered commit history.

### Checkout feature - Cherry pick from master - Merge to master
