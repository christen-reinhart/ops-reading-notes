## Readings 38: Attacking Juice Shop with Burp Suite

- Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

- Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

1. What is Burp Suite?

- Burp Suite is a software application used for penetration testing, specifically for testing the security of web applications. 

2. Explain how Burp Suite allows us to analyze web application traffic.

- Burp Suite acts as an intercepting proxy, meaning it sits between your browser and the web application you're testing. This allows Burp Suite to intercept all the traffic (requests and responses) flowing between your browser and the application. 

3. What does the Repeater tool allow us to do with requests?

- Resend captured requests: You can replay any captured request in the Repeater, potentially with modifications, to analyze the application's response under different conditions.

- Modify requests: You can change various parts of a captured request, like headers, parameters, or the request body, before resending it. 

4. Why might this be a useful tool for an attacker?

- Identifying vulnerabilities: By modifying requests and observing the application's response, attackers can try to identify weaknesses in the application's security mechanisms.

- Crafting exploits: Once a vulnerability is identified, the attacker can use the Repeater to craft a specific exploit by fine-tuning the modifications made to the request.

- Testing attack effectiveness: The attacker can use the Repeater to test different attack variations and see how the application reacts before launching a full-blown attack.


## Reference

[What is Burp suite](https://www.technipages.com/what-is-burp-suite)

## Things I want to know more about

- Exploring advanced techniques like writing your own Burp Suite extensions.
