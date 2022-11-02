# DG-Executables
Executables needed in the data glove project

## Contents

* DataGloveReader (DGR) - handles connection to the data glove
* DataGloveReaderHandler - starts DGR and the python based gesture recognition and handles the communication with the android app
* Utilites.cmd - can be used for various utility functions (like downloading frames from the database as json)

## How to use

1.	Ignore the bin folder and its content unless you know what you’re doing!
2.	double click on "START.cmd" 

The program will now continuously try to connect to the hub. If you see error code 9999, this means that the hub couldn't be found. Check if you made a mistake with your network configuration.
The PC should be connected to the “AT Lehmann” wifi.
After connecting to the hub, it will be configured automatically. This might fail a few times and then the process will restart automatically. If it fails more than 5 or 6 times in a row, close the cmd window (the black window with the white text), wait ~30 seconds and then double click on the “START EVERYTHING.cmd” again.

3.	No further interaction is needed with the pc. Just leave it on and do NOT close the cmd window!
4.	Check the status indicator in the lower left corner of the tablet app. Yellow means startup in progress, green means, that everything is ready!
