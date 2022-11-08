# Development
## Servers needed
The web and api are both node servers. They can run on any system that can run node. 

## Where to deploy files
For the web app, navigate to the web folder, then use <br>
>npm run serve<br>

This will run the web app, and serve up the home page at the url the deployment app tells.


## Stop system
Thes servers can easily stopped by pressing (Ctrl + C) on the terminal running the proccess. This will send the kill command and stop the service.

## Troubleshooting Deployment
The most common mistake made in deployment is note connecting the multiple services together properly. 

## Debugging on live server
Any error on the system while it is running, will be logged at the terminal of the api. While it is running, a stacktrace will appear with any caught errors.