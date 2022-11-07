# Development



## Suggested IDE
-  Microsoft Visual Studio Code 

## Project Structure
This project is written in two distinct elements.
- The Presentation layer will be in the web folder. All visual frontend code will be based in this folder.This will primarily be written in Vue and Typescript.
- The API layer will handle requestsf rom the frontend and accept CRUD requests from the frontend. This will work with the mongoDB that we will be given access to. This will be written in Javascript, through the express and node frameworks.

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
- If there are any dependencies that are missing, make sure to run npm install "package name"
<img src = "..\Documentation\Assets\home_page.png" alt="home page">

## Starting the API
Since the api is running node, there is a similar process to starting the front end.

There will be a .env file that will neeed to be given to new devs. It will contain the connection string to connect to the backend.(This is not set yet)

1. Start with a terminal at the root of your project. Then <br>
    >cd api<br>
    npm install<br>  

This will install all dependencies needed for the api.
<img src="../Documentation\Assets\deps_for_api.png" alt="Install deps for API">

2. Now we can run the command<br>
    >npm start<br>

And the server will be running on port 3000.
<img src="../Documentation\Assets\server_started.png" alt="server running">

The API is now running and ready to recieve requests. Any request that fails, will throw an error in this terminal. Look here if a request fails to return to the frontend.

## Running Tests
This project uses Jest as a testing framework. All tests can be run through npm.
 ### For Unit Tests
 1. Set web as your current directory in the terminal
 2. Run the command <br>
 >Npm run test:unit<br>
 3. All unit tests will run and the output will be placed in the console.
<img src="../Documentation\Assets\console_after_tests.png" alt="console after tests">

## Writing Tests
Sample Test
<img src="../Documentation\Assets\writing_test_sample.png" alt= "writing test sample"><br>
1. Give the test suite the name of the the component you are testing. In this case, it is VideoEditor.vue
2. In the beforeEacht, mount your component. This means that each test will have a component in the dom to test. Mount is needed to test children component, but it is often better to shallowMount to increase test speed
3. Write your test case. In the it() write the actions that your test will be taking, and at the end expect a value.

Try to write a test for every function a component has. Try to be as comprehensive as possible.