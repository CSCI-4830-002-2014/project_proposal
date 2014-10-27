# Final Project Proposal

Use this template to submit your project proposal and we will vote on them next week to decide 4 to implement in the final project.  Remember this project will be a single feature in a multi-feature exhibit for the ATLAS Lobby.

## Description
This project would have a few camera sensors set up around the ATLAS lobby that monitor the movement in the room. The camera sensors would be connected to a computer of some sort (perhaps a Raspberry Pi?) that processes the images (every few seconds or so) and creates an image that is brighter where more movement happens. This can be used to see how well the building is designed for large numbers of students travelling through the lobby.

## Interaction | Data Capture
There are many ways to implement this. One would be to have Raspberry Pi modules that all operate independently and and capture pictures at a constant rate and then uploads them to a central server that analyses them and finds the motion. This would be difficult to have done on the RPi itself because the memory is so low and the processing power is weak to constantly 'diff' images. Could also be done with higher quality webcams on an actual PC. This would allow multiple sources of high-granularity movement to be combined into a 3D visualization.

## Vizualization
The 'heatmap' could be displayed on the screen, with more frequently travelled areas in brighter, or more red, colors. Time can also play a factor, with transparency of different heats fading away the longer that no one has travelled in that area.
This can also be accompanied by sound sensors to correlate the visual movement with sound.

## Milestones
1. Find hardware that supports cameras, buy them
2. Find an image processing library that can detect motion
3. Link the different sources together to get various motion data
4. Extract the portions of image where motion is detected, superimpose it onto a map of the ATLAS lobby
5. Somehow incorporate other sensors into the mix
6. Output the visualization to the ATLAS screen

## Necessary Tools
Some image processing library would be needed. C or C++ might be helpful in this case.
Camera modules (either USB webcams or modules for RPi's)
The actual computing hardware itself
Some links between the devices.

## Supporting Images
[NOT REQUIRED FOR SUBMISSION.  Use this space to add any drawings, pictures, or supporting material that clarifies or exemplifies what you're project would look like or how the visualization would be designed.]
