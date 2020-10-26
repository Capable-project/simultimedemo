# simultimedemo
## Simulation of passing time for the M12 demo

This example implementation in Java uses facilities provided by an ntp server to create a simulated timekeeping utility that can be used to simulate time during M12 demo
The basic example is heavily based on org.apache.commons.net example. You need this library to successfully runnung it (tested on v3.7.2 by Enea).
The Java "simulated clock" example has the advantagde of not needing to tamper with the system (OS) clock. However, it needs explicit handling in one own component's code.

## Usage
re-build the jar (or get it from out/artifacts) and run `java -jar NTPsimulatedTime.jar <ntp-servers-ips/names>`

Check the source for an example client to be used in your (Java) component 
