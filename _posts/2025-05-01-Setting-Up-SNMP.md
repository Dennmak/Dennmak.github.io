---
layout: post
title: Setting Up SNMP
subtitle: How to Set up SNMP
cover-img: assets/img/Blue Background - Setting Up SNMP.jpg
thumbnail-img: assets/img/Network Share and Thumbnail - Setting Up SNMP.jpg
share-img: assets/img/Network Share and Thumbnail - Setting Up SNMP.jpg
tags: [Networking, Tutorial]
author: Dennis Maksimov
---

## What is SNMP?

Have you wondered what SNMP is? Well I have the answer for you! SNMP is a protocol used in networking that allows for monitoring and managing network devices. This allows network administrators or in this case you, to gather diagnosdtic data and other information about their network. It's an efficient way to gather data that can be used for troubleshooting and other tasks.

## Let's Get Started!

Today we're going to set up SNMP in a simple network so you can see how to get started and how it works. We're going to be using Cisco Packet Tracer and it'll be simulating what you can do with actual hardware that you may have at home. Let's go!

![Shark Start](/assets/img/Shark Start - Setting Up SNMP.jpg)

## Network Creation

We're going to get started by setting up a small network. This will consist of 3 PC's, a switch, and a router. Drag these onto your canvas in any format you desire.

![Screenshot 1](/assets/img/Screenshot 1 - Setting Up SNMP.png)

Next we're going to connect our devices together. Head to the connections tab and select **automatically choose connection type**. Connect your router to your switch, and then connect all 3 PC's to your switch.

![Screenshot 2](/assets/img/Screenshot 2 - Setting Up SNMP.png)

After you connected them, it should look similar to this.

![Screenshot 3](/assets/img/Screenshot 3 - Setting Up SNMP.png)

## Configuration Conundrum

Next we're going to configure our devices by assigning IP addresses to them. We're going to assign IP's to our 3 PC's and then to our router. 

First, head to the router and head to the config tab. Select **gigabitethernet 0/0** on the left under interface.

On the right, you'll see port status. Check that box to **on**.

Next go to IPv4 and set the address to **192.168.2.1**.

Set the subnet mask to **255.255.255.0**.

![Screenshot 4](/assets/img/Screenshot 4 - Setting Up SNMP.png)

Next, head to the first PC and go to ip configuration under the desktop tab.

Next go to IPv4 and set the address to **192.168.2.2**.

Set the subnet mask to **255.255.255.0**.

![Screenshot 5](/assets/img/Screenshot 5 - Setting Up SNMP.png)

Now head to the next PC and repeat the process.

Next go to IPv4 and set the address to **192.168.2.3**.

Set the subnet mask to **255.255.255.0**.

![Screenshot 6](/assets/img/Screenshot 6 - Setting Up SNMP.png)

Finally, head to the last PC and repeat it again.

Go to IPv4 and set the address to **192.168.2.4**.

Set the subnet mask to **255.255.255.0**.

![Screenshot 7](/assets/img/Screenshot 7 - Setting Up SNMP.png)


