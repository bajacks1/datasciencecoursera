# datasciencecoursera
used for coursera classes
asdf

## using git & cmd line...

open GitShell or open command line in windows with by running "cmd" in start menu (note, having problems with regular cmd but gitshell works) 
* useful commands ... to use these commands the cd must be set to the directory of a linked git repository
** cd - current directory. shows the name of the current directory
** .. - move up one directory from cd (new cd)
** ls - list all files in cd (mac)
** dir - list all files in cd (win)
** git - will list all commands available working within git
** git clone <url> - copies repository from github and creates a new folder in cd with same name as repository
** git status - shows what's difference between local dir and on git
** git add <file name> - makes local "untracked" file known to git but does not commit changes
** git add . - adds all new files in directory to the local git index
** git add -u - updates tracking for files that changed names or were deleted
** git add -A - does action for both "git add ." and "git add -u"
** git commit - m "<custom message about commit>" - commits all changes with the custom message to git but does not sync with github
** git push - syncs recent commits to github
** git pull - pulls changes from committed changes synced with github


* General workflow...
** start day with git pull
** make my code changes
** git add -A
** git commit -m "specific message about recent code changes"
*** commit frequently throughout the day.
** git push, git pull also frequently throughout the day

Conflicts...
New synced code will indicate where there are conflicting lines. The first line under conflict HEAD will be my original line and the second will be the conflict from someone else. I will need to manually review the differences and make a decision which is write or what new hybrid value is needed.
