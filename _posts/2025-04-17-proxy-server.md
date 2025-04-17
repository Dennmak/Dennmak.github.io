---
layout: post
title: Proxy Server
subtitle: Setup and Configuration
cover-img: assets/img/Blue Background -Network Topology.jpg
thumbnail-img: assets/img/Proxy Share and Thumbnail - Proxy.jpg
share-img: assets/img/Proxy Share and Thumbnail - Proxy.jpg
tags: [Networking]
author: Dennis Maksimov
---

## It's Proxy Time

What is a proxy server? You've come to the right place! A proxy server has a special purpose, it acts as an intermediary between a device and the internet. Why is this important? It allows for more privacy, security, and can even allow one to bypass geographical restrictions such as national firewalls.

Today we're going to be using Cisco Packet Tracer to create a proxy server and you can follow along to see how I do it. Ready? Let's go!

![Cat](/assets/img/Cat Start - Proxy.jpg)

## The Journey Begins

Once you open Cisco Packet Tracer you'll have a fresh blank canvas. We're going to start off by placing PC's on our canvas.

Head to the lower left corner and select **end devices** and select **PC**. We're going to place **four** computers on our canvas.

![Screenshot 1](/assets/img/Screenshot 1 - Proxy.jpg)

Now we have four computers! Aren't they beautiful?

![Screenshot 2](/assets/img/Screenshot 2 - Proxy.jpg)

Next, we're going to place down two switches.

Head to **network devices** and then to the **switch tab**. We're going to select the **2960** and place two of them on our screen.

![Screenshot 3](/assets/img/Screenshot 3 - Proxy.jpg)

Now we have 2 switches and 4 computers, our ecosystem is growing!

![Screenshot 4](/assets/img/Screenshot 4 - Proxy.jpg)

Next, we're going to add a router to keep our other devices company.

Go to the **network devices** tab and select **router**. We're going to be using the **4331** router today.

![Screenshot 5](/assets/img/Screenshot 5 - Proxy.jpg)

Our network is growing! Isn't it great?

![Screenshot 6](/assets/img/Screenshot 6 - Proxy.jpg)

Now we're going to add two servers to the network. Head to the **end devices** tab and select **server**. We're going to place two of them on the screen.

![Screenshot 7](/assets/img/Screenshot 7 - Proxy.jpg)

Now our network is finally complete with our servers set up!

![Screenshot 8](/assets/img/Screenshot 8 - Proxy.jpg)

## It's Time to Connect

We're going to start connecting our hardware together and begin configuring it.

Head to the connections tab and select **copper cross-over cable**.

![Screenshot 9](/assets/img/Screenshot 9 - Proxy.jpg)

Select the first switch and pick the port **fast ethernet 0/1** and attach it to our router. When selecting the router you'll see **giga ethernet 0/0/0**, connect to that.

![Screenshot 10](/assets/img/Screenshot 10 - Proxy.jpg)

![Screenshot 11](/assets/img/Screenshot 11 - Proxy.jpg)

Now head to the other switch and repeat the process with **copper cross-over cable**. Select the other switch and pick **fast ethernet 0/1**. Attach it to the router in the port **giga ethernet 0/0/1**.

![Screenshot 12](/assets/img/Screenshot 12 - Proxy.jpg)

![Screenshot 13](/assets/img/Screenshot 13 - Proxy.jpg)

At the end, you should see the switches connected to the router!

![Screenshot 14](/assets/img/Screenshot 14 - Proxy.jpg)

Next we're going to be connecting our switches to the servers.

Go to the connections tab and select **copper cross-over cable**.

![Screenshot 15](/assets/img/Screenshot 15 - Proxy.jpg)

Select the first switch and select **fast ethernet 0/2**. You'll then connect it to the first server in the port **fast ethernet 0**.

![Screenshot 16](/assets/img/Screenshot 16 - Proxy.jpg)

Repeat that process with the other server with the same **copper cross-over cable**.

Now we should have our switches connected to our servers with cables.

![Screenshot 18](/assets/img/Screenshot 18 - Proxy.jpg)

Now, we're going to connect our PC end devices to our switches.

Head to the connections tab and select **copper cross-over cable**. 

![Screenshot 19](/assets/img/Screenshot 19 - Proxy.jpg)

Select the first computer while using the cable and a port called **fast ethernet 0** should pop up. Select it.

![Screenshot 20](/assets/img/Screenshot 20 - Proxy.jpg)

Attach it to the first switch and you should see a port called **fast ethernet 0/3**.

![Screenshot 21](/assets/img/Screenshot 21 - Proxy.jpg)

Repeat this process for the 2nd PC and attach it to the first switch.

After that, head over to the second switch and connect both computers to the second switch.

At the end of your process, it should look like this. Do you see how the switches are connected to the PC's? 

![Screenshot 22](/assets/img/Screenshot 22 - Proxy.jpg)








