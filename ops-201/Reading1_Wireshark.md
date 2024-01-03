## Readings: Network Traffic Analysis with Wireshark

Below you will find reading material and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading

Layers of OSI Model

## What does “OSI” stand for?

"OSI" stands for "Open Systems Interconnection."


## List the 7 layers of the OSI model and what each one is responsible for.

Physical Layer: The physical layer is responsible for the physical transmission of data bits across the network. It defines the physical characteristics of the network, such as the type of cable, connectors, and voltages.
Data Link Layer: The data link layer is responsible for error-free data transmission over a physical link. It breaks down data into frames, adds error-checking information, and manages the physical address of the devices on the network.
Network Layer: The network layer is responsible for routing data packets across the network. It determines the best path for data to travel, and it handles the addressing and routing of data packets.
Transport Layer: The transport layer is responsible for providing reliable data transmission between end-user applications. It provides sequencing, error-checking, and flow control for data packets.
Session Layer: The session layer is responsible for establishing, managing, and terminating communication sessions between applications. It handles synchronization, dialog control, and token management.
Presentation Layer: The presentation layer is responsible for formatting data for presentation to the application layer. It handles data encryption, compression, and character conversion.
Application Layer: The application layer is the top layer of the OSI model and is responsible for providing network services to application programs. It provides services such as file transfer, email, and web browsing.


## Distinguish which layers are the “hardware layers”, and which layers are the “software layers”. 

The OSI model's lower three layers, the Physical Layer, Data Link Layer, and Network Layer, are considered hardware layers. These layers are responsible for the physical transmission of data bits across the network, error-free data transmission over a physical link, and routing data packets across the network, respectively.

The upper four layers of the OSI model, the Transport Layer, Session Layer, Presentation Layer, and Application Layer, are considered software layers. These layers are responsible for providing reliable data transmission between applications, establishing, managing, and terminating communication sessions, formatting data for presentation to applications, and providing network services to applications, respectively.

## What does that even mean?

The bottom 3 layers still rely heavily on hardware to complete their tasks. The upper levels are mostly applications, protocols, and software.

## How can the OSI model be used in troubleshooting?

Physical Layer: Verify that the physical connections are secure and that the cables are in good condition. Test the network interface cards (NICs) on both the sending and receiving devices.
Data Link Layer: Use ping to test connectivity at the Data Link Layer. Verify that the MAC addresses of the devices are correct. Check for errors in the network configuration.
Network Layer: Use ping to test connectivity at the Network Layer. Verify that the IP addresses of the devices are correct. Check the routing tables on routers and switches.
Transport Layer: Use telnet or FTP to test connectivity at the Transport Layer. Verify that the port numbers of the applications are correct. Check the firewall settings on the devices.
Session Layer: Use applications such as NetBIOS or AppleTalk to test connectivity at the Session Layer. Verify that the session establishment protocols are functioning correctly.
Presentation Layer: Use encryption and compression tools to test connectivity at the Presentation Layer. Verify that the data encoding and decoding protocols are functioning correctly.
Application Layer: Use applications such as email or web browsers to test connectivity at the Application Layer. Verify that the application-specific protocols are functioning correctly.


## What Is Wireshark and How Is It Used?

Wireshark is a free and open-source network protocol analyzer that captures and analyzes network traffic. It is used by network administrators, security professionals, and software developers to troubleshoot network problems, analyze network traffic, and develop new network protocols. Wireshark can capture traffic from a variety of network interfaces, including wired and wireless networks, and it can decode packets for a wide range of protocols, including TCP, IP, UDP, HTTP, and DNS.

Feel free to stop at “How to Use Wireshark”


## What is a packet?

Packets are the basic building blocks of network communication. They are used to transmit data between computers, routers, switches, and other network devices. When a computer sends a message over a network, the message is broken up into packets and sent over the network one packet at a time. The packets are then reassembled at the destination computer to form the original message.

## What 3 high-level things does Wireshark accomplish? How could these be used for nefarious purposes? For benevolent purposes? 


Wireshark, network protocol analyzer, accomplishes three high-level tasks:
Capturing network traffic: Wireshark can capture real-time network traffic from a variety of network interfaces, including wired and wireless connections. This captured traffic serves as a valuable source of information for network troubleshooting, security analysis, and protocol development.
Decoding network packets: Wireshark can decode packets for a wide range of network protocols, including TCP, IP, UDP, HTTP, DNS, and many more. By decoding the packet structure, Wireshark provides insights into the content and flow of network traffic.
Analyzing network traffic: Wireshark offers a comprehensive suite of tools for analyzing captured network traffic. These tools include filters, statistics, and graphical visualizations that help network professionals identify patterns, anomalies, and potential issues.
Nefarious Purposes
Wireshark's powerful capabilities can be misused for various nefarious purposes, including:
Interception and eavesdropping: Wireshark can capture and monitor network traffic, potentially exposing sensitive data such as passwords, login credentials, and confidential communications.
Network traffic manipulation: Wireshark can be used to modify or inject network packets, potentially disrupting network services, launching Denial-of-Service (DoS) attacks, or altering data transmissions.
Vulnerability analysis and exploitation: Wireshark can be used to identify vulnerabilities in network protocols or applications, potentially enabling attackers to exploit those weaknesses.
Benevolent Purposes
Wireshark's capabilities can also be harnessed for various benevolent purposes, including:
Network troubleshooting: Wireshark can be used to pinpoint the root cause of network problems, such as latency issues, packet loss, or connectivity disruptions.
Security analysis: Wireshark can be used to identify potential security threats, such as malware infections, intrusion attempts, or unauthorized access.
Performance optimization: Wireshark can be used to analyze network traffic patterns and identify bottlenecks or inefficiencies, helping optimize network performance.
Protocol development and testing: Wireshark can be used to debug and test new network protocols, ensuring they function correctly and adhere to standards.


## References:
[Wire Shark](https://www.comptia.org/content/articles/what-is-wireshark-and-how-to-use-it) 
[Chat GPT](https://chat.openai.com/share/c6f7160c-ac3a-482e-8c53-5d56c03352ab) 
## Things I want to know more about
Hopefully tomorrow I will learn more about how to use wireshark. I have downloaded the application and am looking forward to learning how to interpret the data and set it up.
