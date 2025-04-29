---
layout: post
title: Configure a Firewall
subtitle: How to Set up a Basic Firewall
cover-img: assets/img/Paint Background - Configure a Firewall.jpg
thumbnail-img: assets/img/Firewall Thumbnail and Share - Configure a Firewall.jpg
share-img: assets/img/Firewall Thumbnail and Share - Configure a Firewall.jpg
tags: [Networking, Tutorial, Cybersecurity]
author: Dennis Maksimov
---
## How to Set Up a Firewall

Ever wondered how to set up a firewall? Well, I'm going to show you today using Cisco Packet Tracer! What's a firewall you say? No, a firewall isn't a giant wall made out of fire but a security measure in a network that acts as a barrier. It monitors inbound and outbound traffic based on what rules are in place. 

Why's it needed? Well, think of your front door being unlocked and anyone can get in. A firewall is the equivalent of a lock and a security guard making sure that only those who are allowed are able to get in.

Anywho, let's get started and get this basic firewall up and running!

![Happy Dolphin](assets/img/Happy Dolphin - Configure a Firewall.jpg)

## The Basic Layout

We're going to get started in Cisco Packet Tracer and we're going to place 1 PC, 1 server, and 1 switch.

![Screenshot 1](assets/img/Screenshot 1 - Configure a Firewall.png)

Next, we're going to connect our devices together. Head to the connections tab and select **automatically choose connection type**.

![Screenshot 2](assets/img/Screenshot 2 - Configure a Firewall.png)

 We're then going to connect the server to the switch, and the switch to the PC.

![Screenshot 3](assets/img/Screenshot 3 - Configure a Firewall.png)

## Time to Configure

We're then going to input IP addresses into our devices so they can communicate with one another.

First, head into your server and then go to desktop, and then IP configuration.

Input **192.168.0.1** into the Ipv4 tab and **255.255.255.0** into the subnet mask tab.

![Screenshot 4](assets/img/Screenshot 4 - Configure a Firewall.png)

Now, head into your PC, desktop, and then the IP configuration tab.

Input **192.168.0.2** into the Ipv4 tab and **255.255.255.0** into the subnet mask tab. 

![Screenshot 5](assets/img/Screenshot 5 - Configure a Firewall.png)

## Time to Test

Now we're going to ping one of our IP addresses to see if they're up and accessable. This is before we set up our firewall. Head into your PC, select the command prompt, and type **ping 192.168.0.1**. This will ping the IP address and show that it's reachable and list a few statistics with it.

![Screenshot 6](assets/img/Screenshot 6 - Configure a Firewall.png)







