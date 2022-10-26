# Development



## Suggested IDE
-  Microsoft Visual Studio Code 

## Project Structure
This project is written in two distinct elements.
- The Presentation layer will be in the web folder. All visual frontend code will be based in this folder.This will primarily be written in Vue and Typescript.
- The API layer will handle requestsf rom the frontend and accept CRUD requests from the frontend. This will work with the mongoDB that we will be given access to.

## Starting the Front End
1. The most important package is Node.js, this will be used to download most of the other dependencies. The download link is https://nodejs.org/en/download/

2. To acquire the rest of the dependencies for this project, open up the repository folder in VScode.

<img src ="../Documentation\Assets\open_in_vscode.png" alt="Folder open in VsCode" >
3. Now we need to open up a terminal to install dependencies for the front end<br>
    cd web<br>
    npm install
<img src="../Documentation\Assets\install_deps.png" alt="deps installed">

4. Now that all of our dependencies are installed we can run the web page.<br>
By running:<br>
    npm run serve<br>
The home page will be avaialble at localhost:8080. View it in your browser<br>
<img src = "..\Documentation\Assets\home_page.png" alt="home page">

## Starting the API
Since the api is running node, there is a similar process to starting the front end.

1. Start with a terminal at the root of your project. Then <br>
    cd api<br>
    npm install<br>  
This will install all dependencies needed for the api.
<img src="../Documentation\Assets\deps_for_api.png" alt="Install deps for API">

2. Now we can run the command<br>
    npm start<br>
And the server will be running on port 3000.
<img src="../Documentation\Assets\server_started.png" alt="server running">

The API is now running and ready to recieve requests.

## Running Tests
This project uses Jest as a testing framework. All tests can be run through npm.
 ### For API Tests
 1. Set api as your current directory in the terminal
 2. Run the command <br>
 "Npm run test:unit"<br>
 3. All unit tests will run and the output will be placed in the console.
