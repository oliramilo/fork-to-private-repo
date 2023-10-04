# fork-to-private-repo
## Forking a public repository to your private repository


1. Obtain the repository link you want to fork. For the example below the link is https://github.com/oliramilo/Stockbot.git
![screenshot1](screenshots/repository%20link.png)



2. Go to your terminal, for this one I'm using the terminal in VSCode: use the command git clone --bare (repository link). i.e git clone --bare https://github.com/oliramilo/Stockbot.git

![screenshot2](screenshots/terminal%20screenshot.png)


A git file will be cloned to the current directory: 
![screenshot3](screenshots/directory.png)

## use cd to change to the bare clone directory 
![screenshot4](screenshots/cd.png)

## Now create your private repo
![screenshot5](screenshots/private.png)

## Copy the git repository link
![screenshot6](screenshots/private2.png)


## Use: git push --mirror (private repository link)

Example Below: git push --mirror https://github.com/oliramilo/Example.git

![screenshot7](screenshot/../screenshots/mirror%20push.png)

## Go back a directory and clone your private repo
![screenshot8](screenshots/clone%20private.png)

## Contents will appear in your private repository

![screenshot9](screenshots/contents.png)