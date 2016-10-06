# LawGameV6

Law Game Web App

Have MongoDB and NodeJS installed

Then:

Clone this repository (it has node_modules excluded in the npm)

npm install inside the root folder

Run mongod. If you don't have it as a system variable, use this video here: https://www.youtube.com/watch?v=sBdaRlgb4N8&feature=youtu.be&t=120

Run node server.js from the root folder

localhost:8080/

This game is meant to be a quick-pay game (i.e. it does not save user results) that tests users' knowledge of contract law.

The user will first enter their name on the login screen, and will be able to choose from a set of scenarios, each of which has multiple questions. The data for each question is extracted from the pre-populated MongoDB database, but which can be edited on the fly via an admin site.

The game progresses with stimulus scenes followed by question scenes in a repetitive manner. 

Type '/editor/ at the end to enter the editor page; every other page is accessible from the login screen by going through the steps.
