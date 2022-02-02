# Rails Tutorial Scripts

## What's the point?
*  This repository contains the Bash scripts that I find necessary for Rails Tutorial.  I find these scripts necessary for automating the most routine tasks.  I can focus on the tutorial rather than have to memorize or look up commands.
*  I use the Docker environment for Rails Tutorial.  I never have to live in fear of accidentally screwing up my development environment.  To make sure I've covered all the steps needed to set up my development environment, I like to reset my Docker environment at the start of each chapter and then run the credentials.sh, test.sh, and heroku-login.sh scripts.  If there's a critical detail that I've missed, it's better to take care of it sooner than later.

## Things To Do
* If necessary: Update the version of Bundler in bundle_install.sh and guard.sh.
* Be sure to fill in the name of the Heroku app in the heroku-push.sh script.
* Provide the link to the Heroku app in the README.md file.
