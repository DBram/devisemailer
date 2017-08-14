
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


Welcome to your Rails project on Cloud9 IDE!

To get started, just do the following:

1. Run the project with the "Run Project" button in the menu bar on top of the IDE.
2. Preview your new app by clicking on the URL that appears in the Run panel below (https://HOSTNAME/).

Happy coding!
The Cloud9 IDE team


##  GIT Support & Documentation

Visit http://docs.c9.io for support, or to learn more about using Cloud9 IDE. 
To watch some training videos, visit http://www.youtube.com/user/c9ide


…or create a new repository on the command line

## echo "# devisemailer" >> README.md
## git init
## git add README.md
## git commit -m "first commit"
## git remote add origin git@github.com:DBram/devisemailer.git
## git push -u origin master


## …or push an existing repository from the command line

## git remote add origin git@github.com:DBram/devisemailer.git
## git push -u origin master


/ Heroku Add

## If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

$ heroku login


## Create a new Git repository

# Initialize a git repository in a new or existing directory

$ cd my-project/
$ git init
$ heroku git:remote -a bramdevisemail

## Deploy your application

## Commit your code to the repository and deploy it to Heroku using Git.

$ git add .
$ git commit -am "make it better"
$ git push heroku master


Existing Git repository

For existing repositories, simply add the heroku remote

$ heroku git:remote -a bramdevisemail