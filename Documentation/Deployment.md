# Deployment
## Servers needed
The web and api are both node servers. They can run on any system that can run node.

## Deploying Site to Firebase
1. Navigate to the api folder
>cd api  
2. Run the deploy command
> npm run deploy  
  
This will build the backend api and then deploy it to firebase, give that the user is logged in using the proper credentials
3. Navigate to the web folder
> cd ../web  
  
Run the build command and then the deploy command.
>`npm run build `  
>`npm run deploy`  

This will build the dist folder, and then deploy the front end to firebase.


## Where to deploy files locally
For the web app, navigate to the web folder, then use <br>
>npm run serve<br>

This will run the web app, and serve up the home page at the url the deployment app tells.

For the API, navigate to the api folder, then use <br>
>npm start<br>

This will run the node server , and it will await requests.


## Stop system
Thes servers can easily stopped by pressing (Ctrl + C) on the terminal running the proccess. This will send the kill command and stop the service.

## Troubleshooting Deployment
The most common mistake made in deployment is note connecting the multiple services together properly. 

## Debugging on live server
Any error on the system while it is running, will be logged at the terminal of the api. While it is running, a stacktrace will appear with any caught errors.