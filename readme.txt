Hello!

'git init': command to initialize tracking a repository/folder using Git
'git status': tells you the status of the folder, lets you know if there are any changes or files added. returns an error if the folder/directory is not a Git repository. Also lets you know which branch you are working on.
'git add <filename>': lets you add the file you created to the changes you'll commit using Git. if . listed instead of file name, it will add all file changes.
'git commit -m "brief explanation"': lets you commit the changes you've added and using the -m lets you add the message following in double quotes describing the updates. if no message is entered, it will open a text editor for you to enter a message. will abort if message is empty
'git diff': lets you view changes to files that have been made
'git config --global user.name <User Name>': lets you set your name
'git config --global user.username <GitHub Username>': allows you to link your GitHub account. Must use the exact lettercase as listed on GitHub.
'git config --global -l': lets you look at all the configurations including username, user.name and email you have listed.
'git remote add origin <URLFROMGITHUB>': lets you add a remote repository for your local repository and allows you to name it. typically named origin. if forked from another user's repository can add the original remote repository by naming it upstream instead of origin.
'git remote set-url <origin|upstream> <URLFROMGITHUB>': lets you set a different URL to associate with either origin or remote. Lets you correct a mistake if you entered the wrong URL.
'git remote -v': displays remote connections and their URLs
'git push origin master': sends everything to the designated remote repository and the designated branch name i.e. git push <remote name> <branch name>

forking remote repositories on GitHub and cloning them locally:
to fork another user's repository, click the fork button in the top-left corner.
to clone the repo locally, copy the URL of your forked copy and enter as below. Make sure you are not in a Git repository folder. You can do confirm by using git status command.
'git clone <URLOFFORKEDREPO>' creates a local copy of the repo on GitHub. It is automatically connected to the remote repo. To add the original, you will need to add another remote repo named upstream using the git remote add command.
'git branch': with no command line option lists all existing branches.
'git branch <BRANCHNAME>': lets you create a new branch from the existing branch.
'git branch -m <NEWBRANCHNAME>': lets you rename the current branch you're working on.
'git checkout <BRANCHNAME>': lets you move onto the designated branch from the current branch.
'git checkout -b <BRANCHNAME>': the -b command line option creates a new branch as designated by the last argument and moves onto the new branch.
I am adding this extra line to use the git diff command..
