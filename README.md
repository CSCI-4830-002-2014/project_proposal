# Final Project Proposal

Use this template to submit your project proposal and we will vote on them next week to decide 4 to implement in the final project.  Remember this project will be a single feature in a multi-feature exhibit for the ATLAS Lobby.

## Description
Busyness Sensor

## Interaction | Data Capture
[Explain what would drive your installation - i.e., how would the user interact and feed it data or how would it collect data passively]
The sensors would collect data at the doors of how many people come inside of Atlas through (hopefully) any of the entrances.  The users will not even need to know they are being sensed, it should be seamless.


## Vizualization
[How would we present this data on the screens in the lobby?]
As a function of how many people are in the space, it would be cool to have a d3 visualization, showing very slow moving, few in number objects for small numbers of people, that grow to complete anarchy for a high population.  We would want to not make it distracting but somehow interesting if possible.
A stretch goal would be to add a light audio component in a similar manner.  This could easily turn annoying though so it's dangerous.

## Milestones
[Give a rough flow for your project.  Explain the steps that would be involved to move from idea to completed implementation.]
1.) Plan / get approximations of flow through Atlas.
2.) Create interesting d3 visualization that can scale to any number of people.
3.) Setup sensors in lobby and test them to ensure accurate counts are received.
4.) Connect sensors output data into the input of d3 on the screen.
5.) Test, test, test.

## Necessary Tools
[What programming languages, sensors, hardware, etc, are necessary to finish your project]
Some solid d3, at least 2 infrared sensors per entrance to calculate number of people ( although we could only base off front doors), communication between sensors and screen.

If music were involved, we'd need to use something like supercollider (http://supercollider.sourceforge.net/) but the result would be quite similar to the visualization.

## Supporting Images
[NOT REQUIRED FOR SUBMISSION.  Use this space to add any drawings, pictures, or supporting material that clarifies or exemplifies what you're project would look like or how the visualization would be designed.]

Everything is pretty abstract to me at this point, so I'll hold off on this.
