# Node-RED Example

This is a node-red flow for controlling couple of a KMTronic TCP Web Switch including and a Temperature Monitor

Node-Red https://nodered.org/

This flow requires from the Pallet Manager

Dashboard - node-red-dashboard


<img src="https://github.com/kmtronic-ltd/node-red-example/blob/master/Node-RED%20(6).png" width="800" height="438">


<img src="https://github.com/kmtronic-ltd/node-red-example/blob/master/Node-RED%20(7).png" width="800" height="378">

Every http request will have to be edited with the
IP address of your KMTronic WEB Switch (not UDP
switch).  Change 192.168.110.206 ,212 and 202 to the address of you KMTronic board/boards.
If you don't have more than one board you can remove the rest.

Switch 6 is a PTT switch and by pressing it, it will
toggle on Switch 6 for 1 second - you can delete
it if not required

In the initial setup of your KMtronic switch turn 
off any authetication.  

<img src="https://github.com/kmtronic-ltd/node-red-example/blob/master/Node-RED%20(1).jpg" width="250" height="514">

<img src="https://github.com/kmtronic-ltd/node-red-example/blob/master/Node-RED%20(2).jpg" width="250" height="514">

<img src="https://github.com/kmtronic-ltd/node-red-example/blob/master/Node-RED%20(3).jpg" width="250" height="514">

<img src="https://github.com/kmtronic-ltd/node-red-example/blob/master/Node-RED%20(4).jpg" width="250" height="514">

<img src="https://github.com/kmtronic-ltd/node-red-example/blob/master/Node-RED%20(5).png" width="800" height="503">


# Requirements for USB Relay Boards: 

Serial Port - node-red-node-serialport

<img src="https://github.com/kmtronic-ltd/node-red-example/blob/master/Serial-Palette.png" width="704" height="210">

Find the serial board in Linux from you terminal: 

<img src="https://github.com/kmtronic-ltd/node-red-example/blob/master/ttyUSB.png" width="664" height="255">

Serial Port Config

<img src="https://github.com/kmtronic-ltd/node-red-example/blob/master/SerialPort-config.png" width="513" height="347">

<img src="https://github.com/kmtronic-ltd/node-red-example/blob/master/USB8REL.png" width="508" height="558">
Credits 
Michael Walker
