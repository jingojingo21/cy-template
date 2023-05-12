# cy-template

1. Fork this repo

If you want to experiment with running this project in Continuous Integration, you'll need to fork it first.

After forking this project in Github, run these commands:

## clone this repo to a local directory

gh repo clone jingojingo21/cy-template

## cd into the cloned repo
cd cy-template

## install the node_modules
**npm install**

## start the local webserver
**npm start**
  
The npm start script will spawn a webserver on port 8080 which hosts the Kitchen Sink App.

You can verify this by opening your browser and navigating to: http://localhost:8080

You should see the Kitchen Sink App up and running. We are now ready to run Cypress tests.

# launch the cypress test runner
  
**npm run cy:open**
  or 
**npx cypress open**
  
  
shortcut: you can use command npm run local:open that uses start-server-and-test to start local server and open Cypress. When you close Cypress, the local server is stopped automatically. Similarly you can use npm run local:run to start the server, run Cypress tests headlessly and close the server.

