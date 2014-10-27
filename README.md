# Final Project Proposal

Use this template to submit your project proposal and we will vote on them next week to decide 4 to implement in the final project.  Remember this project will be a single feature in a multi-feature exhibit for the ATLAS Lobby.

## Description

My idea would be to use the SORCE (Solar Radiation & Climate Experiment) Satellite data available [here](http://lasp.colorado.edu/home/sorce/data/) and show the change TSI (Total Solar Irradation) or SSI (Spectral Solar Irradiance) over its 10+ year lifetime.  The speed at which we cycle through the data visually can dynamically respond to the activity in the room.  For example, the visualization will spin through 1 year per minute when there is a lot of noise and movement (either based on proximity or general motion), but may change at only 1 day per mintue when the ambiance is less intense.

Individuals will be able to interact with a fun visualization while learning about the sun's cycles (important for understanding/predicting solar flares and climate change).  Plus it's neat that this data comes from the LASP, which is part of the University.

## Interaction | Data Capture
A combination of proximity/motion and noise with cause the visualization to react to the ambiance in the room.

## Vizualization
It will be projected onto the wall.

## Milestones
* Analyze and clean the data
* Conceptualize a visual abstraction
* Create an algorithm that interprets arduino data and interacts with the visualization
* Implement and piece together

## Necessary Tools
Arduinos, D3, javascript, IDL is probably unnecessary but may come in handy if we want to use the query wrapper that's provided on the site

## Supporting Images
I am really inspired by this [visualization of the earth](http://earth.nullschool.net), which I belive is implemented in D3.  We probably don't have the time to simulate the sun itself, but can definitely create some sort of abstraction that represents the data.

[Here](http://lasp.colorado.edu/lisird/sorce/sorce_tsi/) is also a graph of the TSI data over time.  The break in data was caused by mechanical issues (understandably, since the satellite has exceeded its expected lifetime by twofold).
