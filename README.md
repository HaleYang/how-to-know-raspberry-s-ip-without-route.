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

Once you know your pi's ip , you can connect it and display on your PC's screen.Perhaps you need download putty or Xshell.


所需的东西：笔记本电脑、网线、树莓派。

步骤：
1、先将你的笔记本联网（连接WLAN），然后用网线连接你的笔记本和树莓派；\n
2、打开网络共享中心找到你所连接的WLAN（不是你连接的树莓派接口），点击设置网络属性，在共享这一栏选择一个专用网络连接（这个作用网络连接即为你的树莓派）；\n
3、选择后点击确定树莓派所接入的网络允许共享，在命令行cmd中输入arp -a；\n
4、在树莓派系统盘中写入ssh命名的文件；\n
5、查看多的接口，树莓派一般是192.168开头，在树莓派的物理接口下，一般是动态ip，且是第一个，若不行在试用其他ip地址；\n
6、找到ip后输入至ssh通信连接软件。
