## Reading Assignment 3

### Git Tutorial

#### Version Control

- Version control is a system that allows you to revisit various versions of a file or set of files by recording changes

#### So What is Git

- Stores data
- Relies on local operations
- Every change is tracked
- Loss of data

#### Setting up a Git Repo
- Importing 
    1. Switch to the targets projects directory 
    2. Use the git init command
    3. To start tracking these repo files, perform an intial commit by trying the following
        - git add *.c
        - git commit -m 'any message here'
        - git add LICENSE

#### WorkFlow

- Local repo structure has 3 components 
    1. Working directory: The actual files reside there
    2. Index: The areas used for staging
    3. Head: Points to the most recent commit
- The lifecycle of file status
    1. After you edit a file, git flags it as modified because of changed made after the previous commit
    2. You can stage the modified file
    3. Then you commit the changes