# Heroku Setup # 

This Document is a collection of Notes from the [Heroku documentation](https://devcenter.heroku.com/articles/getting-started-with-python?c=7013A000000txcVQAQ&utm_campaign=Onboarding-2.0-Deploy-1.2-Python&utm_medium=email&utm_source=nurture&utm_content=devcenter&utm_term=start-python#set-up)

The purpose is to create a single reference point as a refresher. 

### Getting Started ###

##### Requirements #####

These are teh requirements for the the tutorial.

1. [Heroku Account](https://signup.heroku.com/signup/dc)
2. Python 3.9 (for tutorial)
3. [Postgres](https://devcenter.heroku.com/articles/heroku-postgresql#local-setup) locally


##### Setting Up Herkou #####

` $ brew install heroku/brew.heroku ` - Mac

Then Login:

`$ heroku login`

Navigate to the working directory of the program. Within the directory a `runtime.txt.` should be present along with a `requirements.txt`. 
Now, establish that working repository as a GIT and set the branch to the one that will be sent to Heroku with a `push`.
