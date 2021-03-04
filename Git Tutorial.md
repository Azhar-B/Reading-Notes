# Git Tutorial

## What is Git
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it.

Benefits of Git
* Local Operations
* Tracking Changes
* Limits the Loss of Data
* Three Main States
    * Committed: Stored in a local database
    * Modified: Changed by not committed to the database
    * Staged: Flagged changed version to be committed in the next snapshot.

## History of Git
Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s and the eventual revocation of the DVCS’ gratis status. Subsequently, Linus Torvalds, the chief architect of the Linux kernel, began creating Git. With the intention of creating a DVCS with a workflow design similar to that of BitKeeper, which was also fast, Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.

## Setting up a Git Repository
### Importing
To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:
1. Switch to the target project’s directory
2. Use the git init command
3. To start tracking these repository files, perform an initial commit by typing the following
      1. $ git add *.c
      2. $ git add LICENSE
      3. $ git commit -m “any message here”
### Cloning
You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:
      
      *$ git clone https://github.com/test

By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

## Workflow
### Local Repository Structure
The local Git repository has three components:
   1. Working Directory: The actual files reside here.
   2. Index: The area used for staging
   3. Head: Points to the most recent commit
### Saving Changes
All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.
   * Tracked: Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
   * Untracked: Untracked files were not in the last snapshot and do not currently reside in the staging area.
### Lifecycle of File Status
1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
2. You stage the modified file
3. Then, you commit staged changes.

### Checking File Status
To determine the state of files, utilize the git status command:
   * $ git status
 ### Tracking and Staging a New File
 #### Single File
 Track one file only by using the following format:
   * git add filename
#### All Files
Track all files in a repository by using the following command:
   * $ git add *
   * After adding a new file called EXAMPLE, you would see information regarding changes to be committed when using the git status command:
         * $ git status
### Committing a File
After staging one or multiple files, you should commit the changes and record what you did within the commit message:
   * $ git commit -m “made change x,y,z”
### Committing All Changes
* $ git commit -a
### Pushing Changes
Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.


## References
[Git Tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## About The Author
Veteran and Current Student at University of Memphis. Hoping to make positive changes in the world through my daily work. I can be found at [Azhar Baig](https://github.com/Azhar-B)
