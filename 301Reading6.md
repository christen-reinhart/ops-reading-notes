## Readings 6: Network Address Translation

Below you will find reading material and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

Network Address Translation (NAT)

-What is the main purpose for implementing NAT on a network?
The main purpose of implementing NAT is to conserve public IP addresses, which are limited resources. By allowing multiple devices to share a single public IP address, NAT significantly reduces the number of required public IP addresses.

-At what layer of the OSI model does NAT happen?
NAT operates at the Network Layer (Layer 3) of the OSI model. It intercepts and modifies the IP address headers of packets as they traverse the network boundary between the private and public networks.
-What happens to packets when NAT runs out of addresses in the pool of available IPs?
Port Address Translation (PAT): PAT assigns a single public IP address to multiple private devices, differentiating them using unique port numbers.
Address Pool Overflow Detection: NAT can detect when the address pool is exhausted and notify the network administrator or implement alternative routing mechanisms.
Dynamic NAT: Dynamic NAT can reuse public IP addresses that have become inactive, providing more flexibility.


-What disadvantage does using NAT pose for routers?
Complexity: NAT adds complexity to routers, requiring additional processing and address management.
Troubleshooting: NAT can make troubleshooting network issues more complex, as it masks the true source of network traffic.
Security Implications: NAT can hinder certain security protocols and tools that rely on end-to-end IP address visibility.
Application Compatibility: Some applications may not function properly with NAT due to the alteration of IP addresses.


## References:

[Network Address Translation](https://www.professormesser.com/professor-messer-archives/n10-007/network-address-translation-3/) 

[Common Network Types](https://www.professormesser.com/professor-messer-archives/n10-007/common-network-types/) 

[IPv4 and IPv6 Addressing](https://www.professormesser.com/professor-messer-archives/n10-007/ipv4-and-ipv6-addressing/) 

[Chat GPT](https://chat.openai.com/c/c7a1ee7a-b49d-4577-bf17-f013929d37d2) 

[Google Bard](https://bard.google.com/chat/d47ff40eb0a0ac77) 

## Things I would like to know more about

How to implement NAT and PAT on a router using the CLI.
