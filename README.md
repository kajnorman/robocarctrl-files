# robocarctrl-files

Cherrypy first experiments
different robocar files for use when learning the controll of this system

Installation to run these experiments
Everything is meant to run on the raspberry pi as installed at the start of the semester.
As cherrypy only runs on version3 of python a number of installations must be carried out.

•	sudo apt-get install python3-pip
•	sudo pip3 install cherrypy
•	sudo pip3 install RPi.GPIO

This will install python3, pip3 which is the install program for python3 modules, cherrypy  and RPi.GPIO that allows controlling th GPIO-pins on the raspberry.  (if some of the installations are already there you will get informed when trying to install)

The HTML file will be explained in class

To test ……
•	On the raspberry do 
o	python3 cherrytest.py
•	This will make the raspberry listen for incoming connection on port 8080

Now open a browser on your labtop computer and browse    ipnumber:8080..  
  
You should see a webpage with two buttons

Pressing the buttons ..  ON  and   OFF  should 
•	control GPIO-pin number 7
•	on the raspberry you should see logmessages everytime you press ON/OFF.

Assignment
Attach another  LED on another GPIO pin and see that this is controllable also.


To test the buttongrid.html 
  either change the refference in cherrytest.py
or
  rename the buttongrid.html to htmlfile.html
