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

Have you wondered what SNMP is? Well I have the answer for you! SNMP is a protocol used in networking that allows for monitoring and managing network devices. This allows network administrators or in this case you, to gather diagnostic data and other information about their network. It's an efficient way to gather data that can be used for troubleshooting and other tasks.

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

## It's CLI Time

Now we're going to head into our router and check out the CLI tab. This is where we'll start configuring SNMP.

We'll be using two commands today. 

snmp-server community read ro

snmp-server community write rw

Copy over my inputs from the CLI box to know which order to put them in.

![Screenshot 8](/assets/img/Screenshot 8 - Setting Up SNMP.png)

## Time to Browse

Head into your first PC and go to **MiB** browser. 

In the address bar type in **192.168.2.1** and then select the **advanced** box.

![Screenshot 9](/assets/img/Screenshot 9 - Setting Up SNMP.png)

Now in the read community box, type **read** as the password.

In the write community box, type **write** as the password. 

Yes, very original, I know. 

![Screenshot 10](/assets/img/Screenshot 10 - Setting Up SNMP .png)

Now, this might get a little tricky. You'll see a tree on the left with little arrows under it. Keep clicking arrows until you come to a system drop down and you see **.sysName**.

You will see an OID number that popped up in the top right box. Press go!

![Screenshot 11](/assets/img/Screenshot 11 - Setting Up SNMP.png)

Now you'll see a box that says **Get**. Press that box and you'll see a drag down box appear that has **Set** in it. 

Another box should then pop up and you should see data type and in this you'll change it to **OctetString**. 

After that, change the value in the **value box** to whatever you desire. In my case I put R1 for a value that's easy to remember.

![Screenshot 12](/assets/img/Screenshot 12 - Setting Up SNMP.png)

## Time to Check!

Now we're going to open up the CLI tab in our router to see if it worked. In my case it shows R1 which shows that we are successful! Woohoo!

![Screenshot 13](/assets/img/Screenshot 13 - Setting Up SNMP.png)

## It Is Finished!

We have now successfully set up SNMP in our network! This tool gives us the ability to monitor different devices in our network, in this case our router. You can add more devices to monitor if you desire but I decided to keep it simple so I can show an easy and practical option. One can only imagine how complicated it can get if you have hundreds of devices in a network. Anyway, great job and congratulations! Keep exploring and seeing what else you can do with SNMP!

![Shark End](/assets/img/Shark End - Setting Up SNMP.jpg)
