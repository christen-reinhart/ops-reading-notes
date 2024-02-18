## Read: Class 31

### Readings: Malware Detection with YARA Rules

- Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

- Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

1. What is the main goal of Threat Hunting and how is it different from traditional threat monitoring?
-The main goal of threat hunting is to proactively identify and mitigate cyber threats that may have infiltrated an organization's network, aiming to detect and respond to threats before they cause significant damage. Threat hunting involves actively searching for indicators of compromise (IOCs) and signs of malicious activity that may not be detected by traditional security measures like antivirus software or firewalls.

2. What are the four types of YARA rules and what does each one of them use to identify and classify malicious software?

1. Pattern-based rules: These rules utilize strings of text, which can either be explicit values or regular expressions, to identify malware based on specific patterns found within its code.

2. Metadata-driven rules: These rules depend on file metadata to detect malware. Metadata encompasses details such as file type, creation or modification timestamps, or other attributes.

3. Hash-based rules: These rules leverage cryptographic hashes, unique representations of file contents, to identify malware.

4. Network-centric rules: These rules scrutinize network traffic data, such as IP addresses, ports, or protocols, to identify malware-related activities. 

3. How are YARA rules similar to how Anti-Virus programs detect malicious software?

- YARA rules and antivirus programs share common ground in detecting malicious software. Both rely on pattern matching techniques to identify potential threats: YARA rules utilize patterns defined by strings of text, file metadata, hashes, or network traffic data, while antivirus programs leverage signatures or heuristics to match against known patterns associated with malware. They both employ signature-based detection, comparing the characteristics of files or network traffic against a database of known malware signatures to flag suspicious entities. 

## Bookmark and Review

- YARA Rules GitHub Project

- This project covers the need of a group of IT Security Researchers to have a single repository where different Yara signatures are compiled, classified and kept as up to date as possible, and began as an open source community for collecting Yara rules.

## Reference

[Archerint](https://archerint.com/what-are-yara-rules/)

[Threat Hunting](https://www.geeksforgeeks.org/threat-hunting-using-yara/)

[Github](https://github.com/Yara-Rules/rules)

## Things I want to know more about

- How to use YARA rules to target specific attacks in threat-hunting.

