# angular-cli-learning
I am learning angular-cli with less.. so far followed the below steps..

1. Installed node js.
2. Installed angular-cli

Once the cli is installed, followed below steps to create a new project.

1. Open Node.js command prompt.
2. run commad # ng new <<app-name>> --style=less.
    --style attribute is used to create less file.. if this option is not provided then by default it will use css..
3. Once the project is created, I used the command
      - ng eject. 
      
	  This command ejects the webpack.config.. 
      Now, the cli commands like ng serve, ng build can not be used. you need to use the following command ..
   	
            To run your builds, you now need to do the following commands:
    - "npm run build" to build.
    - "npm test" to run unit tests.
    - "npm start" to serve the app using webpack-dev-server.
    - "npm run e2e" to run protractor.

