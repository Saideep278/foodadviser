open folder
split terminal for client side(react) and server side


CLIENT TERMINAL
cd client
npx create-react-app ./
npm axios moment react-file-base64 redux redux-thunk 

npm  config set legacy-peer-deps true

npm i @material-ui/core

npm i @material-ui/icons

npm i react-router-dom

npm i react-redux

npm i jwt-decode react-google-login

# axios for making api requests
# moment is a library for time and date
# react-file-base64 for photos
# redux redux-thunk to perform asynchronization tasks by redux





SERVER TERMINAL
cd server
npm init -y
npm install body-parser cors express mongoose nodemon
# body-parser for post request 
# cors for cross origin request
# express for framework
# mongoose for models
# nodemon for reset the changes saves automaticlly
# in package.json add "type" = "module for latest version of import statements

#  in package.json "scripts" -> "start":"nodemon index.js"

npm i dotenv

npm i bcryptjs jsonwebtoken



delete src in client 
again create src and src/index.js which connects index.html and index.js
create app.js in src
npm start

in server/index.js
create app=express()


create cluster in mangodb atlas connect database network aceses




SVGbackground.com



heroku and netlify




