# Demo file for git

Git Starting Commands
 
Lecture Command Listing - Fresh Start
pwd
cd projects/
git init git-demo
 
Lecture Command Listing - Start with Existing Project
pwd
cd projects/
cd website/
ls
git init
 
Command Reference
Present Workding Directory
pwd
Change Directory
cd folder-name
Git initialization
git init [project-name]
project-name parameter is optional. If not supplied, Git will initialize the current directory.

## ADDItionAL
Git Add
git add file-name
Adds the new or newly modified file-name to Git's staging area (index).
Git Commit
git commit -m "A really good commit message"
Commits all files currently in Git's staging area. The -m parameter allows for a commit message directly from the command line.
Clear!
clear
Clears all previous commands from the terminal screen -- just a bit of clean up.
Text Mate
mate file-name
All command line demos are preformed on the MacOS. 
Creating and editing files is done with TextMate 2 (free) 
using the mate command from Terminal. 
Passing a file-name to the mate command will create or open that file. 
Windows users can use the notepad file-name command instead.

### Adding more
Command Reference
List
ls
Lists files and folders in current directory.
 Without parameters, will list non-hidden folders and files.
Git Status
git status
