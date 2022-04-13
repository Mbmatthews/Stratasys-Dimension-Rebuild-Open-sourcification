# Stratasys-Dimension-Rebuild-Open-sourcification
The purpose of this project was to rebuild an out-of-service Stratasys Dimension 1200es printer using open-source or off the shelf components vs paying thousands of dollars for parts from Stratasys.  

This machine will be run on Klipper with a raspberry pi 4b as the host and a BTT Octopus as the mainboard.  The repos for fluidd-klipper and the octopus board documentation can be found below:

https://github.com/fluidd-core/FluiddPi/releases/tag/v1.17.0
https://github.com/bigtreetech/BIGTREETECH-OCTOPUS-V1.0

Fluidd is the web ui that will run on the pi giving easy access to the klipper config files.  Due to networking issues at my work this will probably not be super useful so an ethernet connection directly to the pi will probably be necesarry to ssh into it to get the files, change network settings, etc. 

Starting with hardware, there are a ton of 3D printed mounts being used in this project to adapt newer electronics to this printer's form.  All the mounts are found in the 3D CAD folder of this repo.  Almost everywhere utilizes tapered m3 brass threaded heat-set inserts and the ones that the parts are designed for are these from McMaster Carr:

https://www.mcmaster.com/94180A333/

