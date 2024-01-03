## Readings 4: Routing

Below you will find reading material and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

VirtualBox Network Settings Guide

Which network mode in VirtualBox can be used to emulate unplugging the Ethernet cable from the network?
Network Address Translation (NAT): VirtualBox creates a private network for the VM and assigns it a private IP address. When the VM tries to access the internet, its traffic is routed through a NAT router within VirtualBox. The NAT router translates the VM's private IP address to the host machine's public IP address, allowing the VM to communicate with the internet.


 Which network mode would be best if you wanted to run a server on a VM that could be fully accessible from your physical local area network?
The best network mode for running a server on a VM that should be fully accessible from your physical local area network (LAN) would be Bridged Networking. This mode allows the VM to directly participate in the LAN, making it appear as a separate device on the network and enabling seamless communication with other devices on the same network.

What are the three options of promiscuous mode and what does each do?
In VirtualBox, the term "Promiscuous Mode" is related to networking and how a virtual network adapter behaves. Promiscuous mode allows a network interface to pass all traffic it receives to the operating system's networking stack, rather than just the packets addressed to it. In the context of VirtualBox, there are three options for Promiscuous Mode, and they are associated with how the virtual network adapter handles network traffic. These options are available when you configure the network settings for a virtual machine:
Deny: In this mode, the virtual network adapter only receives frames that are addressed specifically to it. It doesn't capture or process frames that are not explicitly destined for its MAC address. This is the default setting for security reasons, as it prevents a virtual machine from eavesdropping on the network traffic of other virtual machines on the same host.
Allow VMs: This mode allows the virtual network adapter to receive frames that are addressed to other virtual machines on the same host. It allows communication between virtual machines on the same host. However, the host machine's physical network adapter still filters out traffic not destined for the host or the VMs.
Allow All: In this mode, the virtual network adapter receives all frames on the physical network, regardless of the destination MAC address. This means that the virtual machine can capture and process all network traffic on the physical network to which the host is connected. It effectively puts the virtual machine's network adapter in promiscuous mode, allowing it to see all traffic on the network.



What is Port Forwarding?
Port forwarding is a networking technique used to redirect a communication request from one address and port number combination to another while the data packets are traversing a network gateway, such as a router or firewall. This process is commonly employed in home and small office networks to enable access to services or applications hosted on devices within the local network from the outside world, typically over the internet.

## References:

[Prof Messer](https://www.professormesser.com/network-plus/n10-008/n10-008-video/network-switching-overview-n10-008/) 
[Prof Messer](https://www.professormesser.com/network-plus/n10-008/n10-008-video/n10-008-dynamic-routing/) 
[Prof Messer](https://www.professormesser.com/network-plus/n10-008/n10-008-video/routing-technologies-n10-008/) 
[Prof Messer](https://www.professormesser.com/network-plus/n10-008/n10-008-video/network-topologies-5/) 

[Chat GPT](https://chat.openai.com/share/8003f867-47a6-4042-b45e-656081ddb534) 

[Google Bard](https://bard.google.com/chat/889fe46c8efdcb09) 

## Things I want to know more about:

Port forwarding and how to implement it.I have heard the terminology but have not seen it used before or had a class on it.
