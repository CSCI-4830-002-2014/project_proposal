# Final Project Proposal

Use this template to submit your project proposal and we will vote on them next week to decide 4 to implement in the final project.  Remember this project will be a single feature in a multi-feature exhibit for the ATLAS Lobby.

## Description
This could be difficult, but It could be interesting to have a microphone set up to record all the conversation that's taking place in the lobby. The recorded files could be sent through an API that parses meaningful words, and a counter could be kept to see how often each word is spoken. The data could be kept in a database, and a webpage could draw data from that database to create a word cloud, where words spoken more frequently would be larger than other words. A tv could then be used to display the webpage in the lobby.

## Interaction | Data Capture
An arduino with an internet connection would have a microphone to take sound samples and send it to the speech-to-text API. I'm not 100% sure if all of this can be managed from an arduino, but it doesn't seem out of the question.

## Vizualization
The screen would simply display a webpage, which would refresh its visualization at a regular interval.

## Milestones
- Find an API that could be easy to interact with using an Arduino.
- Build the arduino circuit to record sound samples. This would likely require a microSD card to store the data before it is uploaded to the API. The resulting text from the API could then be sent to a PHP script via POST to enter into a MySQL db. 
- Build a simple webpage with a word cloud visualization that can update itself at a regular interval.
- Setup the project in the lobby?

## Necessary Tools
Arduino, microSD, microphone, WiFi shield?, MySQL, PHP, D3, TV

## Supporting Images
Example of a word cloud

![image](http://www.pragmaticea.com/images/160-challenge-word-cloud-raw.png)
