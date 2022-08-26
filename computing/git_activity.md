# git activity

Today, you're going to play a bit with git, interacting with, creating, and reverting repos.  Pull this up, just in case <https://training.github.com/downloads/github-git-cheat-sheet.pdf>, and then do the following.

1. List the commits to this (css_bootcamp_2022) repository and find the commit ID for the commit which 'Added git activity'.
2. Shortly after, Will committed a deep, dark secret to the repository in the css_bootcamp_2022/computing folder.  He then got cold feet, and deleted his secret. Use git checkout to reload the state of the repository at the time of that commit, and read his deep dark secret using `vim`.
3. Now that you're SHOCKED, revert to the main with `git reset --hard` which will delete ALL CHANGES and return to the latest commit.
4. The file 'boringfile.txt' wasn't always so boring.  Use `git log --follow --name-status` to find its original filenames and the commits in which it changed.
5. Now, go to your home directory and make a new folder.  Initialize a new git repo there.
6. Create a file with some text in `vim` or `nano`, and then add and commit that file with a 'Hello World' message.
7. Copy in a file from another folder to your repository, and then try to commit without running add first.  Then, add the file and successfully commit.
8. On second thought, you don't need that garbage. Get the commit ID of the file before you added that junk, and then clear it out of there by running `git reset (commit id)`.
9. Go back to the `css_bootcamp_2022` repo.  Use a `git log --follow` to figure out the commits where this file (git_activity.md) changed.
10. Now, compare two of those commits directly, using `git diff ID1 ID2 git_activity.md`

