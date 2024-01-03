## Readings 8: RADIUS Authentication

Below you will find reading material and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

Computer Network - AAA (Authentication, Authorization and Accounting)

Explain each of the three A’s as you would to a non-technical family member. Use an analogy or a story. Authentication would be like checking your driver's license to make sure you are who you say you are. Authorization would be the type of drivers license you have: CDL, pilots license, bus driver etc. Accounting would be comparable to the black box in the airplane or even some cars that are like a flight recorder of the actions you took while operating the vehicle or aircraft.

-What should the administrator do if the ACS server fails to authenticate a user during AAA implementation?
Check ACS Server Status:
Verify that the ACS server is running and operational. Check the server's status and ensure that it is accessible over the network.
Network Connectivity:
Verify network connectivity between the device (router, switch, etc.) and the ACS server. Ensure there are no network issues such as firewall blocks, routing problems, or connectivity issues.
ACS Server Logs:
Check the ACS server logs for any error messages or indications of authentication failures. The logs can provide valuable information about the cause of the authentication failure.
User Credentials:
Verify that the user credentials provided are correct. Check for typos, incorrect passwords, or any other issues with the user's credentials.
ACS Server Configuration:
Review the ACS server configuration to ensure that the authentication method (e.g., RADIUS, TACACS+) is correctly configured. Check if the user is configured in the ACS database.
Shared Secrets:
If RADIUS or TACACS+ is being used, ensure that the shared secret (password) configured on the ACS server matches the shared secret configured on the networking device.
AAA Configuration on Networking Device:
Review the AAA configuration on the networking device (router, switch, etc.). Ensure that the device is correctly configured to communicate with the ACS server for authentication.
ACS Server Reachability:
Verify that the ACS server is reachable from the networking device. Ping the ACS server from the device to confirm reachability.
Firewall and Security Policies:
Check for any firewall or security policies that may be blocking communication between the networking device and the ACS server. Ensure that the necessary ports are open.
ACS Server Software Updates:
Ensure that the ACS server is running the latest software updates and patches. Software bugs or issues may be addressed in newer releases.
Fallback Authentication Methods:
If possible, configure fallback authentication methods on the networking device. This allows the device to attempt alternative authentication methods if the primary method (ACS) fails.
Consult ACS Documentation:
Refer to the documentation provided by the ACS server vendor for troubleshooting guidance specific to the server software version in use.


-What is the role of the NAS in the AAA implementation using an ACS server? Use a diagram.
RADIUS Concepts
Authentication:
The NAS initiates the authentication process by forwarding authentication requests to the ACS server.
The NAS communicates with the ACS server using supported authentication protocols.
Authorization:
The NAS forwards authorization requests to the ACS server after successful authentication.
The ACS server evaluates authorization requests and grants or denies access based on policies.
Accounting:
The NAS logs accounting information related to the user's network session.
The NAS periodically forwards accounting data to the ACS server for tracking and auditing.
Dynamic VLAN Assignment:
The NAS may dynamically assign VLANs to users based on their authentication and authorization status.
The NAS coordinates disconnect requests and forwards them to the ACS server when users log out.
Error Handling and Feedback:
The NAS handles authentication and authorization failures and provides appropriate feedback to the end user.


-What are the benefits of using RADIUS for authentication and authorization?
Centralized Authentication:
RADIUS enables centralized authentication, allowing organizations to manage user authentication from a single authentication server. This centralization simplifies user account management and ensures consistent authentication policies across the network.
Scalability:
RADIUS is highly scalable, making it suitable for large and complex network environments. As the number of users and network devices increases, RADIUS servers can handle the authentication requests efficiently.
Security:
RADIUS supports secure communication through protocols like PAP (Password Authentication Protocol), CHAP (Challenge Handshake Authentication Protocol), and EAP (Extensible Authentication Protocol). This ensures that user credentials are transmitted securely over the network.
Authorization Policies:
RADIUS allows for the enforcement of granular authorization policies. Based on user attributes, such as group memberships or roles, administrators can define access policies that determine the resources a user is allowed to access.


-What is RADIUS and what does it stand for?
Remote Access Dial in User Service
Note: It is note dial up like a phone

-Research: What encryption algorithms does RADIUS use?
1. PAP (Password Authentication Protocol):
PAP is a simple authentication protocol that transmits usernames and passwords in plaintext. While PAP is considered less secure due to the lack of encryption, it is still commonly used in legacy networks and for compatibility reasons.
2. CHAP (Challenge-Handshake Authentication Protocol):
CHAP is a more secure alternative to PAP, as it employs a challenge-handshake mechanism to verify user credentials without transmitting passwords in plaintext. This mechanism involves the RADIUS server sending a challenge to the client, which encrypts it with a shared secret and sends it back to the server. The server then compares the encrypted challenge to its own calculation, ensuring the client's knowledge of the shared secret.
3. MS-CHAPv2 (Microsoft Challenge-Handshake Authentication Protocol version 2):
MS-CHAPv2 is an enhanced version of CHAP developed by Microsoft. It introduces additional security measures, such as using a stronger encryption algorithm and incorporating random numbers to enhance the challenge-handshake process.
4. EAP (Extensible Authentication Protocol):
EAP is a more flexible and extensible authentication protocol that supports a variety of authentication methods, including TLS (Transport Layer Security), PEAP (Protected Extensible Authentication Protocol), and TTLS (Tunneled Transport Layer Security). These methods provide strong encryption and secure key exchange, making them suitable for high-security environments.
5. TLS/DTLS (Transport Layer Security/Datagram Transport Layer Security):
TLS/DTLS are encryption protocols that provide secure communication between the RADIUS server and the client. They establish secure channels using strong encryption algorithms and digital certificates to protect data confidentiality and integrity.



[Authentication Methods](https://www.professormesser.com/network-plus/n10-008/n10-008-video/authentication-methods-n10-008/) 

[Defense in Depth](https://www.professormesser.com/network-plus/n10-008/n10-008-video/defense-in-depth-n10-008/) 

[RADIUS and TACACS](https://www.professormesser.com/security-plus/sy0-401/radius-and-tacacs-2/) 

[Kerberos](https://www.professormesser.com/security-plus/sy0-401/kerberos-2/) 

Reference

[Chat GPT](https://chat.openai.com/share/87881497-942a-4d1a-91b9-396f029420f5)

[Google Bard](https://bard.google.com/chat/d47ff40eb0a0ac77) 

## Things I want to know more about

Kerberos is what I would to know more about from what I saw in the videos it seemed like the most complicated Authentication with the ticket granting ticket(TGT)


