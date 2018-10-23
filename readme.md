## BASIC NAVIGATION

`cd` - Change Directory
    Example use cases
    `cd` .. - Change to parent directory <br />
    `cd` - return to root directory <br />
    `cd` ../example/example - navigating multiple levels of a file tree <br />

`ls` - list files in a directory
    Example use cases<br />
`ls` -l : long detailed listing includes detailed read/write permissions, date file was created, date file was created, and name of the file 
`ls` -a: list all (including hidden)

pwd - Present Working Directory
    List current absolute directory
    

FILE MANIPULATION

touch- creates a file  

less: read a text file

rm: remove a file 
    E.g. rm *file name*
rm -r: remove a directory
    E.g. rm -r *directory name*
rmdir: remove a directory
rm -rf: force removes everything (files/directories, etc do not use unless you know what you’re doing)

cp: copy a file (within the same directory, if the second file does not exist, one will be created)
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

Git Init -  this initializes a repository <br />
Git status -  Checks the status of the repository tracks any changes of the repository <br />
Git add - add files to git repository (use ‘.’ for all) <br />
Git clone - clone a repository <br />
Git push- this pushes the code to github <br />
Git push origin master- Send changes to the master branch of your remote repository. <br />
Git remote add - this adds the files to the repository <br />
Git pull- this pulls the files from a repository <br />
Git commit -m - this command commits the code to github and adds a message <br />
Git clone /path/to/repository -Create a working copy of a local repository <br />
Git remote add origin <server>- If you haven't connected your local repository to a remote server, add the server to be able to push to it. <br />


Branches

Git checkout -b <branchname> - Create a new branch and switch to it.<br />
Git checkout <branchname> - Switch from one branch to another.<br />
Git branch - List all the branches in your repo, and also tell you what branch you're currently in.<br />
Git branch -d <branchname> - Delete the current  branch.<br />
Git push origin <branchname> - Push the branch to your remote repository, so others can use it.<br />
Git push --all origin - Push all branches to your remote repository.<br />
git push origin :<branchname>








HELP
{command} --help: shows description and usage of a command.
Man: search the manual for a command

