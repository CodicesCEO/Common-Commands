## d._.b Codices - Common Terminal Commands
### Last Update: 3/31/2019

Using Unix/Mac terminal is simple, don't be afraid to use it. Here are some common commands when using NPM, Yarn, Brew, Git, Heroku, and more. This single README.MD file Repo was created to help new developers with common commands that are used throughout the development process of building Angular apps and other related package managers and Command Line Interfaces (CLI). I will continue to update this file and hope this will help others through their development journey!

[Comman Commands Repo](https://github.com/CodicesTechnology/Common-Commands)

## Versions
* Angular v5.2.9
* Angular Cli v1.7.3 
* Angular Cli v7.2.11
* Homebrew v2.0.6
* Yarn v1.15.2
* Node v11.10.0
* NPM v6.7.0
* MongoDB v4.0.3 
* Mongoose v5.0.11
* Express v4.16.3
* Heroku Cli v7.22.7

## Terminal
* Navigate to a specific directory
    * $ `cd /FOLDER/FOLDER`
* Make folder "directory"
    * $ `mkdir folderA`
* Make a file
    * $ `touch fileOne.html`

## Angular Cli 
### Angular Universal
* Run command to add universal module and files
    * `ng g universal universal`

## Git 
### Git Clone
* Clone a specific GitHub Repo by copying the HTTPS  
    * $ `git clone https://github.com/USERNAME/REPO-NAME.git`

### New GitHub Repo and Remote
* 1st make a new GitHub Repo.
* Initialize your root project directory
    * $ `git init`
* Copy the origin remote command
    * $ `git remote add origin https://github.com/USERNAME/REPO-NAME.git`
* Verify added remote origin
    * $ `git remote -v`
* Stage all your files
    * $ `git add .`
* Commit staged files
    * $ `git commit -m "MY FIRST COMMIT d._.b Codices"`
* Push to remote Repo
    * $ `git push -u origin master`

### Create New GitHub Branch
* Make sure you are up to date on the repo.
    * $ `git pull`
* Make your new repo branch locally.
    * $ `git checkout -b BRANCH-NAME`
* Now push your newly made branch.
    * $ `git push origin BRANCH-NAME`

### REMOVE REMOTE
* First verfiy that yor local directory has a remote. If nothing appears after the following command, it means you dont have one attached.
    * $ `git remote -v`

* It may look something like this...
    heroku  https://git.heroku.com/HEROKU-REPO-URL.git (fetch)
    heroku  https://git.heroku.com/HEROKU-REPO-URL.git (push)
    origin  https://github.com/USERNAME/REPO-NAME.git (fetch)
    origin  https://github.com/USERNAME/REPO-NAME.git (push)

* Remove the selected remote by passing the remote's label. If I wanted to remove the "heroku" remote, I would use the following...
    * $ `git remote rm heroku`

* If I wanted to remove the "origin" remote, I would use the following...
    * $ `git remote rm origin`

* Finally, make sure you removed the GitHub remotes by running the first command. The remiaing remotes or nothing will show.
    * $ `git remote -v`

### Make Updates to your GitHub Branch
* Coming soon...

## Yarn
* Install dependencies, first make sure you are in the project's root directory, then run...
    * $ `yarn install`
* Upgrade Yarn
    * $ `yarn upgrade`

## Homebrew
* Coming Soon...

## MongoDB
* Coming Soon...

## Heroku Cli
### Heroku Deployment
* Change code in the following files...


### Author
d._.b [Codices](https://github.com/CodicesTechnology)