## Readings 37: Automated AppSec with ZAP

- Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

- Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

### Getting Started with Zed Attack Proxy

1) What are the common stages of the Penetration Testing process and what tasks are performed at each one?

a) Pre-Engagement:
- Tasks:

- Define the scope and goals of the test with the client.
- Gather information about the target systems and network.
- Identify stakeholders and obtain necessary approvals.
- Develop a detailed test plan outlining methodology, tools, and reporting format.

b) Information Gathering (Reconnaissance):
- Tasks:

- Gather publicly available information about the target, including network diagrams, employee information, and software versions.
- Identify potential attack vectors and vulnerabilities.
- Map the network infrastructure to understand its layout and connectivity.

c) Scanning and Enumeration:
- Tasks:

- Use automated tools to scan the target network for vulnerabilities in systems, applications, and configurations.
- Identify specific weaknesses and gather detailed information about them (enumeration).
- Analyze the results to prioritize potential attack vectors.

d) Exploitation and Post-Exploitation:
- Tasks:

- Attempt to exploit identified vulnerabilities using manual or automated tools.
- Gain access to systems and network resources, simulating real-world attacker behavior.
- Maintain access and escalate privileges if possible.
- Document the exploit process and potential impact on the target.

e) Reporting and Post-Engagement:
- Tasks:

- Document the findings in a comprehensive report, including identified vulnerabilities, exploited weaknesses, and potential impact.
- Provide recommendations for remediation and mitigation strategies.
- Discuss the test limitations and future testing recommendations.
- Conduct a closing meeting with stakeholders to discuss the findings and recommendations.


2) Explain a “main-in-the-middle proxy” in non-technical terms.

- Imagine you're sending a letter to your friend. Normally, you'd write the letter, put it in an envelope, and send it directly to your friend's address. However, if someone wanted to read or tamper with your letter, they might intercept it before it reaches your friend.

- Now, let's say you want to ensure your letter reaches your friend safely. So, instead of sending it directly, you give it to a trusted person, let's call them Alice. Alice receives your letter, opens it to make sure it's safe, then puts it in a new envelope and sends it to your friend. Your friend receives the letter, knowing it's coming from you via Alice.

3) What are the 2 spiders available for use in ZAP?

- Traditional Spider: This spider works by systematically crawling through a web application, following links and submitting forms to discover all accessible pages and functionality within the application.

- Ajax Spider: Unlike the Traditional Spider, the Ajax Spider is designed to handle web applications that heavily rely on JavaScript and AJAX (Asynchronous JavaScript and XML) to dynamically load content.

4) What situations are they best suited for?

1) Traditional Spider:

- Well-structured web applications with primarily static content: The Traditional Spider is ideal for systematically crawling through such applications, following links, and discovering all accessible pages and functionality.

2) Ajax Spider:

- Web applications with heavy use of JavaScript and AJAX: The Ajax Spider is specifically designed to handle dynamic web applications where content is loaded asynchronously using JavaScript.


## Bookmark and Review

[Python Tools for Cyber](https://hackersonlineclub.com/python-tools/)

[Chat GPT](https://chat.openai.com/share/13d79e6f-f147-465c-a2d4-088b26814cf7) 

## Things I want to know more about 

- How to perform a penetration test and the various tools along with different tests depending on the environment.
