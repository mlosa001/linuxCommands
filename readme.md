## BASIC NAVIGATION


`cd` : Change Directory
#### Example use cases
`cd ..` : Change to parent directory

`cd ~`  or  `cd` : return to root directory

`cd ../example/example` : navigating multiple levels of a file tree


`ls` : List segments; List files in a directory

#### Example use cases

`ls -l` : long detailed listing includes detailed read/write permissions, date file was created, date file was created, and name of the file 

`ls -a` : list all (including hidden)

`pwd` : Present Working Directory; List current absolute directory
    

## FILE MANIPULATION

`touch` : creates a file  

`less` : read a text file

`rm *file name*` : remove a file

`rm -r *directory name*` : remove a directory

`rmdir *directory name*` : remove a directory

`rm -rf *directory name*` : force removes everything (files/directories, etc do not use unless you know what you’re doing)

`cp` : copy a file (within the same directory, if the second file does not exist, one will be created)

`cp *file1* *file2*` : copy file1 to file2

`cp *file 1* ../*directory name*` : Copy a file to a different directory 

`chmod` : change the permissions of file to _octal_

`mv *file1* *directory*` : move a file to another directory

`mv *file1* *newFileName*` : rename a file

## Create a Local Repository 

`git init` :  this initializes a repository 

`git status` : Checks the status of the repository tracks any changes of the repository 

`git add` : add files to git repository (use ‘.’ for all) 

`git clone` : clone a repository 

`git push` : this pushes the code to github 

`git push origin master` : Send changes to the master branch of your remote repository. 

`git remote add` : this adds the files to the repository 

`git pull` : this pulls the files from a repository 

`git commit -m *details about your process*` : this command commits the code to github and adds a message 

`git clone */path/to/repository*` : Create a working copy of a local repository 

`git remote add origin <server>` : If you haven't connected your local repository to a remote server, add the server to be able to push to it. 



## Branches

`git checkout -b <branchname>` : Create a new branch and switch to it.

`git checkout <branchname>` : Switch from one branch to another.

`git branch` : List all the branches in your repo, and also tell you what branch you're currently in.

`git branch -d <branchname>` : Delete the current  branch.

`git push origin <branchname>` : Push the branch to your remote repository, so others can use it.

`git push --all origin` : Push all branches to your remote repository.



## HELP

`{command} --help` : shows description and usage of a command.

`man` : search the manual for a command

`info` : gives more detailed information about a command then it's respective man pages



## OTHER

`cal` : displays the calendar in the terminal