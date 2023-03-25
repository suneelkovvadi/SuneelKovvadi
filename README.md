GIT commands along with their syntax and use:

1. git init
Syntax: git init [directory]
Use: Initializes a new Git repository in the specified directory or the current directory if not specified.

2. git clone
Syntax: git clone [repository_url] [directory]
Use: Creates a copy of the specified remote Git repository in the specified directory or the current directory if not specified.

3. git add
Syntax: git add [file/directory]
Use: Adds the specified file or directory to the staging area to be committed in the next commit.

4. git commit
Syntax: git commit -m "commit message"
Use: Records changes made to the repository with a commit message describing the changes.

5. git status
Syntax: git status
Use: Displays the current status of the repository, showing which files are staged, modified, or untracked.

6. git branch
Syntax: git branch [branch_name]
Use: Lists all local branches in the repository or creates a new branch with the specified name.

7. git checkout
Syntax: git checkout [branch_name]
Use: Switches to the specified branch, updating the working directory to match the content of that branch.

8. git merge
Syntax: git merge [branch_name]
Use: Combines changes from the specified branch into the current branch.

9. git push
Syntax: git push [remote] [branch]
Use: Pushes the local commits to the specified remote repository and branch.

10. git pull
Syntax: git pull [remote] [branch]
Use: Fetches the changes from the specified remote repository and merges them into the current branch.

11. git fetch
Syntax: git fetch [remote]
Use: Fetches the latest changes from the specified remote repository without merging them into the current branch.

12. git diff
Syntax: git diff [file]
Use: Shows the differences between the working directory and the staging area or between different commits.

13. git log
Syntax: git log
Use: Displays a list of commits in the repository, showing their commit messages, authors, and timestamps.

14. git reset
Syntax: git reset [file]
Use: Removes the specified file from the staging area or undoes a commit, resetting the repository to a previous state.

15. git rm
Syntax: git rm [file]
Use: Removes the specified file from the repository and the working directory.

16. git mv
Syntax: git mv [old_file] [new_file]
Use: Renames the specified file in the repository and the working directory.

17. git tag
Syntax: git tag [tag_name]
Use: Creates a new tag at the current commit with the specified name.

18. git fetch
Syntax: git fetch [remote]
Use: Fetches the latest changes from the specified remote repository without merging them into the current branch.

19. git stash
Syntax: git stash
Use: Temporarily stores changes made to the working directory, allowing the user to switch to a different branch or commit before restoring the changes.

20. git bisect
Syntax: git bisect [good_commit] [bad_commit]
Use: Helps find the commit that introduced a bug by performing a binary search on the commit history.

21. git revert
Syntax: git revert [commit]
Use: Creates a new commit that undoes the changes made in the specified commit, leaving the repository in its previous state.
