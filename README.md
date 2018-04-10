# CSNE2018-MyoADD
Wrist driven orthosis (WDO) acontrolled by Myo and RPi, project for CSNE Hackathon 2018.

This repository contains the work developed during the CSNE hackathon 2018. Event description: The CSNE Hackathon is an annual, extended weekend-long event that takes place in Seattle, WA. Local and out-of-state participants hack away with cool technology and come up with prototypes for neural engineering solutions.

The Myo controlled WDO is comprised of major components: 3D printed WDO, Myo armband by Thalmic Labs, and Raspberry Pi. This repository does not provide detail necessary to construct the mechatronic WDO, however contains many of the source files used to produce the prototype.

Motivation: 3D printing movement in consumer market and academia to develop prosthetics and orthoses in open-source format

Goal: Bring additional functionality to purely mechanical assistive devicecs with mechatronics: myoelectric inputs and haptic feedback

Case study: Modify WDO to incorporate (1) finger lift functionality so user can interface with touchscreeen devices by independently lifting the index finger and (2) grip force feedback for grip strength through haptic. 

What we did: 
  - Downloaded open-source SolidWorks files produced by Steele Lab
  - Modified CAD to add functionality to add index finger lift
  - Connected Myo to Pi via bluetooth
  - Interfaced WDO with servo motor and force sensitive resistor (FSR)
  - Controlled servo motor with gestures from Myo
  - Trained Myo on custom gestures
  - Triggered Myo vibration feedback from FSR signal threshold
