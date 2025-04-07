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

![Spider Web](/assets/img/Spiderweb - Network Topology.jpg)

## Routers and Switches

In this model I used a combination of a router and switches. I started off with a 2911 router and two 2960-24TT switches. I then added four PC's to the network to act as end devices. 

I connected the two switches to the router using copper straight-through cables to create a connection. I then used copper straight-through cable to connect the four PC's to the switches.

(I did not fully configure this network. It was meant to be an example and act as a framework or blueprint.)

![Screenshot 1](/assets/img/Screenshot 1 - Network Topology.png)

## The File Server

For this next network, my goal was to implement a file server.

I started off with two PC's as end devices which I then connected to a 2960-24TT switch with copper straight-through cable.

I then connected the switch to a ISR4331 router with more copper straight-through cable. I then connected the router to a Server-PT unit with copper cross-over cable to get it all together. This would support a file server and my intention was to create a network specifically for this purpose.

(I did not fully configure this network. It was meant to be an example and act as a framework or blueprint.)

![Screenshot 2](/assets/img/Screenshot 2 - Network Topology.png)

## The Access Point

My goal for this network was to incorporate a wireless access point and connect devices to it.

I started off with three cell phones to act as end devices and connected them to an Access Point-PT unit. I then connected the access point to a 2960-24TT switch. I then placed three more laptops to act as more end devices. 

My purpose for this was to see how I could support multiple devices on one wireless access point and to see if it could handle it.
(I did not fully configure this network. It was meant to be an example and act as a framework or blueprint.)

![Screenshot 3](/assets/img/Screenshot 3 - Network Topology.png)

## The Firewall Cometh

For this next network, I wanted to try and implement a firewall to secure the network. This network was a bit more simple and I wanted to set up a basic framework that would support it.

I started off with two PC's as end devices which would connect to a 2960-24TT switch using copper straight-through cable.

I then connected the 2960-24TT switch to a 5506-X firewall unit with copper straight-through cable. 

(I did not fully configure this network. It was meant to be an example and act as a framework or blueprint.)

![Screenshot 4](/assets/img/Screenshot 4 - Network Topology.png)

## No Place Like Home

I decided to create a very simple home network with one end device and a router.

I connected a home router with Cat 5/6 to a PC end device to simulate a simple network. This is basically the barebones framework for most households in America. You could always add a router with more connection capability and ports to support more traffic and devices such as cellphones, laptops, and printers, but this would be where you would start off at.

(I did not fully configure this network. It was meant to be an example and act as a framework or blueprint.)

![Screenshot 5](/assets/img/Screenshot 5 - Network Topology.png)

## It's Fiber Time

I decided to simulate a simple fiber connection using an end device PC and a router which supports fiber. I connected both with a fiber cable and voilah, let there be light.

(I did not fully configure this network. It was meant to be an example and act as a framework or blueprint.)

![Screenshot 6](/assets/img/Screenshot 6 - Network Topology.png)

## It is Finished!

I provided a examples of various types of networks and how you can configure them. There are many networks that support various purposes and each one has to be specialized for a specific use. If you're curious about learning more, install Cisco Packet Tracer and begin dabbling to become a true network architect! I'm still a beginner so these are mostly frameworks and starting points for more complicated networks. Good luck on your journey!

![Ball](/assets/img/Ball picture - Network Topology.jpg)
