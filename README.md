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

cat fileName -> opens the file in CLI

git add . -> adding the period tells git to add changes of all the files in our local directory to git

git add individualFileName -> only adds the changes of that specific file in our local directory to git

clear -> clears the terminal

git status -> shows the status of the files

git commit -m -> it's important to add "-m" because without it, we'll not be able to use commit. first "-m" adds a title, a second "-m" adds a description. usually it should be the change logs in the files

git push -> after using commit, push is used to upload the files into github to our remote depository
