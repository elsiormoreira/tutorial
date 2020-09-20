# GIT AND GITHUB TUTORIAL
*By Elsior Moreira Alves Junior*

*2020, 18 Setembro*

## COMMAND LINE INTERFACE (CLI)
* **pwd** : *display current working directory path*
* **clear/ctrl + L** : *clear CLI windows*
* **ls** : *list files and folder in the current directory*
* **ls -a** : *list hidden and unhidden files and folders*
* **ls -al** : *list details for hidden and unhidden files and folders*
* **cd** : change to home directory
* **cd [file_name] or [directory_name]** : *change to specified file or directory*
* **cd ..** : *move back one directory*
* **mkdir [directory_name]** : *create a new directory*
* **rm -r [directory_name]** : *remove a directory*
* **touch [file_name]** : *create an empty file*
* **rm [file_name]** : *remove a file*
* **echo [”text”] >> [file_name]** : *appends (>>) a text inside a file. (e.g.: 
echo “# To Do List” >> README.md)*
* **echo [”text”] > [file_name]** : *overwrites (>) a text inside a file. (e.g.: 
echo “# To Do List” > README.md)*
* **cp [file_name] [path_name]** : *copy file to specify path*
* **cp -r [first_directory_path] [second_directory_path]** : *copy all files from one 
directory to another one*
* **mv [file_name] [directory_name]** : *move a file to another directory*
* **mv [file_name_01] [file_name_02]** : *rename a file*
* **date** : *print on screen actual date and time*


## SETUP GIT BASH WORK DIRECTORY
Access the link below to folowup a step by step tutorial to configure your git bash
work directory for a standard open folder every time you start to sue git bash.
 
* https://stackoverflow.com/questions/53606099/how-to-set-the-startup-directory-in-git-bash


## LIST OF COMMANDS
* **git --version** : *check your current version of git*
* **git update-git-for-windows** : *upgrade to the latest version of git*
* **git config --global user.name "[your_name]"** : *tag each commit with the 
user name of the person that made the commit*
* **git config --global user.email "[your_email]"** : *tag each commit with 
the user email of the person that made the commit*
* **git config --list** : *confirm all your config changes*
* **touch .gitignore** : *create a file to specifies intentionally untracked 
files to ignore. There is a bug if you use explorer to create that type of file*
* **git init** : *Create an empty git repository  in a existing directory or 
reinitialize an existing one. You have to move to your local directory before
start this process.*
* **git remote add [remote_name] [remote_repo_url]** : *This command will map 
remote repository at <remote_repo_url> to a reference in your local repo 
under <remote_name>. 
Ex: git remote add origin https://github.com/elsiormoreira/my_project.git*
* **git push -u [remote_name] [local_branch_name]** : *Once you have mapped the 
remote repo you can push local branches to it. Ex: git push -u origin master*
* **git status** : *check file status (added, committed or pushed)*
* **git add <file_name> or <*> or <.>** : *add file contents  to the index*
* **git reset** : *undo previous “git add” command*
* **git commit -m ‘<message>’** : *record changes to the repository*
* **git commit --amend -m ‘<message>’** : *edit previous commit message*
* **git rm <file_name>** : *remove files from the working tree and stage area*
* **git diff** : *show changes between commits*
* **git diff --staged** : *only show changes from files in the staged area*
* **git log** : *show commit log*
* **git log --pretty=oneline** : *prints on screen each commit on a single line*
* **git log -p [-n]** : *Show commit logs information but with a diff directly
following each entry. Argument "-n" will show the last "n" commit that you want 
to print on screen.*
* **gitk** : *open git repository browser. Best way to see diff logs.*


## REFERENCES AND WEB SOURCE
* https://git-scm.com/book/en/v2
* https://git-scm.com/docs
* https://www.freecodecamp.org/news/understanding-git-basics-commands-tips-tricks/
* https://www.geeksforgeeks.org/using-git-on-commandline/?ref=lbp
* http://rogerdudler.github.io/git-guide/index.pt_BR.html
* https://lab.github.com/
* https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud
* https://www.codecademy.com/learn/learn-git
* https://docs.google.com/document/d/1qd7_JSJOPYD0DhcMDvi2e9EKXwkyYzpTaq09CHoK_CA/edit
* https://docs.google.com/document/d/1qd7_JSJOPYD0DhcMDvi2e9EKXwkyYzpTaq09CHoK_CA/edit
* https://chris.beams.io/posts/git-commit/
