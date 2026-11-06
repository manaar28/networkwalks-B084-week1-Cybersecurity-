# Week 1 - Cybersecurity Lab Setup | NetworkWalks B084

## Overview
This repository documents my Week 1 task for NetworkWalks Cybersecurity Internship.
I explored the official Kali Linux platform and setup lab environment.
## What I Did:

I have successfully setup a Cybersecurity testing lab environment on my Laptop as per task requirements.
During setup I faced an error but I fixed it and continued my lab setup.
### My Lab Setup Details:

- I used VirtualBox latest version as my base platform
- I setup Kali Linux as my attacking/hacker machine
- I configured the network in subnet 10.0.0.0/24
- I created and used NATNetwork with 10.0.0.0/24
- I enabled clipboard & file drag/drop in Virtual Machine settings (Bidirectional)
- I enabled shared folders and shared /downloads folder from host machine
- I configured Kali Linux IP Address as 10.0.0.2/24
- I verified Kali Linux has full Internet access
# WK1 - Wireshark Project | NetworkWalks

I completed 6 Wireshark labs:

1. Identify the Attacker's IP - Found attacker IP via port scan analysis
2. Follow TCP Stream 1 - Reconstructed internal chat
3. Follow TCP Stream Part 2 - Found hidden data in HTTP traffic
4. HTTP Plain Text Credentials - Found username and password sent over HTTP
5. Catch the Brute Force Attacker - Detected FTP brute force attack
6. Catch the Call Scammer - Replayed VoIP call via SIP/RTP and found card details

## Key Learnings:
- HTTP exposes sensitive data, HTTPS is a must
- Repeated failed logins + success = brute force compromise
- VoIP calls need SRTP with TLS for SIP to stay private

#NetworkWalks #Wireshark #CyberSecurity
