## MERN Template

This repository is the boilerplate for MERN stack. It sets up a simple http server and serves HTTP requests using REST protocol with the help of express library.

## Structure

### bin
The bin folder has the www file which starts the server and does some preprocessing and postprocessing jobs.

### controller
This folder has all the middleware functions pertaining to a specific subroute. Each subroute should have a file of its own.

### db
This folder is initialized with mongodb connection setup. You need to write down the schema and the querying functions required here.

### helper
Auxilliary functions that takes care of the readability, reusability and logging of the code.

### routes
This folder contains all the subroutes and the list of middlewares that are required for it.

### views
These are the view pages just required for verifying initial setup. Can be used extensively if you are not planning to add a frontend to your stack. Currently used engine is jade.

### .env
You need this file to hold all environmental variable that are necessary for the functionality of the application. It is recommended that you do not push this file to the version control for security reasons.

### app.js
The file where the express server is created and configured along with the listing of all the major routes.