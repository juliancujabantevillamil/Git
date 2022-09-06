# GIT NOTES

## GIT BASIC WORKFLOW

Git's basic workflow can be explained in the following image:

![](Images_Git_notes/img1.png)

There are 3 '_areas_'
-**Working Directory**:
Where initially files are. Changes on files are made here.
-**staging Area**:
Area where files are uploaded, ready to be commited and saved in repository.
-**Repository**:
Final Area where files will be stored.

For each '_area_' you can relate an specific git command.

In that sense, **_git init_** would be related to the first area (**working directory**).
**_git add_** would be related to the second area (**staging area**), and **_git commit_** to the third (**repository**).

### BASIC GIT COMMANDS

**git init**: Initiates the project.

**git status**: Shows the status of the project. Displays the elements in the **working ddirectory** and on the **staging area**.

**git add filename**: Adds an specific file from the **working directory** to the **staging area**. 
**git add** can be used with multiple files, in that case each filename must be write following each other, ie. **git add filename1 filename2 filename 3**. 
If all the files of the directory are going to be 'staged', -A refering to all, or . after **git add** could be used to add all elements. **git add -A** or **git add .**.
If all the files from a specific extension would be added, it can be specified so in the command: **git add .*txt**.

