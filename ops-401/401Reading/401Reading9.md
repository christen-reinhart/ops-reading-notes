## Readings 9: Public Key Infrastructure (PKI)

Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

1.What is Public Key Infrastructure (PKI)

Authentication: verifying the identity of individuals, devices, or websites.
Encryption: securing communication channels and protecting sensitive data.
Non-repudiation: ensuring accountability for actions and transactions.


2.Name the three main components which make up PKI.

Key Generation: Each entity (user, device, website) involved in PKI generates a pair of cryptographic keys:
Public Key: Shared publicly and used for encryption and signature verification.
Private Key: Kept secret and used for decryption and signature creation.
Certificate Authority (CA): A trusted third-party verifies an entity's identity and issues a digital certificate. This certificate binds the entity's public key to its identity and other relevant information.
Certificate Verification: When two entities communicate, they exchange their certificates. Each party can verify the other's certificate using the CA's public key, ensuring its authenticity and legitimacy.
Encryption and Signing: Entities use their private keys to sign messages or encrypt data for the other party. Only the recipient's corresponding public key can decrypt the data or verify the signature.



3.How would you explain, to a non-technical friend, the role PKI plays in protecting traffic between your browser and a web server.

-Imagine the internet like a busy highway, where millions of people (browsers) and shops (web servers) exchange things (data). Now, sometimes you want to send something valuable to a specific shop, like your credit card info to purchase a gift. 

4.What is the main weakness of the PKI architecture?

-Human Factor and Social Engineering: Phishing attacks can trick users into visiting fake websites with valid certificates, bypassing PKI security.

## Reference

[Prof Messer PKI](https://www.youtube.com/watch?v=3yuad7_bszE) 

## Things I want to know more about

Implementing the PKI in enterprise networks.
