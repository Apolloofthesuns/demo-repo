# Demo

**terminologies:**

1 hashtag -> main header;

directory -> folder;

terminal or command line -> interface for text commands;

CLI -> command line interface;

cd -> change directory;

code editor - word processor for writing code;

repository -> project, or the folder/place where your project is kept;

github -> a website to host your respositories online;

**git commands:**

clone -> bring a repository that is hosted somewhere like github into a folder on your local machine;

add -> track your files and save changes in git;

commit -> save your files in git;

push -> upload git commits to a remote repo, like github;

pull -> download changes from remote repo to your local machine, opposite of push;

ssh-keygen -> generates a ssh key for github. "-t" type of encryption (ed25519) [for legacy systems: (rsa), "-b" strength of encryption (4096)], -C email address

cd -> goes back to main directory

ls -> lists all the files in that directory

cat _fileName_ -> opens the file in CLI

git add . -> adding the period tells git to add changes of all the files in our local directory to git

git add _individualFileName_ -> only adds the changes of that specific file in our local directory to git

clear -> clears the terminal

git status -> shows the status of the files

git commit -m -> it's important to add "-m" because without it, we'll not be able to use commit. first "-m" adds a title, a second "-m" adds a description. usually it should be the change logs in the files

git push origin main-> after using commit, push is used to upload the files into github to our remote depository

git init -> turn another folder into a git repository

git remote add origin _ssh-key_ -> [remote means somewhere else and not on this computer] adds the new folder to github repository(easiest way to do this is to create another repository in github). we are gonna use this to add a reference to a remote repository on github

git remote -v -> to check any remote repositories that was connected to this local repository

git push -u origin main -> to setup an upstream so in future we can push without typing "origin master"

//git branch trail
