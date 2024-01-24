## Readings 14: Intrusion Detection and Prevention Systems (IDS/IPS)

-Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

-Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

1.List 2 differences between firewalls and an IDS?

-Firewall: Prevents unauthorized access to a network or system by acting as a barrier or gatekeeper. It controls incoming and outgoing traffic based on a set of predefined rules and filters. 
-IDS: Detects unauthorized or suspicious activity within a network or system. It monitors traffic for patterns or anomalies that may indicate an attack, but it does not directly block or prevent the activity.


2.Under what circumstances would you choose a network-based IDS over a host-based IDS?

- If your applications and services are spread across multiple hosts, a NIDS offers a single point of visibility for the entire network.
-NIDS can monitor all traffic passing through the network, regardless of its origin or destination. This can help detect malicious activity initiated by authorized users (insider threats) within the network.
 

3.Name 3 major drawbacks of a NIDS?

-NIDS cannot inspect encrypted traffic, which hinders their ability to detect attacks hidden within encrypted communication channels.
-NIDS rely on analyzing network traffic patterns to identify suspicious activity. However, these patterns can sometimes be misinterpreted, leading to false positives.
-Unlike firewalls that can directly block or prevent suspicious traffic, NIDS primarily function as an alerting system.

## Videos

[Network IDS](https://www.youtube.com/watch?v=hEgWPWIuq_s&ab_channel=ProfessorMesser) 

## Reference

[The Pros and Cons ](https://blog.rapid7.com/2017/01/11/the-pros-cons-of-intrusion-detection-systems/)

## Things I want to know more about

-How to set up firewalls and intrusion detection systems. I would like to know how to input the actual setting into a firewall to prevent the wrong traffic and allow the right traffic.
