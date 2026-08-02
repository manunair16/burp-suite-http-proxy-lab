# Burp Suite HTTP Proxy Lab

## Objective

Understand how Burp Suite intercepts, modifies, forwards, and drops HTTP requests while analyzing communication between a web browser and a web server.

## Lab Environment

- Attacker: Kali Linux 2026
- Target: Kali Linux 2017
- Web Server: Apache2
- Database: MariaDB
- Vulnerable Application: DVWA
- Browser: Firefox
- Platform: Oracle VirtualBox

## Tools Used

- Burp Suite Community Edition
- Apache2
- MariaDB
- DVWA
- Firefox

## Activities Performed

- Configured Burp Suite as an intercepting proxy.
- Intercepted GET and POST HTTP requests.
- Forwarded intercepted requests.
- Dropped HTTP requests.
- Modified intercepted HTTP requests before forwarding them to the web server.
- Reviewed HTTP History to analyze GET requests used for page navigation and POST requests used for user authentication within DVWA.

## Skills Demonstrated

- HTTP Request Analysis
- Web Proxy Configuration
- Request Interception
- HTTP Request Modification
- Client-Server Communication Analysis

## Outcome

Successfully demonstrated the use of Burp Suite Proxy to intercept, inspect, modify, forward, and drop HTTP requests in a controlled DVWA lab environment.
