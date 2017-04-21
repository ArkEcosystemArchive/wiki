![alt text](https://github.com/kristjank/wiki/blob/master/images/ArkWiki.png)

# ARK - Connecting to Ark Ecosystem on GitHub

As a fully open source project, ARK will live and die by it’s community contributions. We truly believe that the future of the ARK Ecosystem depends on a strong collaborative effort between the ARK Crew and our open source developers and designers. As such, we want to promote and encourage community contributions to all aspects of the project.
In order to start contributing to community, you need to pull the code and start learning/playing with it.

The following short guide will help you setup an easy to contribute environment for the Ark Ecosystem.

# Git basics and the available tooling
Take a look at this awesome **no deep shit guide** from Roger Dudler - http://rogerdudler.github.io/git-guide/. It will take you thru the installation process and explain all you need to know to start using git.

[Optional] Install GUI Git client. You can select from:
- GitHub Desktop https://desktop.github.com/
- Atlassian SourceTree https://www.sourcetreeapp.com/
- Tortoise GIT https://tortoisegit.org/

# Accessing ARK ecosystem code
A list of avaiable ARK project/repositories is accesible here: https://github.com/ArkEcosystem/. 
#### 1. Select a project you would like to learn about and contribute to
#### 2. Fork the project (you will need to be signed-in to github to acomplish this)
#### 3. Clone the project you just forked (omg - how many strange words:))

```git clone git@github.com:YOUR-USERNAME/YOUR-FORKED-REPO.git```

#### 4. Start working and viewing, editing the code.

# Contributing the code to ARK ecosystem
Let's say you found a bug, or a simple code correction suggestion. You have already tested it on your local environment, but you would also love to share it with the community (don't forget the bounty:)). To acomplish this:
- Commit your local repository changes with explanations - why you did this, what you found, what is the improvement
```
git add FILENAME
git commit -m "Commit message"
```
- Push the changes to your fork of Ark project
```
git push origin master
```
- Create a new pull request between ArkEcosystem git project and you personal project fork

After completing the pull request ARK team will go thru the proposed changes and accept, decline or ask for further explanations of your proposal.

# Keeping your fork up to date
As a separate fork your repo still needs to stay up to date with the main fork. Follow the steps bellow to setup up remote git upstream.

### 1. Clone your fork (if your already did this in previous steps, just go to root directory):

    git clone git@github.com:YOUR-USERNAME/YOUR-FORKED-REPO.git

### 2. Add remote from original repository in your forked repository: 

    cd into/cloned/fork-repo
    git remote add upstream git://github.com/ORIGINAL-DEV-USERNAME/REPO-YOU-FORKED-FROM.git
    git fetch upstream

### 3. Updating your fork from original repo to keep up with their changes:

    git pull upstream master


# Other information

1. [Wiki README](README.md)
2. [FAQ](faq.md)
