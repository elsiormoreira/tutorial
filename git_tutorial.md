# GIT AND GITHUB TUTORIAL
*By Elsior Moreira Alves Junior*

*2020, 18 Setembro*

## COMMAND LINE INTERFACE (CLI)
* **pwd** : *display current working directory path*
* **clear** : *clear CLI windows*
* **ls** : *list files and folder in the current directory*
* **ls -a** : *list hidden and unhidden files and folders*
* **ls -al** : *list details for hidden and unhidden files and folders*
* **cmd //c tree //f** : *print out a tree view from current directory*
* **cd** : change to home directory
* **cd [file_name] or [directory]** : *change to specified file or directory*
* **cd ..** : *move back one directory*
* **mkdir** : *create a new directory*
* **touch [file_name]** : *create an empty file*
* **echo [”text”] >> [file_name]** : *appends (>>) a text inside a file. e.g.: 
echo “# To Do List” >> README.md*
* **echo [”text”] > [file_name]** : *overwrites (>) a text inside a file. e.g.: 
echo “# To Do List” > README.md*
* **notepad .gitignore** : *open a .gitignore file (and any other file) inside 
notepad text editor*
* **cp [file_name] [path]** : *copy file to specify path*
* **cp -r [first_directory] [second_directory]** : *copy all files from one 
directory to another directory*
* **rm [file_name]** : *remove a file*
* **rm -r [directory]** : *remove a directory*
* **mv [file_name] [directory]** : *move a file to another directory*
* **mv [file_name_01] [file_name_02]** : *rename a file*
* **date** : *print on screen actual date and time*


## SETUP GIT BASH WORK DIRECTORY
Acessar o link a seguir para configurar a pasta de trabalho padrão que será 
exibida no prompt do git bash quando a janela de trabalho for aberta.

* https://stackoverflow.com/questions/53606099/how-to-set-the-startup-directory-in-git-bash


## GIT MOST USED COMMANDS

### Git configuration
* **git --version** : *check your current version of git*

![git version command output](./img/git_version.jpg)
<img src="img/git_version.jpg" width="200"/>

* **git update-git-for-windows** : *upgrade to the latest version of git*
* **git config --global user.name "[your_name]"** : *tag each commit with the 
user name of the person that made the commit*
* **git config --global user.email "[your_email]"** : *tag each commit with 
the user email of the person that made the commit*
* **git config --list** : *confirm all your config changes*
* **touch .gitignore** : *before start to use git you have to create .gitignore
file to avoid future bug. Create a file to specifies intentionally untracked 
files to ignore. There is a bug if you use explorer to create that type of file*


### Create a repository from your computer
* **git init** : *Create an empty git repository  in a existing directory or 
reinitialize an existing one. You have to move to your local directory before
start this process.*
* **git remote add [remote_name] [remote_repo_url]** : *This command will map 
remote repository at <remote_repo_url> to a reference in your local repo 
under <remote_name>. 
Ex: git remote add origin https://github.com/elsiormoreira/my_project.git*
* **git push -u [remote_name] [local_branch_name]** : *Once you have mapped the 
remote repo you can push local branches to it. Ex: git push -u origin master*


### Create a repository from github


### Commit files
* **git status** : *check file status (added, committed or pushed)*
* **git add [file_name] or [*] or [.]** : *add file contents  to the index*
* **git commit -m ‘[message]’** : *record changes to the repository*


### Check file changes 
* **git diff** : *between unstaged files and commited ones*
* **git diff --staged** : *between staged files and commited ones*
* **got diff HEAD** : *between staged + unstaged files and commited ones*
* **gitk** : *open git repository browser. Best way to see diff logs.*


### View commit history
* **git log** : *print out commit log*
* **git log --oneline** : *print out each commit on a single line*
* **git log -p [-n]** : *Print out commit logs information with a diff directly
following each entry. Argument "-n" will show the last "n" commit that you want 
to print on screen.*

### Remove files from staging area
* **git commit --amend -m ‘<message>’** : *edit previous commit message*
* **git reset** : *undo previous “git add” command*
* **git rm <file_name>** : *remove files from the working tree and stage area*


### Undo things
* **git restore [file_name]** : *to discard changes in working directory*
* **git restore --staged [file_name]** : *unstage files*


### COURSE SUGGESTION
* [Coursera - Version Control with Git](https://www.coursera.org/learn/version-control-with-git?ranMID=40328&ranEAID=BuGceriufQM&ranSiteID=BuGceriufQM-SLxn_q_dKbzyr_dqlx32ug&siteID=BuGceriufQM-SLxn_q_dKbzyr_dqlx32ug&utm_content=10&utm_medium=partners&utm_source=linkshare&utm_campaign=BuGceriufQM#syllabus)


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
* https://docs.github.com/pt
* https://tutorials.botsfloor.com/top-tutorials-to-learn-git-for-beginners-622289ffdfe5