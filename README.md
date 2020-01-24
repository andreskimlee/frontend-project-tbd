# Outernets-Project 
    This Application was made as a mock task by Outernets. In order to produce the most authentic scenarios, I began by picking a mock company which in this case was DuoLingo. The project is focused on an interactive ad experience and allows users to speak to individuals around the world. In my use case scenario, the applications would exist in high traffic areas around the globe using a display with a camera and microphone. Users would then be given options to choose from different countries and use duolingo to practice speaking the chosen countrie's language and converse with strangers from the chosen country. I believe this ad would help achieve three potential things for duolingo. 

    1. The ability to exercise their brand name on a broader level
    2. Give future customers the potential use case of duolingo
    3. Expand to untapped international markets

 ![alt-text](https://i.imgur.com/11Hu6ny.png)

## Technologies
-Javascript
-React
-jQuery/Json/Jbuilder 
-CSS
-Socket.io
-Annyang 
-express
-simple-peer

## Features 

This project utilizes Annyang to allow users to control certain functionalities of the project. In the current version, if the user says "Hong Kong" the page will shift to the proper location.

Along with the implementation of websockets, we were able to include a live video chat functionality. This would give users a real time experience versus the pre-recorded alterior option.

![alt-text](https://i.imgur.com/5VTz75Y.png)

## Future Features 

Since the project was finished within 2 days. A vast majority of future updates could further improve user experience. Currently the voice commands are only allowed to one country (Hong Kong). Future implementations would include multiple chatrooms for each country as well as voice commands. 

Translations could also be updated to real time. For example, using Google Translate API along with Annyang would allow users to pick phrases that they would like to say instead of only picking and choosing from the given phrases. 

## How To Run 

First, within the project directory, in terminal, run the following commands in order. 

npm install 

npm run server

npm run start 

you can utilize localhost:3000 to access the website on the clientside.

you can also visit the site on another tab to see the live chat functionality. Keep in mind I would recommend turning off sound since issues do arise from running two video chats on one client. 
