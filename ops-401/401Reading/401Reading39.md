## Readings 39: SQLi with Burp Suite, WebGoat

- Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

- Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

- Understanding SQL Injection, Identification and Prevention

1. What is SQL injection?

- SQL injection (SQLi) is a critical security vulnerability that attackers exploit to gain unauthorized access to a website's database. It occurs when an attacker injects malicious code into a seemingly harmless input field on a web application. 

2. Can you give an example of how a hacker could use SQL injection to gain unauthorized access?

- A website with a login page where users can enter their username and password to access their accounts. The website's backend code interacts with a SQL database to authenticate users.

3. What are some ways to prevent SQL injection attacks on a web server?

- Use Parameterized Queries: Instead of dynamically constructing SQL queries by concatenating strings with user input, use parameterized queries (also known as prepared statements).

- Input Validation and Sanitization: Validate and sanitize all user input before using it in SQL queries. 

- Least Privilege Principle: Follow the principle of least privilege by granting the minimum necessary permissions to database users and limiting their access to sensitive data and operations.

- Database Firewall and WAF: Implement a database firewall or a web application firewall (WAF) to monitor and filter incoming SQL queries for suspicious patterns or potential injection attempts. 

## Reference

[Understanding SQL Injection](https://www.varonis.com/blog/sql-injection-identification-and-prevention-part-1/) 

## Things I want to know more about

- How to Inject SQL commands into input fields to manipulate the behavior of SQL queries.
