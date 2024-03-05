## Readings 42: Pass the Hash with Mimikatz

- Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

- Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

1. Name the six credential-gathering techniques which Mimikatz is able to perform and explain how two of them work.

- Pass-the-Hash (PtH): Mimikatz can extract password hashes from memory or through the LSASS (Local Security Authority Subsystem Service) process and then use these hashes to authenticate to other systems without needing to know the actual plaintext passwords.

- Pass-the-Ticket (PtT): This technique involves stealing Kerberos tickets (TGTs or TGSs) from memory or LSASS and using them to authenticate to other systems. By obtaining valid tickets, attackers can access resources without needing to provide valid credentials.

- Pass-the-Cache (PtC): Mimikatz can extract cached credentials stored in the system's memory, including passwords and NTLM hashes, and use them to gain unauthorized access to resources.

- Over-Pass-the-Hash: This technique involves manipulating certain security protocols, such as NTLM, to allow for the authentication of arbitrary usernames and hashes, even if they do not match.


- Pass-the-Key: Mimikatz can extract Kerberos keys from LSASS memory, allowing attackers to impersonate users and gain unauthorized access to resources protected by Kerberos authentication.


- Golden Ticket: This technique involves forging Kerberos tickets with arbitrary group membership and expiration times, effectively granting attackers full control over a domain. Golden tickets are persistent and can be used to maintain access even after passwords are changed.

## Explanation of Two Techniques:

- Pass-the-Hash (PtH): Mimikatz retrieves password hashes (NTLM or Kerberos) from memory or LSASS. It then sends these hashes directly to the targeted system as part of the authentication process, bypassing the need for plaintext passwords. The targeted system verifies the received hash against its own stored hash, granting access if they match. This technique is effective because it allows attackers to authenticate to systems without needing to know the actual passwords, making it difficult for traditional security measures like password complexity to prevent unauthorized access.

- Golden Ticket: Mimikatz forges Kerberos tickets, specifically Ticket Granting Tickets (TGTs), which are used by the Key Distribution Center (KDC) to authenticate users and grant them access to resources within a domain. With a 

- Golden Ticket, attackers can generate a TGT for any user and specify arbitrary group memberships and privileges, effectively granting themselves unrestricted access to any resource in the domain. Golden Tickets are difficult to detect and can persist indefinitely, even after domain passwords are changed, making them a powerful and stealthy method for maintaining unauthorized access to a network.

2. What are four ways we can defend against Mimikatz attacks. Explain how two of the mitigations can stop Mimikatz.

- Use Credential Guard: Credential Guard is a security feature available in Windows 10 and Windows Server 2016 that protects credentials by utilizing virtualization-based security. It stores NTLM and Kerberos credential hashes in a secure isolated container (LSAIso) rather than in LSASS memory, making them inaccessible to Mimikatz and other credential-gathering tools.

- Implement LAPS (Local Administrator Password Solution): LAPS is a Microsoft tool that automatically generates and manages unique passwords for local administrator accounts on domain-joined computers. By regularly rotating local administrator passwords and storing them securely in Active Directory, LAPS can prevent attackers from using stolen or cracked passwords to move laterally across the network.

- Enable Credential Theft Mitigations: Windows includes several built-in security features designed to mitigate credential theft attacks, such as:
a. Restricted Admin Mode for Remote Desktop Services (RDP): This feature prevents the transmission of credentials to the remote server during RDP sessions, reducing the risk of credential theft via pass-the-hash attacks.
b. Credential Guard: As mentioned earlier, Credential Guard protects credentials by storing them securely in a virtualized environment, making them inaccessible to Mimikatz and other credential-gathering tools.

- Implement Least Privilege: Limit user privileges and access rights to only those necessary for performing job functions. By enforcing least privilege, organizations can reduce the impact of credential theft attacks. Attackers may obtain credentials, but their ability to move laterally and escalate privileges within the network is constrained.
 ## Explanation of Two Mitigations:

- Credential Guard: Credential Guard protects against Mimikatz attacks by securely storing NTLM and Kerberos credential hashes in a virtualized environment (LSAIso), inaccessible to processes running in the operating system. Mimikatz relies on accessing credential hashes stored in LSASS memory, but with Credential Guard enabled, these hashes are encrypted and isolated, preventing Mimikatz from extracting them.

- Restricted Admin Mode for RDP: Restricted Admin Mode (Remote Credential Guard) prevents the transmission of plaintext credentials to remote servers during RDP sessions. Instead of sending the actual credentials, Restricted Admin Mode uses a temporary session-based token to authenticate to the remote server, reducing the risk of credential theft via pass-the-hash attacks. Mimikatz requires access to plaintext credentials or hashes stored in LSASS memory to perform pass-the-hash attacks, but with Restricted Admin Mode enabled, this information is not transmitted over the network, effectively mitigating Mimikatz attacks during RDP sessions.

## Reference

[What is Mimikatz?](https://www.varonis.com/blog/what-is-mimikatz/) 

## Things I want to know more about

- Restricted Admin mode and Credential guard
