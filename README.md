# CyberSecurity-Codepath

Assignment -7,8

Step: 1) Changed the wordpress version to 4.1
      2) Run vagrant up
      3) Back in Kali VM, run "wpscan --url http://wpdistillery.vm"
      4) We will find exploits
Xploits:

1) Vulnerability Name or ID : USER Enumeration
![](ue.gif)
Summary: This exploit allowes user to enumerate through different user names, I tested with multiple non-existing usernames, and extisting usernames. Upon knowing the valid username or usernames, it is easier to perfrom bruteforce attack.
Vulnerability types: User enumeration
Tested in version: 4.2



 
