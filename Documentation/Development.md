# Development
## Source Code
The source code for this project is located at:<br>
 <a href="https://github.com/BRADrocket72/right-call-web">https://github.com/BRADrocket72/right-call-web</a>

 You can download the zip file, or open it through an IDE. To open it through visual studio code:<br>
 1. Open a new VSCode Window and click on Clone Git Repository
 2. Paste URL from above into the commant pallete
<img src='./Assets/clone_repo_dev.png' alt="Cloning repository through VS Code">
 The repository should pull down the code from the main branch.<br>

 ## Rules for Pull Requests
 For any new features, they must be made on their own branch. When the feature is complete, please go to github, and create a Pull request into the main branch. At least one other developer must apporve the request before it is merged in.


## Suggested IDE
-  Microsoft Visual Studio Code 

## Project Structure
This project is written in two distinct elements.
- The Presentation layer will be in the web folder. All visual frontend code will be based in this folder.This will primarily be written in Vue and Typescript.

## Managing Environmental Variables
The API and Web both contain secrent connection variables that are essential for them to function. To use them:
1. Ask a current developer for their .env file.
2. Copy the sample.env file from your project
3. paste the file in the same place, and rename it .env
4. Paste the values of a current users .env file.

## Replicate via Docker
This project contains a .devcontainer file that can be rna to ensure all developers have the same VSCode extenstions installed. Running in a dev container can take a lot of resources, but it helps ensure that the project is run in similar environments on each machine.

1. When the project has been cloned into VSCode, a popup will appear in the bottom right. click "Reopen in a Dev Container".
This will build the container, and install all of the dependencies needed to get started on the project.
<img src="../Documentation/Assets/start_in_dev_container.png">
2. If the project is running too slow, please provide Docker with more resources through the Docker Daemon on desktop. Follow the <a href="https://docs.docker.com/config/containers/resource_constraints/"> Docker Documentation for adding more resources</a>

## Starting the API
Since the api is running node, there is a similar process to starting the front end.

1. Start with a terminal at the root of your project. Then <br>
>   `cd api`<br>
    `npm install` <br>
>
This will install all dependencies needed for the api.
<img src="../Documentation\Assets\deps_for_api.png" alt="Install deps for API">

2. Now we can run the command<br>
    `npm start`<br>
And the server will be running on port 3000.
<img src="../Documentation\Assets\server_started.png" alt="server running">

The API is now running and ready to recieve requests.



## Starting the Front End
1. The most important package is Node.js, this will be used to download most of the other dependencies. The download link is https://nodejs.org/en/download/

2. To acquire the rest of the dependencies for this project, open up the repository folder in VScode.

<img src ="../Documentation\Assets\open_in_vscode.png" alt="Folder open in VsCode" >
3. Now we need to open up a terminal to install dependencies for the front end

>`cd web`<br>
`npm install`

<img src="../Documentation\Assets\install_deps.png" alt="deps installed">

4. Now that all of our dependencies are installed we can run the web page.<br>
By running:<br>
>`npm run serve`

The home page will be avaialble at localhost:8080. View it in your browser<br>
- If there are any dependencies that are missing, make sure to run npm install "package name"
<img src = "..\Documentation\Assets\home_page.png" alt="home page">


## Running Tests
This project uses Jest as a testing framework. All tests can be run through npm.
 ### For Unit Tests
 1. Set web as your current directory in the terminal
 2. Run the command <br>
 >`Npm run test:unit`<br>
 3. All tests will run and the output will be placed in the console.
<img src="../Documentation\Assets\console_after_tests.png" alt="console after tests">

### For backend tests
In the terminal, if you are in the api folder, running
>
`npm test`
>
Will run all the backend tests in the __test__ folder

 ### For Integration Tests
 This project uses the Cypress testing framework for integration testing.
 1. Make sure both api (`npm start` in api directory) and front end (`npm run serve` in web directory) are both running in terminals before running these tests. 
 2. Set web as your current directory in the terminal and run the command <br>
 >`npx cypress run`<br>
 3. All integration tests will run and the output will be placed in the console. 
 <img src="../Documentation\Assets\integrationTestResults.png" alt="console display after tests">

## Writing Tests
Sample Test
<img src="../Documentation\Assets\writing_test_sample.png" alt= "writing test sample"><br>
1. Give the test suite the name of the the component you are testing. In this case, it is VideoEditor.vue
2. In the beforeEach, mount your component. This means that each test will have a component in the dom to test. Mount is needed to test children component, but it is often better to shallowMount to increase test speed
3. Write your test case. In the it() write the actions that your test will be taking, and at the end expect a value.

Try to write a test for every function a component has. Try to be as comprehensive as possible.

# Linting
  This project uses the default typescript style guide. It will only check .ts files, so as we progress more into typescript this will become more beneficial. To run the linter navigate to the web or the api folder. From there run 
  >`npm run lint`
  
  This will mark any styling errors and is encouraged to run before every push to main.