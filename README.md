# CTF-Challenge-The-Ghost-in-the-Badge-Reader

Name: The Ghost in the Badge Reader <br>
Category: Forensics + OSINT <br>
Difficulty: Medium-Hard <br>
Estimated Solve Time: 45-240 minutes depending on skill level <br>
  1. Experienced = 45-90 minutes <br>
  2. Intermediate = 90-180 minutes <br>
  3. Beginner = 180-240 minutes <br>
<br>
Challenge Narrative: <br>
An executive at AeroSecure Corp reported that their physical badge was stolen, but the thief was caught on camera trying to enter the server room and failing. However, the internal network was still breached that same night. Your job is to analyze the Badge Access Logs and the Executive's social media presence to find the Flag. <br>
<br>
Learning Objectives: <br>
- Understanding side-channel attacks and covert data exfiltration <br>
- Log analysis and identifying anomalies in large datasets <br>
- Hex to ASCII conversion and data encoding techniques <br>
- OSINT techniques using social media profiles <br>
- Recognizing and bypassing red herrings <br>
<br>
🔐 The Attack Vector: <br>
<br>
The challenge teaches a realistic side-channel attack where: <br>
- Attacker cloned a maintenance badge (less security scrutiny) <br>
- Used badge reader error logs as a covert data exfiltration channel <br>
- Encoded flag in hex within intentional CRC_ERROR entries <br>
- Left a "calling card" in a location the victim frequents <br>
<br>
🚀 Quick Start: <br>
<br>
- Download All Challenge Files to get everything <br>
- Choose your deployment method (static files, CTFd, or web server) <br>
- Use the progressive hint system if players get stuck <br>
