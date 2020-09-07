# RadioBoard Backend Node.js App

This app does two things, first is host the collaborative whiteboard drawing code & secondly communicates with the drawn shape & text recognizer & relays the data to the Teams addon.


## Steps to run

1. Clone this repo

2. First install modules with ```npm i``` & then run ```node server.js```, server will run on port 5000 locally

3. Host the app on an HTTPS service like ngrok or Heroku for free. Since Teams add-on already uses ngrok we need to use Heroku to deploy the application.