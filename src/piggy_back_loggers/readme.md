#Brief decription of the source code for AggieWater smart metering devices

###Conf_reader.py

This script is run automatically by the sensor_module to read the study site configuration file.

###filenamer.py

This script is run automatically by the sensor_module to manage the file creation and naming conventions.

###lib_include.py

This script lists all required dependencies for the sensor_module.

###log.py

This is a script for internal use of the sensor module to manange the messages generated by the system, such as warnings and debug messages.

###sensor_module.py

This is the main script to run the AggieWater data collection system. This script will invoke all neccessary dependencies for the system to work.

###udp_listener.py

Run this script from the terminal to listen to the messages from the AggieWater smart water meter sensor.

###conf.xml

Use this file to configure the datalogger.
