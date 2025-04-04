---
layout: post
title: Setting Up A Wireless Network
subtitle: How to Set Up A Guest Network
cover-img: assets/img/Blue Background - Guest Network.jpg
thumbnail-img: assets/img/Modem Router Thumbnail - Guest Network.jpg
share-img: assets/img/Modem Router Thumbnail - Guest Network.jpg
tags: [Networking, Tutorial]
author: Dennis Maksimov
---
## How Do I Set Up a Guest Network?

How you ever wondered how to set up a guest network? Do you want to keep others away from your trinkets? I'm going to be using Cisco Packet Tracer today to simulate how one would set up a guest network on their router. 

It seems complicated but at the end of this tutorial you'll have an idea of how it works and be able to make your own! Visitors to your home will be so excited to have wifi access! Woohoo! Let's get started!

![Lemur](/assets/img/Lemur - Guest Network.jpg)

## Let's Get Started!

When you open up Cisco Packet Tracer for the first time you'll be greeted by a blank canvas without any models on it. This is where we'll be starting our project and making our guest network.

![Screenshot 1](/assets/img/Screenshot 1 - Guest Network.png)

Select the **Wireless Devices** tab and a line of devices should pop up.

![Screenshot 2](/assets/img/Screenshot 2 - Guest Network.png)

Find **Home Router** and drag and place it on your blank canvas and a router should appear!

![Screenshot 3](/assets/img/Screenshot 3 - Guest Network.png)

Next we'll go to the **End Devices** tab and we'll click on **Laptop** and place 2 of them on the canvas.

![Screenshot 4](/assets/img/Screenshot 4 - Guest Network.png)

After you placed them on the canvas, you'll see a router and two laptops on your screen.

![Screenshot 5](/assets/img/Screenshot 5 - Guest Network.png)

## The Awesome Router

Double click your router on the canvas and you'll see a menu pop. Click config and you should see the **global settings** menu pop up with a menu stating **Display Name**. Overall, this helps with organization and is optional but in my case I renamed it as **The Awesome Router**. 

![Screenshot 6](/assets/img/Screenshot 6 - Guest Network.png)

Exit out and we'll change the device names of both laptops to **The Awesome Laptop 1** and **The Awesome Laptop 2**. Yes, it is very original, I know. 

![Screenshot 7](/assets/img/Screenshot 7 - Guest Network.png)

The same process will be done for the second laptop.

![Screenshot 8](/assets/img/Screenshot 8 - Guest Network.png)

## Name Day

Today is the day that we'll give our router a true name. A name it will never forget. Double click your router and head to the config tab. Go to the wireless 2.4ghz option and a menu should pop up on the right. You will see **SSID** this is the place where we shall give our router its true name which will be seen by all. I have decided to name our router **The Awesome Router** because it needs some recognition.

![Screenshot 9](/assets/img/Screenshot 9 - Guest Network.png)

We shall repeat this process for our guest network. On the left side you'll see a Wireless 2.4ghz option. Select that and you'll see the same SSID option to rename your guest network. In this case I decided to go with the most original name **Guest**.

![Screenshot 11](/assets/img/Screenshot 11 - Guest Network.png)

## Ramp up the Security!

We'll implement a password on the network now so that your trinkets will be safe. On the same window that's open, select **WPA2-PSK** and you'll see the option to select a passcode next to it. Type in a password that you desire and this will be what you'll use to access your wifi network. 

I used *Hello12345* as my password for demonstrative purposes. However, for official use please use a password with capitals, numbers, and lowercase letters to make it as secure and complicated as possible. Password security is important and the last thing you want is an unauthorized user downloading 45,000 illegal movies on your connection. 

![Screenshot 10](/assets/img/Screenshot 10 - Guest Network.png)

We'll do the same thing for our guest network and we'll head to **wireless guest 2.4ghz**. Head to **WPA2-PSK** and you'll see the same passcode option next to it. Put in a password of your choosing, in my case I did *Hello12345*.

![Screenshot 12](/assets/img/SCreenshot 12 - Guest Network.png)

## The GUI

Next we'll head to the GUI tab of the router and this is where the fun begins! It's GUI time!

Head to the **Wireless** and then **basic wireless settings** tab underneath it. This will show all the channels that are currently being shown.

![Screenshot 13](/assets/img/SCreenshot 13 - Guest Network.png)

We want to reduce clutter and have only our main network and guest network enabled, so disable both 5 ghz 1 and 5 ghz 2. This will disable both channels so they won't show up in active networks in the wifi list when we attempt to connect to them with our laptops.

![Screenshot 14](/assets/img/SCreenshot 14 - Guest Network.png)

Now, head to the guest network tab and select **enable guest profile**. This will activate the guest network and allow it to be shown on the active wifi list!

![Screenshot 15](/assets/img/SCreenshot 15 - Guest Network.png)

Now, after you've done all this, don't forget the most important step! Scroll down and select **save settings**. Everything that you have just done will be reverted if you don't save.

![Screenshot 16](/assets/img/SCreenshot 16 - Guest Network.png)

## It's Hardware Time

Now it's time to mess with some hardware and make sure that our laptops can actually connect to our router.

Double click on the first laptop and head to the **physical** tab to see a physical representation of your laptop and a long list of modules on the side.

![Screenshot 17](/assets/img/SCreenshot 17 - Guest Network.png)








