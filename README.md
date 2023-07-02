Usefull commands for running site:

Push changes to repo:

    git add FILENAME
    git commit -m "message"
    git push origin master

Overwrite local repo with github:

    First, update all origin/<branch> refs to latest:

        git fetch --all

    Backup your current branch (e.g. master):

        git branch backup-master

    Jump to the latest commit on origin/master and checkout those files:

        git reset --hard origin/master

