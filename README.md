# RithmSchool-Git
Notes from Rithm Schools Git Course

git init - Initializes an empty git repository in the current working folder.

rm -rf .git - Use this to remove the git repository

git add fileName - Stages a file before committing

git add . - Adds all new and changed files to staging

git commit -m 'myMessage' - Commits all staged content to the git repository

git log - Shows a history of all commits (q to exit), use --oneline for readability

git config --global user.name "YOUR NAME" - Set user name to use for all git repositories on your machine

git config --global user.email "YOUR EMAIL" - Set user email to use for all git repositories on your machine

git config --global --replace-all core.pager cat - Removes the need to hit q to exit git log

cat ~/.gitconfig - View all your settings

git config alias.KEYBOARD_SHORTCUT COMMAND - Shortcut a git command that you use often, example git config alias.st status will let you type git st instead of git status, this only lasts until the terminal window is open.

git config --global alias.KEYBOARD_SHORTCUT COMMAND - Will save your shortcut globally

git config --global - Show options on global parameters 

