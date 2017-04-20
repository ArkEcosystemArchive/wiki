![alt text](https://github.com/kristjank/wiki/blob/master/images/ArkWikiLogo.png)

# ARK - Connecting to Ark Ecosystem on GitHub

As a fully open source project, ARK will live and die by it’s community contributions. We truly believe that the future of the ARK Ecosystem depends on a strong collaborative effort between the ARK Crew and our open source developers and designers. As such, we want to promote and encourage community contributions to all aspects of the project.
In order to start contributing to community, you need to pull the code and start learning/playing with it.

The following short guide will help you setup an easy to contribute environment for the Ark Ecosystem.


# GIT basics of and the available tooling
Take a look at this awesome http://rogerdudler.github.io **no deep shit guide** from Roger Dudler. It will take you thru the installation process and explain all you need to know to start using git.


Install GUI Git client. You can select from:
- GitHub Desktop https://desktop.github.com/
- Atlassian SourceTree https://www.sourcetreeapp.com/
-  Tortoise GIT https://tortoisegit.org/

# Accessing ARK ecosystem code
A list of avaiable ARK project/repositories is accesible here: https://github.com/ArkEcosystem/. 
- Select a project
- Fork the project (you will need to be signed-in to github to acomplish this)
- Clone the project you just forked (omg - how many stranged words:))
- Start working and viewing, editing the code.

# Contributing the code to ARk ecosystem
Let's say you found a bug, or a simple code correction suggestion. You have already tested it on your local environment, but you would also love to share it with the community (don't forget the bounty:)). To acomplish this:
- Commit your local repository changes with explanations - why you did this
- Push the changes to your fork of Ark project
- Create a new pull request between ArkEcosystem git project and you personal project fork

# Keeping your fork up to date

### 1. Clone your fork (if your already did this in previous steps, just go to root directory):

    git clone git@github.com:YOUR-USERNAME/YOUR-FORKED-REPO.git

### 2. Add remote from original repository in your forked repository: 

    cd into/cloned/fork-repo
    git remote add upstream git://github.com/ORIGINAL-DEV-USERNAME/REPO-YOU-FORKED-FROM.git
    git fetch upstream

### 3. Updating your fork from original repo to keep up with their changes:

    git pull upstream master


And here's some code! :+1:

```javascript
$(function(){
  $('div').html('I am a div.');
});
```

And here's some code! :+1:

```javascript
$(function(){
  $('div').html('I am a div.');
});
```
