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