# GaggiaPico

# Status Report - 13 NOV 2021
Working on copying and modifying the code from https://github.com/kkalbaugh/raspberry-freezer-monitor/blob/master/max31865.py
I know some programming basics and little of Python, so this is a real eye-opener. The original code was written for Raspberry Pi,
so I think have to modify it slightly.

I'm currently stripping it of the Internet code, and removing all the fault status code. I plan to bring fault status information back,
I really need a motivation boost, and I think seeing it output a resistance/temp would be the ticket.



First and foremost, the purpose of this project is to upgrade my Gaggia Classic Pro using at Raspberry Pi Pico. At the same time,
I am also learning about embedded systems and re-learning programming while doing this project. Prior to this project, I have had no education
on embedded systems/software. I have also never worked on an electronics project. This project is currently using MicroPython.

The components used in this project have be throughly influenced by magnusnordlander(https://github.com/magnusnordlander/silvia-pi). 
They upgraded a Silvia with a Raspberry Pi Zero for their unit.

The most imporant goal from this upgrade is to have a controllable and regulated Boiler temperature. My assumption is to use PID control.
In regards to PID control on the Gaggia Classic, I have heard a copper tubing pipeline around the boiler can help preheat the supply water.
This not only increases the energy efficiency of the unit by using waste heat, but it also gives better PID control. The preheated supply water
with have less of an effect on the boiler temperature.

The plan is to have wireless capabilites, data logging, PID Temperature control, controllable pressure, possibly have the ability to save profiles and replay it.

Most of the electronics have already been purchased.

This README will be cleaned up, and updated, at a later time.
