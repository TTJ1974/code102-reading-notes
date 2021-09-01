All about Git!!

VERSION CONTROL
	version control is a system that allows you to revisit various versions of a file or set of files by recording changes.
  Using this one can revert a file or project to a previous version, track mods, individuals, and compare changes.

Local Version Control
  Local VCS entails one database on your hard disk that stores changes to files.

Centralized version control, was developed so that dev's could easily and seamlessly check and change files stored on a central server.

Distributed Version control
DVCS was developed to prevent catastrophic loss of data due to a server dump. It does this by creating mirrored repos. Or as some prefer to say data backups, To use in case of loss of system.

What is Git ?
	Git is a DVCS that stores data in a file system made up of snapshots. When you save a changed version of your project, Git creates a snapshot of the file and stores a reference to it.
  While relying mostly on local operations for most necessary information allows for process expediency. Do to the fact that a projects history resides on the local disk.

STATES
  Files in Git can reside in three main states: committed, modified and staged.
STAGED 
  Flagged a file’s changed version to be committed in the next snapshot

REMOTE REPOSITORIES
  In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from

CLONED REPOSITORIES
  As mentioned earlier, for cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.

SEEING YOUR REMOTES
  By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

By using git remote -v, you can view all the remote URLs next to their corresponding short names