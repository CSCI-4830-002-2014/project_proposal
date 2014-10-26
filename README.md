# Final Project Proposal

## Description

I would like to see an installation that make it almost impossible for the
passerby NOT to interact with it. On top of interacting with the installation
the user should also gain something from the experience. Maybe learn how it was
done, as to encourage him or her to talk about it with friends.

## Interaction | Data Capture

One idea I had was to have a proximity sensor which would adjust the global
color or hue of whatever datapoints we have on the monitor. The display would
indicate whether you were "hot or cold" relative to the location of the sensor.
Once the user got within a certain distance of the sensor, it would unlock a
visualization that the user can interact with.

## Vizualization

The sensor would act as a client, just pushing raw proximitiy data to the
server. The server would follow the observer pattern by waiting for the data
to cross a certain theshold, at which point the it would alter its presentation
making, the it a first class citizen by enabling exclusive interactivity with
the sensor.

Overall though, this will require a dynamic system that delegates tasks to
different programs and sensors. I imagine there will be many different ideas,
so I think it will be important to have a main program which allows the user
to choose which visualization he or she would like to interact with. Something
like an interactive selection screen.

## Milestones

1) Figure out the global "moderator" which controls which interactive display
at the given time. If this is decided early, everyone can create modules which
fit into this framework, making combining all the visualizations much simpler.

2) Get proximity sensors.

3) Find unobtrusive/hidden location for sensors.

4) Write code to collect the data.

5) Write code for interactive data visualization specfic to the sensor.

## Necessary Tools

1) Tools

  * [Raspberry Pi](http://www.raspberrypi.org/)
  * [Infrared Proximity Sensor](https://www.sparkfun.com/products/8958)
  * [Ultrasonic Range Finder](https://www.sparkfun.com/products/639)

2) Languages/Frameworks
  * Javascript/Node
  * C/C++/Whatever weird subset that is for Arduino Programming
  * D3, async.js, underscore.js, paper.js
