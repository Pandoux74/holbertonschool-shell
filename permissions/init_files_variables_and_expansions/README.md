# Shell, init files, variables and expansions

## Task 0: Create an alias

The goal of this task is to create a Bash script that defines an alias named `ls` with the value `rm -rf *`.

## Commands used

- `mkdir init_files_variables_and_expansions` : Creates the project directory.
- `cd init_files_variables_and_expansions` : Enters the project directory.
- `touch 0-alias` : Creates an empty script file.
- `echo '#!/bin/bash' > 0-alias` : Adds the Bash shebang to the script.
- `echo "alias ls='rm -rf *'" >> 0-alias` : Adds the alias definition to the script.
- `chmod u+x 0-alias` : Gives the file owner permission to execute the script.
- `git add 0-alias` : Stages the script for Git.
- `git commit -m "Add 0-alias"` : Saves the changes in Git.
- `git push` : Sends the committed changes to GitHub.

## What I learned

- How to create directories and files.
- How to write commands into a Bash script.
- The difference between `>` (overwrite) and `>>` (append).
- How to create an alias using `alias`.
- How to change file permissions using `chmod`.
- How to save and push changes with Git.

**Warning:** The alias replaces `ls` with a command that recursively deletes non-hidden files and directories in the current directory. It should not be used outside a safe testing environment.
