This is a collection of git commands.

To create a git repository:
    1. Create repository on Github
    2. Copy repo url
    3. Open Gitbash
    4. Move to appropriate directory
    5. git clone <url>
    6. git pull

To push to github:
    1. git add -A
    2. git commit
        add comment in notepad
        OR git commit -m "<commit message>"
    3. git push

Show commit history:
    git log

Undo changes since last commit:
    git checkout .

Create Branch:
    1. git branch <name>
    2. git checkout <name>
    OR
    1. git checkout -b <name>

Merge branch to main:
    1. Move to main
        git checkout main
    2. git merge <branch name>

Delete branch:
    1. git branch -d <name>
