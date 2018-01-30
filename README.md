# odd_couplings

this repository contains a processing sketch I coded for a performance with a bunch of great performance artists.
This particular one is a swarm surrounding the auras of two performers, Nuria and Santaiana. The behaviour is based on fluid mechanics.
The swarm is "actuated" by data comming from two wearable motion sensors, designed and build by Moritz Kemper.

The sketch uploaded has the "initSensors()" function commented to allow the code to compile, otherwise it would try to access
the serial port which obviously you can't since you ain't got the sensors with you. But you can easily replace this with your own
or with other devices to input signals.

I made use of a Java Implementation of the Navier-Stokes Solver Link also included in the sketch.
http://www.dgp.toronto.edu/people/stam/reality/Research/pdf/GDC03.pdf

Hope this is useful to anyone keen on exploring the world of fluid physics.
