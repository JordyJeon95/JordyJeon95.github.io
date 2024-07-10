---
title:  "Application Security - 1"
excerpt: "OWASP TOP 10"

categories:
  - Security
tags:
  - [Application, Security, Firewall, OWASP, TOP10]

toc: true
toc_sticky: true
 
date: 2024-07-09, Tue., 20:38

last_modified_at: 2024-07-09, Tue., 20:38
---
# OWASP [OPEN WEB APPLICATION SECURITY PROJECT]
<br>
## 🚀 Introduction to OWASP Top 10
### About OWASP..
#### OWASP Top 10 - 2021
***
OWASP TOP 10 LIST
- A01: Broken Access Control
- A02: Cryptographic Failures
- A03: Injection
- A04: Insecure Design
- A05: Security Misconfiguration
- A06: Vulnerable and Outdated Components
- A07: Identification and Authentication Failures
- A08: Software and Data Integrity Failures
- A09: Security Logging and Monitoring Failures
- A10: Server-Side Request Forgery
***

#### **A01:Broken Access Control**
***

Restrictions on what authenticated users are allowed to do are often not properly enforced.  
Attackers can exploit these flaws to access unauthorized functionality and/or data, such as access other users' accounts, view sensitive files, modify other users' data,
change access rights, etc.

***

#### **A02: Cryptographic Failures**
***

Failure to sufficiently protect data in transit or rest from exposure to unauthorized individuals.  
This can include poor usage of encryption or the lack of encryption all together.

***

#### **A03: Injection**
***

Injection flaws, such as SQL, NoSQL, OS, and LDAP injection, occur when untrusted data is sent to an interpreter as part of a command or query.  
The attacker's hostile data can trick the interpreter into executing unintended commands or accessing data without proper authorization.

***

#### **A04: Insecure Design**
***

Failing to build security into the application early in the design process through a process of threat modelling, and secure design patterns and principles.

***

#### **A05: Security Misconfiguration**
***

Security misconfiguration is the most commonly seen issue.  
This is commonly a result of insecure default configurations, incomplete or ad hoc configurations, open cloud storage, misconfigured HTTP headers, and verbose
error message containing sensitive information.  
Not only must all operating systems, frameworks, libraries, and applications be securely configured, but they must be patched/upgraded in a timely fashion.

***

#### **A06: Vulnerable and Outdated Components**
***

Components, such as libraries, frameworks, and other software modules, run with the same privileges as the application.  
if a vulnerable component is exploited, such an attack can facilitate serious data loss or server takeover.  
Applications and APIs using components with known vulnerabilities may undermine application defenses and enable various attacks and impacts.

***

#### **A07: Identification and Authentication Failures**
***

Application functions related to authentication and session management are often implemented incorrectly, allowing attackers to compromise passwords, keys, 
or session tokens, or to exploit other implementation flaws to assume other users' identities temporarily or permanently.

***

#### **A08: Software and Data Integrity Failures**
***

Code or infrastructure that does not properly protect against integrity failures like using plugins from untrusted sources that can lead to a compromise.

***

#### **A09: Insufficient Logging and Monitoring**
***

Insufficient logging and monitoring, coupled with missing or ineffective integration with incident response, allow attackers to further attack systems,
maintain persistence, pivot to more systems, and tamper, extract, or destroy data.  
Most breach studies show time to detect a breach is over 200 days, typically detected by external parties rather than internal processes or monitoring.

***

#### **A10: Server-Side Request Forgery**
***

SSRF occurs when an application fetches resources without validating the destination URL.  
This can be taken advantage of by an attaker who is able to enter a destination of their choosing.

***
```
😀 Welcome to Jordy's personal study blog.  
If you notice any errors or inaccuracies, your comments would be greatly appreciated.
```