## Using Git and GitHub

Most open source projets now use GitHub to host their repos and there are idioms with how to properly interact with git and GitHub. I will try to be clear when we are using git (the version control system) and GitHub (repository host).

### Words and stuff

There are a few very important words to know, and they can be easily confused, so before we get sstarted, let's make sure that they are clear.

#### Repository
Repo for short. This is just a place where code lives. A git repo is somewhere that has a .git file. The important part is that it can be your computer, my computer, your GitHub page, these are all seperate repos, even if they are related somehow. 

#### Fork (GitHub)
You copy an existing repository that is on GitHub to a new repository on __your__ GitHub. The repo on your account is the one that you should interact with the most. 

#### Remote (git)
A remote is a repository that isn't on your machine. If you want to interact with the other repos, you just tell git which one you want to interact with.

#### Branch (git)
Each repository has branches. The default is 'master' branch, but often you will find a 'develop' branch. You can think of branchs like different directories containing different versions of the same code. 

## Do stuff!

1. Fork my repo
You always want to begin working with a GitHub project by creating a fork. I will explain why in a second.
2. clone your fork 
    git clone remote_place
Obviously, this takes the code at remote place and copies it to your computer. But it does more than that. Git assumes that you will want to interact with this code again and assigns that address a name, 'origin'. This is your first remote. You can see it with:
    git remote -v
3. 
