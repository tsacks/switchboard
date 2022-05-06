![](https://i.imgur.com/Hkzn8Pq.png)

# Switchboard
A flexible input/output system for world-builders using VRChat Udon

__*This project is a work in progress, and this documentation should be expected to update frequently*__

## How it works
Switchboard lets you build a complex network of inputs and outputs, using *cards*. You attach a *card* to a GameObject in a scene, and then connect multiple *cards* together in a *line*. When a *card* gets an input event, it transmits that event on to the next *card* in the *line*.

There are three basic types of *cards*:
- *Callers* emit an event when they're interacted with
- *Receivers* do something when they receive an event
- *Operators* manage signals coming in, and going out
