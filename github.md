# configure git


# ssh key for git, edit the .ssh/config

Host github.com
   
    HostName github.com
   
    IdentityFile ~/.ssh/<your-ssh-key>
    
    User git

# create a new repository on the command line

echo "# <your-repo-name>" >> README.md

git init

git add README.md

git commit -m "<your commit message>"

git remote add origin git@github.com:<your-name>/<your-repo-name>.git

git push -u origin master


... tbc
