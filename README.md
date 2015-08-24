# Quick Survey

> A tool for quickly building and releasing surveys. Open source & quick to host it yourself.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/simonv3/quick-survey/tree/develop)

![quick-survey](http://i.imgur.com/MaYWf4J.png)
![quick-survey-results](http://i.imgur.com/4elbHfe.png)

# Goals

* One click install. Done.
* Manage questions. Done delete and create - still need to make it possible to edit questions. Add more question types.
* Optional log in and verification (through Github / Twitter) of a survey. Right now a log in is required, but there's no actual verification of the log in.

# To deploy

## To deploy on Heroku:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/simonv3/quick-survey/tree/develop)

## To deploy with Meteor:

1. Install Meteor `curl https://install.meteor.com/ | sh`
2. Clone repo to a local directory `git clone git@github.com:simonv3/quick-survey` and change directory `cd quick-survey`.
3. Add the questions - they're defined in `server/startup/loadQuestions.js`. This will be moved to a yaml file that will get read every time the server restarts.
4. Run the app to see if it all works `meteor`
5. Deploy to meteor `meteor deploy mysurveyname.meteor.com`
6. Go to mysurveyname.meteor.com and enjoy your app!

# Contributing

What's needed:

* This tool was built for user experience researchers. So I need user experience testers!
* Ideas for the tool to do.
* Angular / Meteor expertise to go over the code
* Security holes found?
