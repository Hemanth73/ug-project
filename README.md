# Development of converter and controller for permanent magnet brushless DC Motor drive for air conditioning application
#### Mentor - [Dr. Kalpana Choudhary](http://www.iitbhu.ac.in/dept/eee/people/kchaudharyeee)

Student                  | IIT(BHU) Roll Number
-------------------------|---------------------
Narkedamilli Sai Sumanth | 15084010
Chandan Kumar            | 15085023
V Hemanth Sai            | 15085073
Vunnava Saikiran Kumar   | 15085075

## Abstract
This project deals with a Cuk dc–dc converter as a single-stage power-factor-correction converter for a permanent magnet (PM) brushless dc motor (PMBLDCM) fed through a diode bridge rectifier from a single-phase ac mains. A three-phase voltage-source inverter is used as an electronic commutator to operate the PMBLDCM driving an air-conditioner compressor. The speed of the compressor is controlled to achieve optimum air-conditioning using a concept of the voltage control at dc link proportional to the desired speed of the PMBLDCM. The stator currents of the PMBLDCM during step change in the reference speed are controlled within the specified limits by an addition of a rate limiter in the reference dc link voltage. The proposed PMBLDCM drive (PMBLDCMD) is designed and modeled, and its performance is evaluated in Matlab–Simulink environment. Simulated results are presented to demonstrate an improved power quality at ac mains of the PMBLDCMD system in a wide range of speed and input ac voltage. Test results of a developed controller are also presented to validate the design and model of the drive.

## Synopsis
#### Semester VI:
We plan to get acquainted with PMBLDC Motor and study its normal operation by running experiments in the machine laboratory. Then we will simulate a three-phase voltage-source inverter as commutator for the PMBLDC Motor in Simulink. This inverter will be controlled using hall signals from the PMBLDCM which will be the compressor of air conditioner.  Then we will design a Cuk converter as power factor correction unit for the PMBLDCM and simulate it. The Cuk converter will then be used to set the dc link voltage for the inverter. We will then design a controller for the Cuk converter to control this dc link voltage. Then we will use this controller for Cuk converter to control the speed of motor by controlling the dc link voltage. We then plan to optimize efficiency of this system by tuning various elements used in it.
#### Semester VII:
After successfully completing the simulation, we will implement the hardware version of all the components used. These will include the Cuk converter and the controller for the Cuk converter.
