# Getting Started

## Big Picture

- Git is the engine 
- Github/Gitlab is remote platform (server) for hosting Git repositories

- Git is for version control
- Github/Gitlab allows to
    - have your codebase
    - backup files 
    - share files with others
    - collaborate with others

## Important Concepts
    
**The big idea behind Git is that it has a database that stores snapshots of whole file system.**    

**The core idea in Git is: Git thinks about its version data more like a stream of snapshots.**

Under a Git repository, files can be classified as *tracked* and *untracked*---the Git database only cares about tracked files.

For tracked files, there are **three possible status**, i.e 
*modified*, *staged*, and *committed*.

*modified* means change has been made---Git knows this, because it has the database---thus new snapshots may be needed.

*staged* means being marked---you need to do this---so when Git takes snapshot, it will only
do for those on the *stage*.

*committed* means snapshot being done.

**Remote**

- Remote repositories are versions of your project that are hosted on the 
internet or network somewhere (e.g. Gitlab or Github).
- Collaborating with others involves managing these remote repositories and pushing and pulling data to and from them.

## Tools

- command Line (We can use Command Line in New Terminal in RStudio; if it 
does not work, then use Gitbash)
- GUI (RStudio provides a basic GUI)

