**#My Reading Notes**
**#Revisions and the Clouds**
**GIT**- Is a DVCS that stores data in a file system made up of snap shots. Each time you save a changed version of your project 
-Called Commit- Git creates sanpshot of the files and stores a reference to it.
**Version Control**- Is the sysytem that allows you to revisit various versions of a file or set of file by recording changes. 
Through version control one can revert a file or project to a previous version, track modifications, modifying individuals and compare changes.
**(VCS)** -mistakes with files can be easily rectified.
**Local Version Control**- One database on your hard disk that stores changes to your files.
**Centralized Version Control (CVCS)**- This system entails a single server storing all changes and file versions.
**Distribution Version Control (DVCS)**- address the major vulnerability of the CVS;the server as single point of failure.
**Local Operations**- Git mostly relies onn local operations because the most necessary information can be found in local resources.
**Tracking Changes**- Every single change applied to any file or directory is tracked by Git. And as the gatekeeper, Git will always detect file corruption or loss of information in transit.
**States**- files in Git can reside in three main states: *committed, modified, and staged.*
*Committed- Data is securely stored in a local database
Modified -File has been changed but not committed to the database
Staged- Flagged a file's changed version to be committed in the next snap shot.
**Setting up a Git Reopository**
*To import an existing project or directory into Git follow these steps:
1. $ cd test 
2. Use Git init command- $ git init
3. To start tracking these repository files perform sn initial committ by typing the following:
$ gitadd*.c
$ git add LICENSE
$ git commit-m
Cloning*- You can create a copy of an existing repository from a particular server by using the clone command.

**Workflow
Local Repository structure**- Local Git has 3 components:
1.*Working Directory*- The actual files reside
2.*Index*- The area used for staging
3.*Head*- Points to the most recent commit.

**Saving Changes**- All files in a checked out (or working) copy of a project file either in tracked or untracked state.
*Tracked - tracked files can be modified.
Untracked-Files were not in the last snapshot and do not currently reside in the staging area.*

**Life Cycle of File Status**
1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
2. You stage modified file.
3. Then you commit staged changes.

**Check File Status**
To determine the state of files utilize the git states command:
$git status
Committing all changes- $ git commit-a
Pushing Changes- $ git push orgin master
Stashing Changes- When you are not ready to commit changes but do not want to lose them either git staxh is great option.

**Remote Repositories**
In order to collaborate  on Git projects , you must interact with remote repositories versions of a project residing
online or on a network.
Cloned Repositories- Git will automatically give you the name "origin" to the server from which you cloned and master to yourlocal branch.

**Seeing Your Remotes**
Git remote command you can view the short names , such as origins.
by using git remote-v.


