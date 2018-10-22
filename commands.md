BASIC NAVIGATION

CD - Change Directory
    Example use cases
    cd .. - Change to parent directory
    cd - return to root directory
    cd ../example/example - navigating multiple levels of a file tree

Ls - list files in a directory
    Example use cases
ls -l : long detailed listing includes detailed read/write permissions, date file was created, date file was created, and name of the file 
ls -a: list all (including hidden)

Pwd - Present Working Directory
    List current absolute directory
    

FILE MANIPULATION

Touch- creates a file  

Less: read a text file

Rm: remove a file 
    E.g. rm *file name*
Rm -r: remove a directory
    E.g. rm -r *directory name*
Rmdir: remove a directory
Rm -rf: force removes everything (files/directories, etc do not use unless you know what you’re doing)

Cp: copy a file (within the same directory, if the second file does not exist, one will be created)
    E.g. cp *file 1* *file2* 
            cp apples apples2

    Copy a file to a different directory 
    E.g. cp *file 1* ../*directory name*
           cp cobras.py ../snakes

chmod: 
Mv - move a file
    Syntax: mv {file} {directory} {new file name}
    (can be used to rename a file by leaving directory empty)


Create a Local Repository 

Git Init -  this initializes a repository
Git status -  Checks the status of the repository tracks any changes of the repository
Git add - add files to git repository (use ‘.’ for all)
Git clone - clone a repository
Git push- this pushes the code to github
Git push origin master- Send changes to the master branch of your remote repository.
Git remote add - this adds the files to the repository 
Git pull- this pulls the files from a repository
Git commit -m - this command commits the code to github and adds a message
Git clone /path/to/repository -Create a working copy of a local repository
Git remote add origin <server>- If you haven't connected your local repository to a remote server, add the server to be able to push to it.


Branches

Git checkout -b <branchname> - Create a new branch and switch to it.
Git checkout <branchname> - Switch from one branch to another.
Git branch - List all the branches in your repo, and also tell you what branch you're currently in.
Git branch -d <branchname> - Delete the current  branch.
Git push origin <branchname> - Push the branch to your remote repository, so others can use it.
Git push --all origin - Push all branches to your remote repository.
Git push origin :<branchname>- git push origin :<branchname>








HELP
{command} --help: shows description and usage of a command.
Man: search the manual for a command

