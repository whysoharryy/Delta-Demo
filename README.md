# Delta-Demo
For learning Git & Github.

# git
version control system (Free and Open source)
tracks history , help to collaborate

# github
Website to host online repositories

# configuring git
git config --global user.name "Sreehari"
git config --global user.email "sreeharirajendran09@gmail.com"

# Use mkdir <folder_name>  (To create new folder)
# touch <file_name>  (creates file)
# pwd=print working directory, cd = change directory ,rm=remove 
# terminal :-a= to access hidden files,ls=list directory

# clone
cd Delta-Demo   (Always do)
git clone "https-link" : copy from github
While making these changes file color is change to orange shows Modification

# status
add>commit
git add index.html : Adds to staged state(Middle stage between commit and modified)
git add .          : Adds all files to staged state
git status            

# commit
syntax : git commit -m "any msg"
all these are done in own system
commit=changes

# push
To make upload local repo to remote repo
syntax: git push origin main

Now,mkdir Project2
cd Project2 
Make this a new git repo using
# init
Used to create new repo