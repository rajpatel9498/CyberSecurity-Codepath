# Pentesting
Time spent: 8 hours spent in total

Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

Username Enumeration
Insecure Direct Object Reference (IDOR)
SQL Injection (SQLi)
Cross-Site Scripting (XSS)
Cross-Site Request Forgery (CSRF)
Session Hijacking/Fixation
Each version of the site has been given two of the six vulnerabilities. 
(In other words, all six of the exploits should be assignable to one of the sites.)


# Green

Vulnerability #1: Cross-Site Scripting
![](xss_green.gif)
Attacker can inject an XSS in their feedback form.
Injected XSS Command:
<script>alert('Raj found the XSS!');</script>
This XSS runs once the account holder checks their feedback page

Vulnerability #2: Username Enumeration
![](username.gif)
As you can see from above, the Green Website has the Username Enumeration error where the failure to login message differs for the Username that exists vs doesn't exist.
The "failure" class is applied an bold style in css while "failed" class doesn't.

# Red

