# lab-ses-hab
Software for the LAB-SES HAB (wip). It's really messy as of now. 

Watchdog function hasn't been tested yet, but I'm pretty sure it works. EDIT: Yes it does work

The software will only run on AVR chipsets, since it's AVR specific. I'm sure you can modify the watchdog with a seperate circuit to work better on other chipsets if needed. 

Since the arduino will be running in a near space environment, a watchdog is needed to prevent *bit flips* and *errors*. A NASA study found that on average a HAB could get struck by a high-energy perticle every 2 hours. Since the average flight time of our HAB is predicted to be 4 hours we need to be prepared, especially with the solar cycle rising. 
