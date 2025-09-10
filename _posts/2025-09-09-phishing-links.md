---
layout: post
title: Phishing Links
subtitle: How to Spot Them and Deal With Them
cover-img: assets/img/Water Background - Phishing Links.png
thumbnail-img: assets/img/Share and Thumb - Phishing Links.png
share-img: assets/img/Share and Thumb - Phishing Links.png
tags: [Cybersecurity, Tutorial]
author: Dennis Maksimov
---

## What is Phishing?

What is phishing, you say? Phishing is when malicious actors impersonate others to steal sensitive information from other people using malicious links. They use delivery methods and platforms such as emails, text messages, and social media. The primary method they use is by sending emails to other users, and in these emails, there are malicious links. They cast out bait and hope that someones take a bite, and that bite could be you! That's why it's called phishing because it's basically fishing in the digital world!

These links are usually hidden in buttons or other places where you don't expect them. These links lead to malicious websites that collect your information, such as usernames and passwords. The attackers are then able to use these credentials to log into systems that you may have access to or accounts that you use. Now you have a compromised account, and your information is at risk! It's a huge headache to clean up.

![Fishing](/assets/img/Fishing - Phishing Links.png)

## Why is this Important?

Bad actors use phishing as a means of getting access to systems and getting a hold of confidential information. A user can send out 1,000 malicious emails, and 999 people could spot it, but it takes only 1 person to make a mistake. Those mistakes can be costly and cause great harm, and sometimes you don't even know that the link you clicked was malicious. Your credit card, social security, bank account information, and other information can be accessed just because you clicked a link! It's a big deal, and it greatly emphasises why you should pay attention when you're surfing the internet.

## Social What?

Another topic that goes hand in hand with phishing is social engineering. Social engineering is a method of social hacking that includes manipulating individuals in order for them to do something that one desires without them being aware. Examples of this include convincing someone to reveal confidential information, convincing them to change a password, or creating a sense of urgency that forces a person to act on their emotions. It also consists of gaining a person's trust and taking advantage of that trust so that they perform a task for you. It's one of the main tools in a hacker's tool belt, and it's very effective.

## What's the Plan Today?

Today, we're going to be analyzing a phishing email that had malicious intent. We're going to be looking at the sender, titles, email structure, and how to check if the link or payload in the email is malicious. Hopefully, this will equip you to spot these pesky emails and keep you and others safe from these bad actors.

![Fishing Start](/assets/img/Fishing Start - Phishing Links.png)

## The Tools of the Trade

The tool we're going to be using today is VirusTotal. It's a free tool that allows you to scan a URL or file, and it'll report back whether it's malicious or not. It scans the said file or URL with security vendors and the community, and you get a response when it's done. This is basically what OSINT (open source intelligence) is all about. OSINT is the gathering and analysis of public information and gaining intelligence out of it. It's a huge blessing because it's not locked behind a paywall, and you can do it straight from your home. 

There are many other tools that you can use, such as DNSlytics, message header analyzer, and URLScan. These can be used to analyze the IP of a sender email or website, analyze headers, and scan URLs to see if they're malicious. However, for the sake of simplicity, we're just going to be using Virustotal today. 

![Virus Total](/assets/img/Virustotal - Phishing Links.png)

## The Scene of the Crime

I present to you in all of its infamous glory, a phishing email. I dug it up in my spam folder, and it's looking pretty bad from over here. Someone needs to take out the trash! Yet before we continue to insult the email and its sender, we're going to have to analyze it to make sure that it's actually a phishing email.

![Phishing Email](/assets/img/Phishing Alert - Phishing Links.png)

## Let's Start Unpacking

I'm going to list a series of steps that I use in analyzing this email, and hopefully, you can create a similar method in order to perform your own analysis.

1) The Title: "Final Notice: Your photos and videos will be deleted – take action"

The title states that it's a final notice and that if you don't act, your photos and videos will be deleted with a few warning emojis as a cherry on top. This sense of urgency creates a sense of fear and manipulates you into acting because you're worried that your content will be deleted. This is a case of social engineering and is a method used by hackers in order to manipulate you into performing an action, which in this case is clicking their link. A few questions to ask yourself are, "Is it too good to be true?" and "What are they trying to get me to do?". There's always a catch and purpose to these emails. Once you spot these patterns, it's easy to put it all together.

![Urgency](/assets/img/Urgency Title - Phishing Links.png)

2) The Sender: hngnnrrztsyferqwkzvt

The next thing that we're going to look at is the sender. Questions such as "Does this look like a legitimate sender?" should come to mind. Normally, we'd run it through the email domain through URLscan or DNSlytics, but in this case, we're going to observe and gauge it by eye. It looks to be an abnormally long sender address with a "net" top-level domain and also a "lat" domain. Something smells phishy over here! It doesn't add up because it's not like a normal domain, such as Google or Yahoo. It seems that they're not English speakers either, and this isn't a US or English native domain. 

![The Sender](/assets/img/Sender - Phishing Links.png)
 













