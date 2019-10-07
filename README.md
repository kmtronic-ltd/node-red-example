# node-red Example

This is a node-red flow for controlling couple of a KMTronic TCP Web Switch including and a Temperature Monitor

Node-Red https://nodered.org/

This flow requires from the Pallet Manager

Dashboard - node-red-dashboard

Every http request will have to be edited with the
IP address of your KMTronic WEB Switch (not UDP
switch).  Change 192.168.110.206 ,212 and 202 to the address of you KMTronic board/boards.
If you don't have more than one board you can remove the rest.

Switch 6 is a PTT switch and by pressing it, it will
toggle on Switch 6 for 1 second - you can delete
it if not required

In the initial setup of your KMtronic switch turn 
off any authetication.  