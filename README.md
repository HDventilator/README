# README
Here we summarize the role of the different repositories within HDVentilator.
More detailed descriptions can be found in the readme files of the individual repositories. 
All of the repositories belonging to the standalone monitoring unit start with "mon-".


## [Mechanics](https://github.com/HDventilator/Mechanics)
Here we provide the 2D and 3D drawings of the mechanical parts in .pdf and .step format
## [Electronics](https://github.com/HDventilator/Electronics)
In the electronics repository a list of all components to build the PC Board for the ventilator are found as well as schematic diagrams and drawings.
## [hdvent-control](https://github.com/HDventilator/hdvent-control)
Software for the arduino controlling the ventilator including libraries for different components

## [mon-frontend](https://github.com/HDventilator/mon-frontend)
This is a front end for displaying data from an InfluxDB database, tailored to be used as a monitor for a ventilator. It is based on Plotly/Dash with a primary goal being easy extension and modification.

## [mon-os-image](https://github.com/HDventilator/mon-os-image)
This repository contains all relevant configuration files and scripts to build the HDVent monitoring device software as raspberry PI image ready for installation.
## [mon-receiver](https://github.com/HDventilator/mon-receiver)
This is the component that runs on the monitoring-raspeberrypi to receive data from the arduino-controller, to feed it into influxdb for later display.
## [mon-protocol](https://github.com/HDventilator/mon-protocol)
This repo contains information on the COBS-based protocol used for the serial data link between microcontroller and monitoring unit.
