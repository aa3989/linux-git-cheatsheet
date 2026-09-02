## Linux and Git Cheat Sheet ##

# Linux Commands #


# 1. cd
        Changes directories

        Usage:
            cd folder

        Useful tricks:
            cd ..       -- go back one directory
            cd ~        -- go to home directory
            cd -        -- go to previous directory

# 2. ls
        Lists files and directories

        Usage:
            ls

        Useful tricks:
            ls -l       -- detailed view
            ls -la      -- includes hidden files

# 3. mkdir
        Creates a directory

        Usage:
            mkdir folder

        Useful tricks:
            mkdir folder1 folder2
                -- creates multiple directories

            mkdir -p project/src/components
                -- creates nested directories

# 4. touch
        Creates an empty file

        Usage:
            touch file.txt

        Useful tricks:
            touch file1.txt file2.txt
                -- creates multiple files

# 5. rm
        Removes files or directories

        Usage:
            rm file.txt
            rm -r folder

        Useful tricks:
            rm -r folder
                -- removes folder and its contents

            rm -rf folder
                -- force removes everything inside
                -- USE WITH CAUTION

# 6. cp
        Copies files or directories

        Usage:
            cp file.txt copy.txt

        Useful tricks:
            cp file.txt folder/
                -- copies file into folder

            cp -r folder backup/
                -- copies entire directory

# 7. mv
        Moves or renames files/directories

        Usage:
            mv file.txt folder/

        Rename:
            mv old.txt new.txt

# 8. cat
        Displays the contents of a file

        Usage:
            cat file.txt

        Useful tricks:
            cat -n file.txt
                -- displays line numbers

# 9. grep
        Searches for text

        Usage:
            grep "hello" file.txt

        Useful tricks:
            grep -i "hello" file.txt
                -- ignores uppercase/lowercase

            grep -r "hello" .
                -- searches all files recursively

# GIT Commands #

# 10. git status
        Shows the current state of your Git repository

        Usage:
            git status

        Shows:
            modified files
            staged files
            untracked files
            current branch

# 11. git add
        Adds changes to the staging area

        Usage:
            git add file.py

        Most common:
            git add .
                -- stages all changes

# 12. git commit
        Saves staged changes to Git history

        Usage:
            git commit -m "Add login page"

        Typical workflow:
            git add .
            git commit -m "Update project"




