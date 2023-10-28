# Getting Started

## Big Picture

- Git is the engine 
- Github/Gitlab is remote server for hosting Git repositories

- Git is for version control
- Github/Gitlab allows to
    - have your codebase
    - backup files 
    - share files with others
    - collaborate with others

## Important Concepts
    
**The big idea behind Git is that it has a database that stores snapshots of whole file system.**    

Under a Git repository, files can be classified as *tracked* and *untracked*---the Git database
only cares about tracked files.

For tracked files, there are **three possible status**, i.e 
*modified*, *staged*, and *committed*.

*modified* means change has been made---Git knows this, because it has the database---thus new snapshots may be needed.

*staged* means being marked---you need to do this---so when Git takes snapshot, it will only
do for those on the *stage*.

*committed* means snapshot being done.

