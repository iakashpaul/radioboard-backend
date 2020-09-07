# RadioBoard Backend Node.js App

This app does two things, first is host the collaborative whiteboard drawing code & secondly communicates with the drawn shape & text recognizer & relays the data to the Teams addon.


## Steps to run

1. Clone this repo

2. First install modules with ```npm i``` & then run ```node server.js```, server will run on port 5000 locally

3. Host the app on an HTTPS service like ngrok or Heroku for free. Since Teams add-on already uses ngrok we need to use Heroku to deploy the application.




## Overview

My project integrates offline hand drawn shapes & emojis detection as well as text recognition in over 300+ languages and 25+ writing systems including all major Latin languages, as well as Chinese, Japanese, Korean, Arabic, and Cyrillic. And also regional Indic languages like Hindi, Malayalam etc.

How the app is structured-

It has a teams-add on which enables collaboration on the same whiteboard, and a detection pipeline which passes on the selected shapes to the Android SDK, which is wrapped as a web-server to get back the recognition results.

### Frontend- Teams addon 

* The code is hosted on this repo [github.com/iakashpaul/radioboard-frontend](github.com/iakashpaul/radioboard-frontend)

### Recognizer App

*  App code for Digital Ink is here [https://github.com/iakashpaul/radioboard-recognizer](https://github.com/iakashpaul/radioboard-recognizer) 
Shape Recognition 
https://youtu.be/LTAt1Lf9Cks

Collaborative Teams Whiteboard Add-On
https://youtu.be/nzUkhYqUogo