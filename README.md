# WordInWordBot
Another word game chat bot

## Overview
TODO

### Game Rules
Bot will give an initial word, and player asked to create another word from those letters (with minimum length of word is 3)

#### Rules
- Initial Words has minimum length of 5
- Word created from initial letters minimum length of 3
- Game Duration : 1 minutes
- Invalid word must be notified by Bot

#### Bot Command
Bot command is a sets of unique listener to respond when users send chat that started with `/`
- /startgame
Ask bot to start game (Gives a starting word, and start counting)

## Development Tasks
This sections will list all task that need to be developed for the bot. Please send an inquiry for claiming a tasks
- Create initial bot (main.py)
- bot command listener
- word validator
- Database layers (Firebase)

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