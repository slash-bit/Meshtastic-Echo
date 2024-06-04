# Meshtastic-Echo
This Meshtastic firmware is a development of Echo Module. It is intended for mobile use and allows to discover hidden nodes (that do not broadcast often) by listening to re-broadcast of own position packets.
When on the move the node broadcasts position pings and listens for rebroadcasts from other nodes. When rebroadcasts heard the signal RSSI and SNR is noted and displayed on the device screen and a phone App. 
As an exmaple screen on T-Echo looks like this. One line represents each echo rebroacast showing rssi and time it was received.
In addition in the  App a new node wil apear per rebrodcast , which will also show RSSI and SNR of the received signal , plus the coordinates where the signal was received.
It can then be analised later by looking at the phone App map.
Caveat. Currently the Nodename is shown as a Unknown Name . The plan is to make the Long name showng the time and signal strength and the Short name showing the RSSI level , so it will be easy to see on the map what the signal was and where.

 
