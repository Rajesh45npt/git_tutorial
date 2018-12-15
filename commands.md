 # __Commands__
| **Commands**|**Purpose**|
|:------------|:----------|
|git config --global user.name " "||
|git config --global user.email " "||
|git config --global --list||
|git status|
|git add __filename__||
|git reset HEAD __filename__||
|git commit -m "__Message__"||
|git push origin master||
|git  init __project_name__|Creates a folder name with the __project__name__ and initializes git in it|
|git init|Initializes git in the current directory|
|git rm --cached __filename__| Unstage the added file|
|git commit|Open the editor for the git message|
|git add .|Add all the files in the staging|
|git commit -am "Message"| commit by adding to the staging area|
|git ls-files | check the list of the files that are tracked by the git|
|git add . |add all files to staging area|
|git reset __HEAD__ filename| unstage the added files|
|git checkout -- filename| restore the file to the last committed one|
|git add -A|add all changes recursively and also the renaming, moved and deleting of files|
|git mv current_file new_file| rename the file and add to the staging area automatically|
|git add renamed_filename && git add -u|add the renamed, moved and deleted files selectively(just like __git add -A__ but does selectively|
|git help __command__|shows the help page for the command of the git|
|git log| shows the history of the git|
|git log --abrev-commit| shows the history of the git with the commit code abbreviated|
|git log --oneline --graph --decorate | __--oneline__ compresses our log to one line __--graph__ provide ascii graph depicting the branching graph __--decorate__ adds labels or tags that annotate the commits|
|git log __commit_codefirst...commit_codesecond__| shows the entries from first commit code to the second one|
|git log --since="3 days ago"|shows the log from 3 days ago|
|git log -- __filename__| shows the log of the filename|
|git log --follow -- __filename__|shows the rename and delete log of the __filename__|
|git show __commit_id__|shows the information about the commit belonging to __commit_id__|
|git config --global alias.hist "log --all --graph --decorate --newline"| create a alias named __hist__ for __git log --all --graph --decorate --newline__ which can be called by git hist and can also be modified and new aliases can be added by editing ~/.gitconfig|
|__Git_Ignore_Patterns__|__Specific File:__ Myfile.ext __File Pattern:__ *.ext __Folder:__ my-folder/|
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||