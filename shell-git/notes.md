# Notes for Shell and Git

### Terminal/Shell 31.01.2024

Shell = CLIs (Command Line Interfaces)

#### Commands

- move one folder up = ..
- go to = cd
- list of files = ls
- show hidden files = ls -la
- create new file = touch NameOfFile
- create folder = mkdir NameOfFolder
- remove file = rm FileName
- clear the terminal = clear
- rename/move file = mv oldName newName
- Show content of file = cat NameOfFile
- show path = pwd
- Remove empty folder = -r
- Delete Folder and its content = rm -R (be careful, it forced to delete)
- opens folder/ file = code NameOfFile

#### Diamond Challenge

Location of Diamond:
/Users/emilyraspe/documents/Spiced/challenges/shell-basics/shell-basics_treasure-hunt/treasure-island/forest/deep-forest/very-deep-forest/ruins/temple/.secret-door/tunnel/chest.md

### Git 31.01.2024/01.02.2024

Git = Version control System --> keeps track of changes

#### Push

1. Navigate to folder
2. git init
3. Create new Repo in Github
4. git add . (. adds everything in the folder, if thats not wanted write filename instead of .)
5. git commit -m "initial commit"
6. git remote add origin _link from github_ (make sure the link is SSH and not HTTPS)
7. git push -u origin main

#### New Branch

1. create new Branch = git switch -c "nameOfBranch"
2. Make changes
3. git add . (. adds everything in the folder, if thats not wanted write filename instead of .)
4. git commit -m "write what has been changed"
5. git push -u origin _nameOfBranch_
6. GitHub Compare and Pull request
7. Approve Pullrequest in GitHub
8. MERGE = merging back to the main branch (by merging the feature branch can be deleted in github)
9. git switch main
10. git pull

#### Additional information

- git status = check the status
- Name of the files that should be ignored must be written in the .gitignore file
- If you want to stop tracking the Project you have to delete the .git file = rm rf .git
- Remove = git branch -d nameofbranch
