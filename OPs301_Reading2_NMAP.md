## Readings 2: Network scanning with NMAP

Below you will find reading material and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

For Lecture & Lab

## What is a Port Scanner and How Does it Work?

A port scanner is a network security tool that scans a range of IP addresses and ports to identify which ports are open and listening for incoming connections. This information can be used to identify potential vulnerabilities in a network, such as open ports that could be exploited by attackers.
Port scanners work by sending packets to each port on a target IP address. If a port is open, the target device will send back a response. If a port is closed, there will be no response.


## What is a port? Describe it with an analogy that would help a family member understand.

A port is like a door on a building. Each port has a unique number that identifies it, and only certain types of traffic are allowed through certain ports. For example, port 80 is the default port for HTTP traffic, which is used to access websites.

## What does a port scanner send to a port to check the current status?

A port scanner sends a packet to the port that it is trying to check. The packet contains information about the type of traffic that the port scanner is sending, such as TCP or UDP.

## When a port scanner sends a request to connect, what are the three possible responses? 

Open: This means that the port is open and listening for incoming connections.
Closed: This means that the port is closed and not listening for incoming connections.
Filtered: This means that the port scanner was unable to determine the status of the port. This could be because the port is filtered by a firewall or because the target device is not responding to the port scan.


Describe them.

## What is the difference between TCP and UDP?

TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are two different protocols that are used for sending data over a network.
TCP is a connection-oriented protocol, which means that it establishes a connection between the sender and receiver before any data is sent. TCP also provides a number of features that make it reliable, such as error checking and retransmission.
UDP is a connectionless protocol, which means that it does not establish a connection between the sender and receiver before any data is sent. UDP is also not reliable, and it does not provide any error checking or retransmission.


## Common Ports

List and describe the ports used for the following:

Telnet 23 A remote login protocol that allows users to interact with a computer over a network using text-based commands.

SSH 22 A secure remote login protocol that provides encrypted communication between a client and a server.

DNS 53 The Domain Name System (DNS) is a hierarchical and decentralized naming system for computers, services, or any resource connected to the Internet or a private network.

SMTP 25  The Simple Mail Transfer Protocol (SMTP) is the standard protocol for sending and receiving email over TCP/IP networks.

HTTP  80 The Hypertext Transfer Protocol (HTTP) is the foundation of data communication for the World Wide Web.

HTTPS  443  The Hypertext Transfer Protocol Secure (HTTPS) is the secure version of HTTP, adding encryption to protect data transmission.

RDP  3389  The Remote Desktop Protocol (RDP) is a proprietary protocol developed by Microsoft to remotely control a computer over a network connection.

Ping   ICMP (Internet Control Message Protocol) Ping is a network utility used to test the reachability of a host on a network and measure the round-trip time for messages sent from the originator to the destination.

## References

[Chat GPT](https://chat.openai.com/share/bf76dc29-997c-4c68-900e-c80760f353aa)

[NMAP](https://www.varonis.com/blog/port-scanning-techniques) 

[Bard](https://bard.google.com/chat/889fe46c8efdcb09) 

## Things I want to know more about:

Using the various tools like wireshark and nmap to test networks and firewalls for vulnerabilities.
