---
layout: post
title: Network Topology
subtitle: Examples of Networks and How They Work
cover-img: assets/img/Blue Background -Network Topology.jpg
thumbnail-img: assets/img/Network thumbnail - Network Topology.jpg
share-img: assets/img/Network thumbnail - Network Topology.jpg
tags: [Networking]
author: Dennis Maksimov
---
## What is Network Topology?

Have you ever wondered what network topology is? Well you're in the right place! Network topology is the physical and logical portrayal of a network. It means it's basically a map of what a network looks like and it shows all the devices that is in it and potentially the data flows through it. It's similar to a spider web that's interconnected with many devices on one network. 

I'll be showing various network set ups and examples that may help you understand with the hopes that you'll be able to create your own networks in the future. Get ready, let's go!

(P.S I used Cisco Packet Tracer as a simulation tool, so if you're curious in dabbling in it yourself, check it out.)

![Spider Web](assets/img/Spiderweb - Network Topology.jpg)

## Routers and Switches

In this model I used a combination of a router and switches. I started off with a 2911 router and two 2960-24TT switches. I then added four PC's to the network to act as end devices. 

I connected the two switches to the router using copper straight-through cables to create a connection. I then used copper straight-through cable to connect the four PC's to the switches.

(I did not fully configure this network. It was meant to be an example and act as a framework or blueprint.)

![Screenshot 1](assets/img/Screenshot 1 - Network Topology.png)

## The File Server

For this next network, my goal was to implement a file server.

I started off with two PC's as end devices which I then connected to a 2960-24TT switch with copper straight-through cable.

I then connected the switch to a ISR4331 router with more copper straight-through cable. I then connected the router to a Server-PT unit with copper cross-over cable to get it all together. This would support a file server and my intention was to create a network specifically for this purpose.

(I did not fully configure this network. It was meant to be an example and act as a framework or blueprint.)

![Screenshot 2](assets/img/Screenshot 2 - Network Topology.png)

