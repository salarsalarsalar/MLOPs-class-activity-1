Git commands written on README file as per task.
____________________________________________________________________________

git clone https://github.com/salarsalarsalar/MLOPs-class-activity-1.git 

///Output///
Cloning into 'MLOPs-class-activity-1'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 944 bytes | 7.00 KiB/s, done.
root@DESKTOP-37IUT92:/mnt/c/Users/Minahil Ashfaq/OneDrive/Desktop/MLOPs# git checkout -b dev
fatal: not a git repository (or any parent up to mount point /mnt)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).

____________________________________________________________________________

git checkout -b dev

///Output///
fatal: not a git repository (or any parent up to mount point /mnt)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).

____________________________________________________________________________

git checkout -b test

///Output///
fatal: not a git repository (or any parent up to mount point /mnt)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).

____________________________________________________________________________

ls

///Output///
MLOPs-class-activity-1


____________________________________________________________________________

cd MLOPs-class-activity-1

____________________________________________________________________________

git checkout -b dev

///Output///
Switched to a new branch 'dev'

____________________________________________________________________________

git checkout -b test

///Output///
Switched to a new branch 'test'

____________________________________________________________________________

git checkout -b master

///Output///
Switched to a new branch 'master'

____________________________________________________________________________

touch README.md
mkdir src
touch src/main.py

____________________________________________________________________________

git add .
git commit -m "Initial project scaffolding"

///Output///
[master 00c2e06] Initial project scaffolding
 Committer: root <root@DESKTOP-37IUT92.localdomain>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 40 insertions(+), 2 deletions(-)
 create mode 100644 src/main.py

____________________________________________________________________________

git push origin --all

///Output///
Username for 'https://github.com': salarsalarsalar
Password for 'https://salarsalarsalar@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/salarsalarsalar/MLOPs-class-activity-1.git/'

____________________________________________________________________________

git remote set-url origin https://(token)@github.com/salarsalarsalar/MLOPs-class-activity-1.git

____________________________________________________________________________

git push origin --all

///Output///
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 997 bytes | 18.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/salarsalarsalar/MLOPs-class-activity-1.git
 * [new branch]      dev -> dev
 * [new branch]      master -> master
 * [new branch]      test -> test

____________________________________________________________________________

