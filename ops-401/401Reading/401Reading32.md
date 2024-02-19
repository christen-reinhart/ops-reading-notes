## Readings 32: Malware Traffic Analysis with Wireshark

- Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

- Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

1. What is Malware Analysis?

- Behavioral analysis focuses on understanding the actions and interactions of malware with its environment. Code analysis involves decompiling, disassembling, or reverse engineering the malware's code to understand its internal workings and logic. Memory analysis involves examining the volatile memory (RAM) of a compromised system to identify running processes, loaded modules, network connections, injected code, and other artifacts left by the malware. 

2. You just started a new job as a Malware Analyst. Explain your job responsibilities to a family member. 

- I would tell them it is similar to studying actual viruses like Medical virologists. The main difference is you are studying digital code instead of genes or cells.

3. What are the six steps of the Malware Analysis process? What’s a good mnemonic you can use to remember it?

a) Identification: In this step, analysts identify and gather information about the suspicious file or behavior that may indicate the presence of malware.

b) Static Analysis: Static analysis involves examining the malware without executing it. Analysts analyze the structure, code, and characteristics of the malware to understand its functionality, behavior, and potential impact.

c) Dynamic Analysis: Dynamic analysis involves executing the malware in a controlled environment, such as a sandbox or virtual machine, to observe its behavior in real-time.

d) Behavioral Analysis: Behavioral analysis focuses on understanding how the malware interacts with its environment and affects system resources, processes, and files.

e) Code Analysis: Code analysis involves decompiling, disassembling, or reverse-engineering the malware's code to understand its internal workings, logic, and algorithms. 

f) Reporting: The final step is to document the findings and analysis results in a comprehensive report.

- A mnemonic that can be used to remember these six steps is "I SDB CR" 

4. You are tasked with analyzing a new malware sample. Which type of malware analysis would you conduct first and why?

- Trojans since they disguise themselves as legitimate files or software to trick users into executing them. I like the trojan type of malware since it lays dormant and seems like an actual program. The person that put it in place could have been gone for a long time before someone else triggers the malware.

## Reference

[Chat GPT](https://chat.openai.com/share/07036ee5-b77a-47d2-8da4-5d30a9a43901) 

[Toolbox](https://www.toolbox.com/security/data-security/articles/what-is-malware-analysis-definition-types-stages-best-practices/)

## Things I want to know more about

- How to use a sandbox to analyze malware and perform digital forensics.
