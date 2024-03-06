## Readings 43: Sniffing and Evasion

- Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

- Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

1. Explain a Sniffing attack using non-technical terms.

- A sniffing attack is kind of like eavesdropping on a computer network conversation. Instead of voices, attackers use special tools to listen in on data traveling across the network. This data is like messages being sent back and forth between computers and websites.

2. What are the two types of sniffing attacks and what are some pros and cons of each approach?

1. Passive Sniffing:
- Pros:
- Easier to set up: Requires minimal effort, just listening in on existing network traffic.
- Harder to detect: Doesn't disrupt the network flow, making it stealthier.
- Cons:
- Limited data: Only captures data readily available on the network segment, might miss targeted communication.
- Less effective on modern networks: Switches, common in most networks, direct data only to intended recipients, limiting passive snooping opportunities.

2. Active Sniffing:
- Pros:
- Targeted data: Can focus on specific devices or communication channels, increasing the chance of capturing desired information.
- Can bypass some security measures: Some techniques, like ARP Spoofing, can trick devices into revealing data they wouldn't normally share.
- Cons:
- More complex to set up: Requires additional technical knowledge and tools to manipulate network traffic.
- Easier to detect: Disrupting the network flow can raise red flags and alert security systems.

3. How does encryption protect traffic against sniffing attacks?

- When data is encrypted, it becomes gibberish to anyone who doesn't have the decryption key.

- Encryption often involves mechanisms to detect tampering. If a sniffer tries to modify the encrypted data, it will likely be detected, rendering the information useless.

## Reference

[Sniffing Attack in System Hacking](https://www.geeksforgeeks.org/what-is-sniffing-attack-in-system-hacking/) 

## Things I want to know more about

- Implementing packet sniffing and in depth packet analysis and identifying traffic anomalies.
