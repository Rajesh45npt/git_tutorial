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
|1. __git config__ --global merge.tool p4merge 2. __git config__ --global mergetool.p4merge.path "/home/raj/p4v-2018.4.1740700/bin/p4merge" 3. __git config__ --global mergetool.prompt false|same for diff tool|
|git diff|shows the differences in the working directory and the staged files|
|git difftool| launches the difftool to show the differences in the files in the working directory and staging|
|git diff __HEAD__ git difftool __HEAD__|shows diff between working directory and local git repository|
|git diff --staged __HEAD__ git difftool --staged __HEAD__|shows diff between staging area local git repository|
|git diff -- __filename__|showing the difference for __filename__|
|git diff __commitid1__ __commitid2__|shows the difference between two commits with ids __commitid1__ and __commitid2__|
|git diff __HEAD__ __HEAD^__|compares between __HEAD__ and __HEAD-1__|
|git diff master origin/master|shows the difference between local and remote git repository(shows the difference between last commited and last pushed). Also HEAD can be used for current branch instead of master|
|git branch -a| list all the branches in both local and remote repository|
|git branch __branchname__| create branch named __branchname__|
|git branch| list all the branches in the local repository|
|git checkout __branchname__|change the current branch to the __branchname__|
|git branch -m __oldbranchname__ __newbranchname__|-m specifies the __move__ used to rename the branch|
|git branch -d __branchname__|-d specifies the delete command used to delete the branch|
|git checkout -b __newbranchname__| create and switch to new branch named __newbranchname__|
|git merge __branchname__| merge branch named __branchname__ to current branch|
|git merge __branchname__ --no-ff| merge branches with merge commit message __--no-ff__ means __no fast forward__|
|git log --oneline --decorate --graph __--all__|shows log for all branches|
|git mergetool|to solve merge conflicts and after this commit the resolve of the merge issue|
