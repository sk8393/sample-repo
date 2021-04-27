# sample-repo
Switched to dev branch.

Merged dev branch to main branch without fast forward.

First commit in dev branch.

Second commit in dev branch.

dummy was created in previous commit.

Third commit in dev branch to test --abort option.

1 squash

2 squash

3 squash

a fixup

b fixup

c fixup

Commit on Ubuntu server.

Conducted test of branch and rebase.  In dev branch, I deleted a directory created in main branch and created another new directory that main branch is not aware of.  Switching back to main branch (checkout) did not cause any problem.  The new directory was not there, and the directory dev deleted was reverted.  Merge without fast forward also worked well.  After merging dev branch to main branch, main is one commit ahead of dev.  "git rebase main dev" move dev forward, at the latest commit of main."

Before merge in a.

Before rebase in a.

Before rebase in b.

initial commit for git reflog.

minor fix for git reflog.

minor fix again for git reflog.

initial commit for git reflog with hard reset.

minor fix for git reflog with hard reset.

minor fix again for git reflog with hard reset.

1st commit for cherry pick in main.

2nd commit for cherry pick in main.
