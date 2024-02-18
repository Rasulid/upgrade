#### `git init` - create the git essential files
#### `git config user.name "Rasul Abduvaitov"` - add the name to project configuration
#### `git config user.email "rasulabduvaitov@gmail.com"` - add the email to project configuration

#### `git config --global user.email "rasulabduvaitov@gmail.com"` - add the email to global project configuration same as `name`

#### `git config --list` - get all configuration list

#### `git --unsent user.email` - remove email from project configuration same as `name`


###  in git there 3 isolation levels  `WorkingDirectory`, `Index` and `Repository`

#### `git add ` - add our system files to `Index` level

#### `git commit` - commit the changes to `Repository` level

#### `git show --pretty=fuller` show the commits like commit history

#### `git reset HEAD `name of file` ` - remove the committed file

#### `git add -p `file name` ` - add the changes to `Index` step by step


#### `git commit -all (a)` - commit all modifications to `Repository`

#### `git commit -m "massage" .gitignore (filename) ` - commit only this file 

#### `git config --global core.excludesFile ~/.gitignore` - create .gitignore file on global isolation level

#### `git rm <path>` - remove the directory
* -r - remove the repository
* -f - force remove 
* --cached - remove in Index

#### `git mv <old> <new>` - rename the repository


#### `git branch <name>` - create a new branch
#### `git checkout <name>` - switch to the new branch
#### `git checkout -b <name>` - create the new branch and switch



#### `git stash` - save the all uncommitted changes 
#### `git stash pop` - back my code

#### `git branch -f <branch name> <commit number>` - move back branch commit version
#### `git branch -f <branch name> <branch name>` - branch points to branchs commit
#### `git barnch -B <branch name> <commit number>` - move back and switch branch

#### `git cheackout <old commit number>` - go to the commits link
#### `git cherry-pick <old commit number>` - copy the commit our branch

#### `git checkout <commit number> <file name or names>` backup file if file is deleted
#### `git reset <file name>` - reset the all updates

#### `git checkout HEAD <file name>` - reset the file

#### ``
