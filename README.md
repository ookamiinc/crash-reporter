# crash-reporter
Simple Command Line Application to report crashes from HockeyApp

# How this works

- Null Buildpack on heroku
- Get crash number from HorkeyApp API
- Post to Slack
- Execute daily by Heroku Scheduler

# References

- https://github.com/ryandotsmith/null-buildpack  
- Buildpack https://devcenter.heroku.com/articles/buildpacks
- http://whatupdave.com/post/44562473903/run-bash-scripts-on-heroku

I tried but it didn't work.  
https://github.com/kr/heroku-buildpack-inline
