## Readings 3: Network Segmentation

Below you will find reading material and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

CIDR Block Notation Explained in 2 Minutes

## What is CIDR notation? a CIDR block?
A CIDR notation is a way of representing a range of IP addresses. By using CIDR notations we maximize the utilization of IP addresses by moving away from the classful IP scheme.

## How many octets are found in an IPv4 address?
Four 8 bit octets separated by dots to make them easier to read by humans.

## Setting binary aside and using the decimal system, what is the range of numbers found in an octet? 
0-255 for 256 numbers since 0 has a value to computers.

## What does the final digit after the “/” represent in an IPv4 address?
The slash has a number behind it that represents the number of bits turned on in a subnet. It represents the network portion of the subnet with 1’s added up while the 0’s represent the host portion.

## How many IP addresses are in the CIDR block 10.0.0.0/24?
A /24 has 24 bits of 32 turned on for 8 you then take 2 to the 8th power for 256. You then take away the broadcast and network IP’s for 254 usable IP addresses.

## What Is Network Segmentation and Why Does It Matter?
Network segmentation is the isolation of networks to insulate the different segments from each other like compartmentalization kinda.

## In your own words, describe network segmentation.
Networks are joined physically in many ways, segmentation is how we separate them logically for security and other reasons. 

## Network segmentation isn’t important as long as the network is using a well configured firewall. 

Do you agree? Why or why not?
No, for the most part a fire wall is a filter for incoming and outgoing traffic. Segmentation can help security in many other ways like separating different kinds of traffic through VLANs; microsegmentation is pretty big in security and cybersecurity.

## What is a screened subnet?
A screened subnet, also known as a DMZ (demilitarized zone), is a network segment that is isolated from both the public internet and the internal corporate network. It is typically used to host servers that need to be accessible to external users, such as web servers and email servers. By isolating these servers, the DMZ helps to protect the internal network from cyberattacks.

## Cameras, ID card scanners, locked doors and biometrics are just a few examples of what type of security? 
The layered approach to physical security. Making sure individuals only have access to the proper systems, information and areas and authenticated before given the proper level of access.

## References:

[CompTIA](https://www.comptia.org/blog/security-awareness-training-network-segmentation) 

[Prof Messer](https://www.professormesser.com/network-plus/n10-008/n10-008-video/vlans-and-trunking-n10-008/) 

[Prof Messer](https://www.professormesser.com/network-plus/n10-008/n10-008-video/classful-subnetting-n10-008/) 

[Google Bard](https://bard.google.com/chat/889fe46c8efdcb09) 
