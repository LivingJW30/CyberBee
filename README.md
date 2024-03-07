# CyberBee
Cyber challenge for the February 23rd Hack@UCF general body meeting. Ping @Jack.py on Discord with the flag. 

Flag format: hack@ucf{*flag-name*}

## Background
Buzzing Wings Aerial Pollinators Platform (bWAPP) is in a bit of a buzz right now. Their brand new web based blog feature was hacked! As the new cyber intern, and the only cyber specialist in the company, it is your time to shine. 

Your supervisor needs you to take a look at a packet capture file taken during the attack to find out what happened and what the bad actor stole. There is rumors the bad actor may have breached the CEOs personal information. Can you find what the bad actor stole from the bWAPP CEO before he gets back from vacation?

## Guided questions
1. What is the login name of the user who attacked?
2. What kind of attack was used?
3. What is the login name of the CEO?
4. What did the bad actor steal

Note: You only need to submit the flag but hopefully these questions can help you work your way through the challenge.

## Resources
+ [Wireshark](https://www.wireshark.org/) - recommended for analyzing the pcap
+ [bWAPP](http://www.itsecgames.com/) - actually stands for Buggy Web Application and is a great resource for practicing your web exploits LEGALLY!

## Write up
*will be updated at challenge end*
<!--
+ Initial setup
 - Download a network protocol analyzer as we must analyze this packet capute file (.pcap). I am a fan of Wireshark as it provides a nice GUI. But if you are a command line wizard tshark and tcpdump are good command line tools.
 
 - On a network, information is sent via packets. Packets have a header, which includes the source, destination, and other important information, and a payload, which has the data being sent. All of this is stored as binary making it almost impossible for us to read on our own. That is where our network protocol analyzer comes in. Wireshark, or whatever else you use, allows you to not only see the orginal binary but also converts and categorizes the infromation back to being human readable. This can help us with our challenge!

 + SO much information...where do I start?
  - Once you open the pcap file you are hit with 1571 packets! This can be overwhelming. Let's start by thining down the amount of packets we have to analyze. A lot of these packets are just junk that we either can't read or is unimportant to our cause. So let's find out which ones those are.
  - Wireshark has a cool feature in the statistics bar that will show you the number and type of protocols that were captured.


-->
