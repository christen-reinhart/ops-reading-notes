## Read: Class 36  XSS with w3af, DVWA

- Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

- Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

1. Explain how a cross-site scripting attack works in non-technical terms.

- Imagine you're building a sandcastle on the beach. You carefully collect sand and pat it into towers and walls. But then, someone comes along and secretly hides a sneaky surprise inside your castle - a bucket of water! When you touch it, the whole thing crumbles.

2. What are the three types of XSS attacks?

- Reflected XSS (Non-Persistent XSS): In this type of attack, the malicious script is injected into the web application and then reflected off the web server to the victim's browser.

- Stored XSS (Persistent XSS): In this type of attack, the malicious script is permanently stored on the target server, such as in a database, comment field, forum post, or any other user input field. 

- DOM-based XSS: This occurs when the client-side script writes data to the Document Object Model (DOM) in an unsafe way, allowing an attacker to inject malicious code that gets executed by the victim's browser.

3. If an attacker successfully exploits a XSS vulnerability, what malicious actions would they be able to perform?

1) Data Theft: 

- Stealing cookies and session tokens: These can be used to hijack your account and impersonate you on the targeted website.
- Capturing sensitive information: This includes login credentials, credit card details, personal data, and browsing history.
- Accessing browser storage: Attackers can steal passwords, saved forms, and other sensitive information stored in your browser.

2) Website Manipulation:

- Defacing the website: This involves changing the content or appearance of the website to spread misinformation, promote scams, or damage the website's reputation.
- Injecting malicious content: This can include phishing links, malware, or scripts that redirect users to malicious websites.
- Spreading the attack to other users: By exploiting stored XSS vulnerabilities, attackers can target other users who visit the compromised website.

3) User Control:

- Taking control of your browser: Attackers can use your browser to perform actions like downloading malware, sending spam emails, or participating in cyberattacks.

- Spying on your activity: Attackers can track your browsing history, keystrokes, and other actions on the website.

- Disrupting your experience: This can involve bombarding you with pop-ups, redirecting you to unwanted websites, or crashing your browser.

4.What are some security controls that can be implemented to prevent XSS attacks?

1) Input Validation and Sanitization:

- Validate user input: Ensure user-controlled data matches expected formats and values (e.g., only allow numbers in a numeric field).

2) Output Encoding:

- Encode data before displaying it: Convert special characters into their HTML or JavaScript entity equivalents to prevent script execution.

3) HTTP Headers:

- Set the X-XSS-Protection header: Instructs modern browsers to activate XSS filtering mechanisms.

- Set the Content-Security-Policy (CSP) header: Defines restrictions on what scripts, styles, and other resources can be loaded, mitigating XSS attempts.

4) Security Testing:

- Conduct regular penetration testing and vulnerability scans: Identify and address potential XSS vulnerabilities before attackers exploit them.

## Bookmark and Review

[Production Web Applications](https://www.rapid7.com/globalassets/_pdfs/whitepaperguide/rapid7-tcell-application-security-report.pdf) 

[Cross-site scripting](https://portswigger.net/web-security/cross-site-scripting) 

## Things I want know more about

- Different indicators you would look for in a SIEM like Splunk to detect a XSS attack.

