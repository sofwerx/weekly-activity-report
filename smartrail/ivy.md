# Welcome to the TrackingPoint wiki!

## Introduction

This is a wiki! This a log of my participation in the development of the Sofwerx Ballistics Rail project. [Sofwerx](http://www.sofwerx.org) is an organization devoted to open-sourcing solutions to challenges faced by warfighters every day. My job for the Ballistics Rail is to explore the onboard TrackingPoint and the Freefly Movi Pro API. Furthermore, I am responsible for designing a potential jig to hold the TrackingPoint scope to the gimbal.

### Objectives

* An mechanical stabilization technique to compensate, which can be accomplished by using the gyroscopic properties of a microcontroller to read position shift

* A learned (programmed) iteration that responds when TrackingPoint loses pixel focus

* A _fast_ response to change in position and pixel count, use onboard microcontroller and fpga to articulate

* TrackingPoint needs to talk to the gimbal through the API

## Local API

### Software Week 1

* Collect and read articles about API and machine vision

* Develop objectives

* Explore gitlibrary on machine vision

* Write pseudocode (language agnostic); identify knowns and unknowns

* Research onboard GPSD

* Explore microcontroller options

### Remarks

Movi is has an inhouse API, or application programming interface. The Freefly Movi Pro is equipped with a UART, which significantly cut down on issues with latency, loss of connectivity at range, and downlinking footage collected by TrackingPoint. A manual for installing and using the [wired control kit](https://docs.google.com/document/d/1qa3gVP6pLHrm3hnCwvvhwuEXsQqguN1mVEZPocE62hg/edit) is included here.

While the manual itself is [dense](https://freeflysystems.com/app/uploads/2016/10/MoVI_Pro_Manual_Revision_B.pdf) as all get out, it is accessible enough that any novice maker could find their way around it. This in itself is great! Movi encourages [makers](https://docs.google.com/document/d/16L65isO7Ifh3iWyqnqK69DHKzTWpJYlfl-hDMx7ABkY/edit#heading=h.xu33z8iy5tix) to use their software and get involved. They have even gone so far as to publish their API to allow for [total open-sourced-ness](https://docs.google.com/document/d/1eNkpmxHHc22ooSi0EKxd6F0UNi5H_kI13hzm_rTR8i0/edit#heading=h.855aj17okdm1), provided you have a really nice Freefly Movi gimbal to articulate it. Finally, Freefly compiled notes on the [Velocity Installation Kit](https://docs.google.com/document/d/1p07Qsav7vRJKuUCxo9bHuJ3pkUOJ8CtD92v53lb-FUY/edit). Once an Freefly user has installed the kit to the device, and implemented effective landing gear, data can be collected to improve the Movi experience. This could be highly effective for later testing. Finally, [new software standards](https://docs.google.com/document/d/1wCmwA43pr8ienBFm46D-PwgX9HFo0surBgx3MBcIKlo/edit#heading=h.iv4btsltlqn2) were released indicating updates to the Freefly system we are currently working with.

## Mechanical Considerations

### Mechanics Week 1

* Watch videos on SolidWorks construction of Picatinny Rail

* Become comfortable with SolidWorks 2016/17 controlls

* Record Freefly/TrackingPoint dimensions

* Bill of materials

### Remarks

So far, the biggest problem with stabilizing the tracking function of the TrackingPoint itself was the jittery effects of the gimbal. Previous designs consisted of a stepper motor and a 3D printed housing. In theory the 3D printed material would provide a smooth surface with minimal friction.

## Ballistic Rail Meeting 9/7/2018

Met with David Akers, Matt Cohen of Space Coast Unmanned and Mujahid Abdulrahim. This meeting was held to discuss the progress of the Ballistic Rail. Microcontroller options, and RF communications were discussed, as well as the transition of the project from this intern's purvey to Unmanned Drone.
