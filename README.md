# Final Project Proposal

Use this template to submit your project proposal and we will vote on them next week to decide 4 to implement in the final project.  Remember this project will be a single feature in a multi-feature exhibit for the ATLAS Lobby.

## Description
The project would essentially be an interactive map of the ATLAS Lobby, where the position of the people in the lobby are shown as marks on the map, with tracks showing how they have moved around.
In addition, the flow pattern of how people in general moves around could be shown.

## Interaction | Data Capture
The project would need a few cameras mounted in the ceiling, and some hardware/software that can track motion. This data could then be used for live data display and be collected for other kinds of analysis.
Interactivity, like messages or on screen data updates, could be triggered if someone appears to stop in front of the map.

## Vizualization
The visualization would be presented as a live map of the lobby.

## Milestones
[Give a rough flow for your project.  Explain the steps that would be involved to move from idea to completed implementation.]

The hard part about this project would be the data collection. The most viable solution I can think of is coupling the camera with some hardware capable of running OpenCV, like a Raspberry Pi, which would process the live image data and convert it to coordinates.

When the data source is set up, the next step would be to visualize the data. This could be done on another computer, using mongodb and D3 to constantly poll and store the data, and update the visualization.


## Necessary Tools
The image analysis would require OpenCV which is implemented in C++, but interfaces for many other languages seem to exist. The visualization would be done in D3. The project would require a Raspberry Pi with one or multiple cameras, and a computer for doing the visualization.

## Supporting Images
