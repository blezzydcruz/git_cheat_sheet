# Terminal Commands

    Key Terminal Commands

*Commands for navigating the file system, creating and manipulating files and folders*



| Code  | Description   |
| :---  | ---:         |
| `pw`  | print working directory   |
| `pwd`     | show current working directory |
| `ls` | list of files and folders         |
| `cd`  | change directory |
| `mkdir`   | make directory    | 
| `touch`   | create a new file | 
| `open`    | opens files   |
| `mv`  | move files |
| `cp`  | copy files    |
| `rm`  | delete a file     |
| `rm -r`  | delete a directory     |
| `rm -f`   | delete a folder |

    MORE Terminal Commands

| Code  | Description   |
| :---  | ---:|
| `ls -l`   | list of files and folders along with permissions, owner and date last modified    |
| `ls -al`  | list of files and folders including hidden files  |
| `.`   | current directory |
| `..`  | parent directory  |
| `clear` | clear working space |


# Git in Terminal

    Step by step to using Git in Terminal

| Steps/ Description     | Terminal Input   |
| :---  | ---:|
| Create a directory to work in and navigate to it  | `mkdir` [folder name] then `cd` [folder name]  |
| Create a Git repository   |   `git init` 
| Add files     |  `touch` [name].txt |
| Check modified files |  `git status` |
| In cases of "untracked file" when checking modified files | `git add` [name].txt then `git status`|
| Commiting to the changes| `git commit -m` "add [name].txt"|
| Adding more changes | `git add .` then `git commit -m` "add ..."
| Check history of repository so far and to find ID of the commit | `git log` |
| To exit history of repository | press "q" |
| Undo a specific commit | `git revert` [ID of commit] |
| Undo everything from a specified commit | `git reset`|
| Reverse the commits and remove them from history | `git rebase`|


# GitHub

## Upload code

    1. At GitHub, "create respitory" and ensure it is "public".
   
    2. Select "SSH" option then "copy to clipboard".
   
    3. Write the following code into terminal
        `git remote add origin your/copied/url`
        `git push origin main`


## Dowloading code

    1. At GitHub, click on "code" and copy the link in "SSH".
   
    2. To command to copy the files in Terminal are as follows
        `git clone repository/url/here`
    * Be sure not to clone a repository inside another one * 
    
    3. To download any changes in the repository by someone, write 
        `git pull origin main`