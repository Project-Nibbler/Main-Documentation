![Screen Shot 2024-05-07 at 7 39 55 PM](https://github.com/Project-Nibbler/Project-Nibbler/assets/43685920/a28b5fc4-33dd-41cb-9eb1-91ef7dac5f9e)
# Project Nibbler
Open source pick and place object assembler add-on to the Ender 5 pro 3D printer.  
https://research.avenues.org/moonshots/project-nibbler/
## Introduction 
Nibbler is a pick-and-place add-on to the Ender 5 pro that can build and assemble 3D objects from building block "pucks". 

This repository contains everything needed to set up a Nibbler machine from scratch. 
## Project Status
This repository represents the culmination of four years of work on Project Nibbler done by four generations of Avenues students from Sao Paolo, Brazil and New York, USA.

## Ender 5 pro setup
The Nibbler pick and place machine is an add-on to the Ender 5 Pro. The following modifications must be made to a stock Ender 5: 
 
The Creality Ender 5 Pro is the 3D Printer base that we are hacking and customizing to be able to print with nibbles and binder matrix.
* Build Volume: 220mm x 220mm x 300mm (8.7" x 8.7" x 11.8")
* Frame: Aluminum
* Kinematics: Cartesian XY-head
* Bed leveling: Manual

## UV Light System

## Suction

## Puck Dispenser

The puck dispenser is a contraption that holds up to a hundred pucks. It dispenses pucks one at a time, in a flat orientation, for the suction nozzle to pick up. The puck dispenser encorperates a windmill roller design, which stirs pucks inside, and forces it down a chute. This orients the puck correctly.

### File structure
parts/hopper.STEP --> CAD model of puck storage hopper 

## Resin
Currently, resin is injected into the resin container manually every 10 minutes. The puck is dipped into the resin and cured onto the build plate. An additional customization option is creating an automatic resin dispenser with a motor actuator connected to a long tube. 
## Slicer (Code)


