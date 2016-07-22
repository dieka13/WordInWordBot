# WordInWordBot
Another word game chat bot

## Overview
TODO

### Game Rules
Bot will give an initial word, and player asked to create another word from those letters (with minimum length of word is 3)

## Library
This repository will use the following library (listed in requirement.txt)
- [Python Telegram bot](https://github.com/python-telegram-bot/python-telegram-bot)
- [Unirest](http://unirest.io/python.html)
- [Words API](https://www.wordsapi.com/docs)

## Development Flow
We are encourage to use [Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow).
in brief : 

- Create your own branch from `master`
```
git checkout -b newFeatureBranch
```
- Commit your changes on your branch
```
git add .
git commit -m "gives your comment of your commit here"
```
- After all looks good, push your branch (don't forget to pull from `master` first before push)
```
git push -u origin newFeatureBranch
```
- Create Pull Request from your branch to master
- Wait reviewer to check your Pull Request and merge to the master