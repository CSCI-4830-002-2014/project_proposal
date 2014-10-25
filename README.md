# Final Project Proposal

Use this template to submit your project proposal and we will vote on them next week to decide 4 to implement in the final project.  Remember this project will be a single feature in a multi-feature exhibit for the ATLAS Lobby.

## Description
I discovered this really cool [Python library](http://jdan.github.io/Melopy/) which takes input in the form of some music and makes interesting 16-bit sounding wav files to be played from it. My plan would be to use the Arduino to capture some data in the lobby either via a microphone or light sensor, uplaod the data to a server running the library. The server would then render it into a .wav file which will then be posted to a minimal web server for people to vote on, play, and interact with. 

## Interaction | Data Capture
It would simply pick up ambient noise or light in certain areas and use it as a seed value to generate some random music. 

## Vizualization
We could plug it into a visualization libaray and display it on the screens or we can just use some speakers. 

## Milestones
Some of the milestones are: 

- Get the arduino set up so it can capture input. 
- Take averages of the input. 
- Pass the averages to a server to be analyzed. 
- Generate a music file from the input. 
- Render the music file on the server. 
- Post the music file onto a dyanmic webpage possibly for people to vote on. 

## Necessary Tools
Programming Languages:
- C (arduino)
- Python (web server)
- Music (mlp melopy format for music)
