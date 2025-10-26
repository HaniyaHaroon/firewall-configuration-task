# Firewall Configuration using UFW on Kali Linux

## Objective
To configure and test basic firewall rules using UFW to block and allow network traffic.

## Steps Performed
1. Installed and enabled UFW.
2. Listed current firewall rules.
3. Added a rule to block inbound traffic on port 23 (Telnet).
4. Tested the rule by trying to connect via Telnet (connection failed).
5. Added a rule to allow SSH on port 22.
6. Verified the rules applied correctly.
7. Removed the test Telnet block rule.
8. Disabled UFW
9. Documented commands and rule status.

## Commands Used
See 'commands_used.txt' file.

## Firewall Explanation
UFW acts as a packet filter for inbound and outbound traffic.  
By defining rules, we can restrict or permit traffic based on port numbers and protocols.  
Blocking Telnet (port 23) and allowing SSH (port 22) ensures secure remote management.

## Screenshots
Screenshots are available in the `/screenshots` folder showing rule creation, testing, and deletion.

## Outcome
Learned how to:
- Configure UFW firewall on Linux
- Add, test, and remove rules
- Understand how firewalls filter network traffic
