## Readings 6: Data file encryption

Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

Applying The CIA Triad To Your Enterprise File Transfer

## What Are MD5, SHA-1, and SHA-256 Hashes, and How Do I Check Them?

1. MD5 (Message Digest Algorithm 5):
Produces a 128-bit (16-byte) hash value.
Widely used in the past, but now considered insecure for cryptographic purposes due to vulnerabilities that allow collisions (different inputs producing the same hash).
2. SHA-1 (Secure Hash Algorithm 1):
Produces a 160-bit (20-byte) hash value.
Like MD5, SHA-1 is also considered insecure for cryptographic purposes due to vulnerabilities.
3. SHA-256 (Secure Hash Algorithm 256-bit):
Part of the SHA-2 family, which includes other hash functions like SHA-224, SHA-384, and SHA-512.
Produces a 256-bit (32-byte) hash value.
Currently considered secure and widely used for cryptographic applications.


## You have been made responsible for the company’s file server. How would you preserve the three elements of the CIA triad?

1) Confidentiality:
- Access Controls: Implement strong access controls to ensure that only authorized personnel have access to sensitive data. Use role-based access control (RBAC) and regularly review and update permissions.
- Encryption: Encrypt sensitive data to protect it from unauthorized access. Utilize encryption protocols for both data in transit and data at rest. This helps ensure that even if someone gains access to the storage, the data remains confidential.
2) Integrity:
- Hash Functions: Implement hash functions like SHA-256 to generate checksums for files. Regularly check the integrity of files by comparing their current hash values with the originally recorded hash values. Any discrepancies indicate potential tampering or corruption.
- Access Controls and Logging: Restrict write permissions to authorized users and maintain detailed access logs. Regularly review logs for any suspicious activities that could indicate unauthorized modifications to files.
3) Availability:
- Redundancy: Implement redundancy measures such as RAID (Redundant Array of Independent Disks) to ensure data availability in case of hardware failures. Regularly back up critical data, and store backups in different physical locations to mitigate risks.
- Monitoring and Incident Response: Implement monitoring tools to detect potential issues affecting server availability. Have an incident response plan in place to quickly address and mitigate any disruptions to server availability, whether they are due to technical failures or security incidents.
### Additionally:
- Regular Audits and Assessments: Conduct regular security audits and assessments to identify vulnerabilities and areas for improvement in the server's security posture.
- Employee Training: Provide ongoing security awareness training to employees to ensure they understand the importance of security practices and their role in preserving the CIA triad.
- Patch Management: Keep server software and operating systems up to date with the latest security patches to address known vulnerabilities.




## Explain how hashing verifies data integrity using non-technical terms. How is hashing and encryption different?

- Hashing is a one-way process:
Once you create the lock, you can't open it to get the original data. It's purely for verification.
If you forget what's inside the chest, hashing won't help you recover it.
- Encryption is a two-way process:
You can lock and unlock the contents using the right keys.
If you forget what's inside the magic box, you can use the decoding key to reveal the original contents.

## Reference: 

[Applying CIA](https://www.jscape.com/blog/implementing-the-cia-triad-when-transferring-files-through-the-internet) 

[What are MD5\ SHA-1 etc](https://www.howtogeek.com/67241/htg-explains-what-are-md5-sha-1-hashes-and-how-do-i-check-them/) 


[Chat GPT](https://chat.openai.com/share/1fa7c34c-709e-45f9-834e-abd8583d9951) 

## Things I want to know more about

Using the command line interface and encrypting files, documents, etc.

