# homeevents

## What it is
A simple, event-driven home automation system. By 'simple', I mean conceptually simple. This will, initially at least, be very specific to my home setup and will require significant modification if someone wants to use it in their own home. Maybe someday it will be more user-friendly and configurable.

My motivation for writing this is to replace a commercial system that is nice, but has some issues and is not fully local because it runs "in the cloud" (meaning sometimes my lights come on as I leave the room, not enter it). I looked at on open solution which seems very good and on the right track, but the documentation was limited and it was overly complex for what I needed (a lack of good documentation and some significant complexity are not a good combination).

This is also a learning opportunity for my to learn things like node.js and Javascript (so if you see less than ideal code...)

## Requirements
You'll need: 
* [node.js](https://nodejs.org/en/). I am using version 4.4.3.
* [node-openzwave-shared](https://github.com/OpenZWave/node-openzwave-shared) which brings it's own requirement for open-zwave (see the [node-openzwave-shared README](https://github.com/OpenZWave/node-openzwave-shared/blob/master/README.md) ). I'm using 1.1.9 (which seems to have disappeared from the list of releases, but I'm sure 1.2.0 will work just fine).

## More Info
See the [Wiki](https://github.com/dougdale/homeevents/wiki) for more information.

