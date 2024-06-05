# Meshtastic-Echo
The **Meshtastic-Echo** firmware is a development of the Echo Module. It is designed for mobile use and allows you to discover hidden nodes (those that do not broadcast often) by listening to re-broadcasts of your own position packets.

When you’re on the move, the node broadcasts position pings and listens for rebroadcasts from other nodes. When rebroadcasts are heard, the signal’s Received Signal Strength Indicator (RSSI) and Signal-to-Noise Ratio (SNR) are noted and displayed on the device screen and a phone app.

As an example, the screen on the T-Echo device looks like this:

![image](https://github.com/slash-bit/Meshtastic-Echo/assets/77391720/a3f7761e-7e7c-473b-89c8-0e48a0746e08)

Each “Echo” represents a rebroadcast from another node, showing the RSSI and the time it was received.

When using the app, a new node will appear per rebroadcast. This node will also display the RSSI and SNR of the received signal, along with the coordinates where the signal was received:

![image](https://github.com/slash-bit/Meshtastic-Echo/blob/main/images/Screenshot_20240603-084325_Meshtastic.jpg)

You can then analyze this information later by looking at the phone app map.

Caveat: Currently, the nodename is shown as “Unknown Name.” The plan is to make the long name show the time and signal strength, while the short name will indicate the RSSI level. This way, it will be easy to see on the map what the signal was and where it came from:

 ![image](https://github.com/slash-bit/Meshtastic-Echo/blob/main/images/Screenshot_20240603-084342_Meshtastic.jpg)

