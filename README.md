# how-to-know-raspberry-s-ip-without-route.

when you buy a raspberry,the first thing that you should know is your raspberry's ip ,so you can connect it.
i will introduce a way that you can get your pi's ip if there isn't route.

the things that you should prepare:
PC(it needs connect to a wlan);
one internet line;
your pi;

first step:
connect your PC to the pi with the internet line ,make sure your PC connect to the wlan

open the Network and Sharing Center and change the properties of the wlan that you connected ,make it can share the internet to
other hardware that is connected to your computer

second step:
write a document named ssh (remmeber to remove the postfix ".txt") and save at the os's disc;
open cmd and input the command:'arp -a';
the first ip under the new interface is your pi's ip generally;it's usually dynamic;

Once you know your pi's ip , you can connect it and display on your PC's screen.Perhaps you need download putty.
