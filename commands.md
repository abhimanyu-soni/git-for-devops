Here’s the information formatted for a Markdown (.md) file:

```markdown
# Git Commands for DevOps

## 1. `git`
Invokes Git to execute various commands. Essential for all subsequent Git operations.

## 2. `git version`
Displays the current version of Git installed on your system. Useful for ensuring compatibility with features.

## 3. `pwd`
Prints the current working directory in the terminal. Helps confirm your location in the file system.

## 4. `mkdir git-for-devops`
Creates a new directory named `git-for-devops`. Used for organizing projects.

## 5. `ls -rlt`
Lists files and directories in reverse chronological order with detailed information. Useful for reviewing recent changes.

## 6. `cd git-for-devops/`
Changes the current directory to `git-for-devops`. Necessary for performing operations in the new directory.

## 7. `pwd`
Prints the current directory again to confirm that you're in the right place.

## 8. `vim hello-dosto.txt`
Opens (or creates) a file named `hello-dosto.txt` in the Vim text editor. Used for editing files.

## 9. `ls -rlt`
Lists files again to confirm the presence of `hello-dosto.txt`.

## 10. `git init`
Initializes a new Git repository in the current directory. This is the first step in version control for a project.

## 11. `ls -rlt`
Lists files to check the repository status after initialization.

## 12. `ls -a`
Lists all files, including hidden ones (those starting with a dot). Useful for checking configurations.

## 13. `git status`
Displays the current status of the repository, including staged and unstaged changes. Crucial for understanding what will be committed.

## 14. `touch nibba.txt`
Creates an empty file named `nibba.txt`. Used to create new files quickly.

## 15. `touch nibbi.txt`
Creates another empty file named `nibbi.txt`.

## 16. `ls -rlt`
Lists files to confirm the creation of `nibba.txt` and `nibbi.txt`.

## 17. `git statsu`
A typo intended to be `git status`. It checks the repository status.

## 18. `git add nibbi.txt`
Stages `nibbi.txt` for the next commit. Necessary to include changes in the next snapshot.

## 19. `git statsu`
Another typo for `git status`.

## 20. `git status`
Checks the status of the repository to see what’s staged and what’s not.

## 21. `git add nibba.txt`
Stages `nibba.txt` for the next commit.

## 22. `git status`
Displays the current status, confirming that both files are staged.

## 23. `git commit -m "adding nibba nibbi"`
Commits the staged changes with a message. This is how you save your progress in version control.

## 24. `git status`
Checks the status after committing to confirm that there are no pending changes.

## 25. `ls`
Lists the files in the current directory.

## 26. `rm nibbi.txt`
Removes `nibbi.txt` from the working directory. Useful for cleaning up unnecessary files.

## 27. `git status`
Verifies the status after deletion to ensure the file is no longer tracked.

## 28. `git restore nibbi.txt`
Restores the deleted `nibbi.txt` file from the last commit. This is useful if you accidentally delete a file.

## 29. `git status`
Confirms that `nibbi.txt` has been restored.

## 30. `vim nibbi.txt`
Opens `nibbi.txt` for editing.

## 31. `git statsu`
Another typo for `git status`.

## 32. `git status`
Checks the current status of the repository.

## 33. `git add nibbi.txt`
Stages `nibbi.txt` again for the next commit.

## 34. `git status`
Verifies the status of the staged changes.

## 35. `rm hello-dosto.txt`
Removes the `hello-dosto.txt` file from the working directory.

## 36. `git status`
Checks the status after the deletion.

## 37. `git commit -m nibbi.txt "added contents"`
Commits changes to `nibbi.txt` with a message, but the syntax is incorrect. Should be `git commit -m "added contents" nibbi.txt`.

## 38. `git branch`
Lists all branches in the repository. Useful for managing multiple lines of development.

## 39. `vim nibba.txt`
Opens `nibba.txt` for editing.

## 40. `git status`
Displays the status to see if any changes have been made.

## 41. `git add`
A command without a specified file; this will not work as intended. You should specify a file to stage.

## 42. `git add nibba.txt`
Stages `nibba.txt` for the next commit.

## 43. `git commit -m nibba.txt "added contents"`
Commits changes to `nibba.txt` with a message, but the syntax is incorrect. Should be `git commit -m "added contents" nibba.txt`.

## 44. `git status`
Checks the status after committing.

## 45. `git commit -m nibba.txt nibbi.txt "commited some"`
Attempts to commit multiple files but uses incorrect syntax.

## 46. `git status`
Checks the status of the repository.

## 47. `git log`
Displays the commit history. Useful for reviewing changes over time.

## 48. `vim nibba.txt`
Opens `nibba.txt` for further editing.

## 49. `git add nibba.txt`
Stages the updated `nibba.txt`.

## 50. `git commit -m nibba.txt "added"`
Commits changes with a descriptive message.

## 51. `git log`
Shows the updated commit history.

## 52. `ls -lrt`
Lists files with detailed information in reverse order by time. Useful for seeing the most recent changes.

## 53. `git branch`
Lists the branches in the repository.

## 54. `git checkout -b dev`
Creates and switches to a new branch called `dev`. Useful for isolating new features or fixes.

## 55. `git branch`
Lists branches to confirm that the new branch was created.

## 56. `git status`
Checks the status of the repository in the new branch.

## 57. `git checkout master`
Switches back to the `master` branch.

## 58. `git status`
Verifies the status on the `master` branch.

## 59. `git checkout dev`
Switches back to the `dev` branch.

## 60. `vim nibbu.txt`
Opens `nibbu.txt` for editing.

## 61. `ls -lrt`
Lists files to check for `nibbu.txt`.

## 62. `git checkout master`
Switches back to the `master` branch again.

## 63. `ls -lrt`
Lists files to confirm the current directory status.

## 64. `git status`
Checks the status on the `master` branch.

## 65. `git checkout dev`
Switches to the `dev` branch again.

## 66. `git status`
Checks the status of the repository in the `dev` branch.

## 67. `git add`
A command without a specified file; this will not work as intended.

## 68. `git add nibbu.txt`
Stages `nibbu.txt` for the next commit.

## 69. `git status`
Verifies the status of staged changes.

## 70. `git checkout master`
Switches back to the `master` branch.

## 71. `git status`
Checks the status on the `master` branch.

## 72. `git status`
Repeats the status check.

## 73. `git log`
Displays the commit history.

## 74. `git checkout dev`
Switches back to the `dev` branch.

## 75. `git log`
Shows the commit history in the `dev` branch.

## 76. `git commit -m nibbu.txt "ADDED NIBBU"`
Commits changes in `nibbu.txt` with a message.

## 77. `git add nibbu.txt`
Stages `nibbu.txt` for the next commit.

## 78. `git log`
Displays the updated commit history.

## 79. `git status`
Checks the status of the repository.

## 80. `git commit -m nibbi.txt nibba.txt nibbu.txt`
Attempts to commit multiple files but uses incorrect syntax.

## 81. `git status`
Checks the status of the repository.

## 82. `git config --global user.name "abhimanyu"`
Sets the global Git username to "abhimanyu". This identifies the user for commits.

## 83. `git config --global user.email "infoabhimanyugzp@gmail.com"`
Sets the global Git email to "infoabhimanyugzp@gmail.com". This is used in commit metadata.

## 84. `git commit -m nibbi.txt nibba.txt nibbu.txt`
Attempts to commit multiple files again but uses incorrect syntax.

## 85. `git add`
A command without a specified file; this will not work as intended.

## 86. `git add nibbi.txt`
Stages `nibbi.txt` for the next commit.

## 87.
