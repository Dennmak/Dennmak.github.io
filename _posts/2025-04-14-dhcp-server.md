---
layout: post
title: DHCP Server
subtitle: Setup and Configuration
cover-img: assets/img/Blue Background -Network Topology.jpg
thumbnail-img: assets/img/Share - DHCP Server.jpg
share-img: assets/img/Share - DHCP Server.jpg
tags: [Networking, Tutorial]
author: Dennis Maksimov
---

## What is DHCP?

There are many acronyms in the tech world and today's acronym will be DHCP or Dynamic Host Configuration Protocol. This is a protocol that eliminates the need for manual assignment of IP addresses to devices and allows for automatic IP assigning to devices. It makes life a lot easier and reduces congestion in networks. Who doesn't love automation?

![Intersection](/assets/img/Intersection - DHCP Server.jpg)

## How to Set Up DHCP

Today we're going to be using Cisco Packet Tracer to set up and configure DHCP in a router which will be the focal point for communication between switches and devices. This will be a digital representation which will mimick a real life scenario with actual hardware. Ready? Let's go!

![Lemur](/assets/img/Lemur - Guest Network.jpg)

## The Show Begins

We'll start off with opening Cisco Packet Tracer. On start up you'll have a blank canvas with nothing on it.

In the bottom left corner select **Network Devices**, after that select **router** and then the **2911** router. Drag this router onto your canvas in any spot that you desire!

![Screenshot 1](/assets/img/Screenshot 1 - DHCP Server.png)

Next, select **Network Devices** and then go to the **switch** tab. You will select the **2960** device and drag two of them onto your canvas.

![Screenshot 2](/assets/img/Screenshot 2 - DHCP Server.png)

You'll now have two switches and a router on your canvas! Isn't it beautiful?

![Screenshot 3](/assets/img/Screenshot 3 - DHCP Server.png)

Next, select the **end devices** tab and select the **PC**. We're going to place 6 of these PC's onto our canvas.

![Screenshot 4](/assets/img/Screenshot 4 - DHCP Server.png)

## It's Time to Connect

Now, we're going to connect our router to our switches.

Head to the **connections** tab and select **copper straight-through**. 

![Screenshot 5](/assets/img/Screenshot 5 - DHCP Server.png)

Select your router and select the **gigabit ethernet 0/0** connection.

![Screenshot 6](/assets/img/Screenshot 6 - DHCP Server.png)

Now, go to your 1st switch and select **Fast Ethernet 0/1**.

![Screenshot 7](/assets/img/Screenshot 7 - DHCP Server.png)

Repeat these steps for the 2nd switch.

Now you should have both switches connected to the router by cable.

![Screenshot 8](/assets/img/Screenshot 8 - DHCP Server.png)

Now, go to the connections tab in bottom left corner and select **automatically choose connection**. This will automatically pick the cable needed. Now, connect your switches to your PC devices! 

If we want to do it manually, we'll use copper straight-through for this process but Cisco Packet Tracer automates a few things to make the process less tedious. 

![Screenshot 9](/assets/img/Screenshot 9 - DHCP Server.png)

Now we have our network with a router, two switches, and 6 PC's! Isn't it just a beautiful sight?

![Screenshot 10](/assets/img/Screenshot 10 - DHCP Server.png)

## The Fun Begins

Things may get a little complicated here so pay attention! 

Head to the **CLI** tab in your router.

![Screenshot 11](/assets/img/Screenshot 11 - DHCP Server.png)

Copy down the information from the screenshot into your terminal. It may or may not vary based on the router that you chose. This will configure your router and start the process for setting up DHCP.

![Screenshot 12](/assets/img/Screenshot 12 - DHCP Server.png)

## The First Switch

Now we'll configure the first switch and enable DHCP. Copy the information from the screenshot into your own terminal.

![Screenshot 13](/assets/img/Screenshot 13 - DHCP Server.png)

## The Second Switch

Next, we'll follow the same process but do it for the second switch. Copy the information from the screenshot and input it into your terminal.

![Screenshot 14](/assets/img/Screenshot 14 - DHCP Server.png)

## The DNS Conundrum

If you desire to change your DNS for your gateway on our switches, follow the next steps. I'm switching mine to 8.8.8.8 and it'll show when we change our devices to DHCP.

![Screenshot 15](/assets/img/Screenshot 15 - DHCP Server.png)

We'll do it to the second switch as well.

![Screenshot 16](/assets/img/Screenshot 16 - DHCP Server.png)

## The Desktop

Now we'll head to your first PC and head to the **desktop** tab. You'll then select **IP Configuration** tab.

![Screenshot 17](/assets/img/Screenshot 17 - DHCP Server.png)

Select the **DCHP tab** and the information there should refresh after a few seconds.

![Screenshot 18](/assets/img/Screenshot 18 - DHCP Server.png)

Repeat this process for the rest of your PC's and you should she DHCP enabled on all of them! 

## It is Finished!

Congratulations! You have now set up and configured DHCP for your network! Devices that connect to your network will now have their IP automatically assigned! This process may vary if you have different hardware at home but the concept remains the same. Great job and thanks for sticking with me!

![Screenshot 19](/assets/img/Screenshot 19 - DHCP Server.png)
