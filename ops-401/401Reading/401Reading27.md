## Readings 27: Persistence

- Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

- Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

- While no longer maintained by its original creator as of writing, PowerShell Empire has been forked many times and was used by nation state actors from 2015-2019. The PowerShell 

- The Empire project is now actively maintained by BC Security. As you read this article, take note of its original purpose as well as the tactical advantages offered to its users.

1. What is one of the major advantages of PowerShell Empire?

- A key benefit it offers is its utilization of encrypted communication with the command and control server, rendering its traffic detection particularly challenging, especially within extensive networks.


2. What are some of the APT groups that have been known to use PS Empire and into which step of the Cyber Kill Chain does the use of PS Empire fall?

- During the 2018 Winter Olympics in South Korea, the APT group Hades employed Empire as part of its Olympic Destroyer campaign.

- Towards the conclusion of 2018, the cybercrime group FIN7 transitioned to utilizing the Empire framework, expanding beyond reliance solely on the Cobalt Strike threat emulation software.


3. What are the four main components needed to pull off an attack using PS Empire?

1. Listener: This component sets up the listening post, which is responsible for receiving connections from compromised targets.

2. Stager: The stager is the initial payload delivered to the target system. It's typically small and designed to establish communication with the Empire server, allowing for further stages of the attack to be deployed.

3. Module: Modules are scripts or pieces of code used to perform specific actions on the compromised system, such as gathering information, executing commands, or exfiltrating data.

4. Agent: The agent is the backdoor implanted on the compromised system after successful exploitation. It communicates with the Empire server, allowing the attacker to control the system and execute commands remotely.

## Reference

[PowerShell Empire No Longer Maintained](https://www.bleepingcomputer.com/news/security/powershell-empire-framework-is-no-longer-maintained/) 

[Hacking with Empire](https://www.hackingarticles.in/hacking-with-empire-powershell-post-exploitation-agent/) 

## Things I want to know more about

- How to develop tools like Empire PowerShell to prevent malicious activity.

