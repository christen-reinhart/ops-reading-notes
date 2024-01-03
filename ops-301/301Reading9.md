## Readings 9: Traffic Mirroring

Below you will find reading material and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

## How to capture network traffic? SPAN vs TAP

## What are the differences between SPAN and TAP?
SPAN(Switched Port Analyzer) : Works at Layer 2 of the OSI model. It copies traffic passing through a switch port to another port for monitoring.
TAP(Test Access Point): Operates at Layer 1 It physically intercepts the actual network cable and duplicates the traffic onto a separate monitoring port.


## What types of network devices can support network traffic mirroring?
Switches: Most managed switches support SPAN or similar features for port mirroring.
Network Interface Cards (NICs): Some high-end NICs offer hardware-based mirroring capabilities.
Routers: Some routers offer SPAN functionality or dedicated mirroring ports.
Load Balancers: Some load balancers can mirror traffic for specific applications or services.
Dedicated Monitoring Appliances: Specialized appliances are available for high-performance and feature-rich network traffic mirroring.


## How can network traffic mirroring be used for network security?
Security incident investigation: By analyzing mirrored traffic, security teams can identify and investigate security incidents such as malware infections, data breaches, and unauthorized access attempts.
Intrusion detection and prevention: Mirrored traffic can be fed into intrusion detection/prevention systems (IDS/IPS) to identify and block malicious traffic patterns.
Traffic analysis and troubleshooting: By analyzing mirrored traffic, network administrators can troubleshoot network performance issues, identify bandwidth hogs, and optimize network traffic flow.
Compliance monitoring: Mirrored traffic can be used to demonstrate compliance with security regulations and standards.


## Are there any legal or ethical considerations when using network traffic mirroring?
Privacy laws: Many countries have laws that protect the privacy of individuals' communications. These laws may restrict how you can collect and use network traffic data. For example, the European Union's General Data Protection Regulation (GDPR) requires organizations to have a lawful basis for processing personal data.
Wiretapping laws: In some jurisdictions, wiretapping laws may require you to obtain a warrant before you can intercept or monitor network traffic.
Data retention laws: Some laws may require you to retain network traffic data for a certain period of time. This can have implications for storage space and data management.
Transparency: You should be transparent about your use of network traffic mirroring. Inform users whose traffic will be monitored and provide them with a clear explanation of why and how their data will be used.
Privacy: You should only collect and use network traffic data for legitimate purposes. You should not collect or use data that is not necessary for your stated purpose.




## Reference

[Logs and Monitoring](https://www.professormesser.com/network-plus/n10-008/n10-008-video/logs-and-monitoring-n10-008/) 

## Things I would like to know more about

How to use a switch port analyzer and understand the information. How to install a test access point at layer one.
