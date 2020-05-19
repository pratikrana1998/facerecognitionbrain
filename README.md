FaceRecognitionBrain is a React app created with [Create React App](https://github.com/facebook/create-react-app).

FaceRecognitionBrain helps users to detect faces in an image. It also keeps a track of the number of images submitted by the user for detection.

The facial recognition is performed using Clarifai API.The app contains a sign-up/sign-in feature so that a particular user can keep a track of the number of images submitted.

This project uses React.js, Express.js and Particles.js for the app creation.PostgreSQL is used for database.The app has been hosted on Heroku which can be accessed using the link: 
https://smart-brain-nw.herokuapp.com/

or

You can run the app locally by cloning the [smartfacerecognition](https://github.com/pratikrana1998/smartfacerecognition) and [smart-brain-api](https://github.com/pratikrana1998/smart-brain-api) repositories and follow the following steps:

1. On one terminal, map into the directory smartfacerecognition and run:

   ### npm start
   
  This runs the app in the development mode.

2. On the second terminal, map into the directory smart-brain-api and run:

   ### nodemon server.js
   
  This start the server on port 3000(if no port provided).
  
3. You are ready to go :) 
   Open http://localhost:3000 to view the app in browser.
