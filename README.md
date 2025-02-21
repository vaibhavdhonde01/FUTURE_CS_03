# FUTURE_CS_03
# Analyze and Respond to a Simulated Cybersecurity Incident

🚨 Incident Response Report - DoS Attack on Metasploitable 2 🚨
📌 Overview
This repository contains an Incident Response Report documenting the analysis and mitigation of a Denial-of-Service (DoS) attack performed using the Slowloris tool. The target system was a web server running on Metasploitable 2 (Oracle VM VirtualBox).

The report provides details on:

Attack execution and analysis using Wireshark
Root cause identification
Mitigation steps taken
Preventive security measures

📁 Files in This Repository
FUTURE_CS_03(incident response).pdf – Full incident response report
Wireshark Packet Capture Logs – Network traffic logs from the attack
Screenshots – Before and after attack evidence
🔍 Incident Summary
📌 Attack Details
Target: Web server (Port 80 - HTTP)
Attack Type: Denial-of-Service (DoS)
Threat Actor: Simulated attack using Slowloris
Analysis Tool: Wireshark
🔍 Root Cause
The attack exploited the lack of timeout handling for incomplete connections, allowing Slowloris to exhaust the web server’s connection pool.

🛠️ Mitigation Steps
✅ Terminated attacker’s connection
✅ Restarted the web server
✅ Blocked the attacker's IP using a firewall
✅ Implemented rate limiting
✅ Configured timeout settings

🔐 Recommendations for Prevention
🔧 Technical Measures
Deploy a Web Application Firewall (WAF)
Set connection timeouts for idle HTTP requests
Implement rate limiting on web servers
Use reverse proxies (e.g., Nginx) to filter traffic
Enable load balancing to distribute traffic
📜 Administrative Measures
Establish an Incident Response Plan
Conduct regular penetration testing
Train staff on security awareness
Keep servers patched and updated
📢 Conclusion
This report showcases a realistic cybersecurity incident response workflow, covering detection, analysis, and mitigation of a DoS attack. By following the recommendations, organizations can enhance their resilience against similar threats.

🚀 For cybersecurity enthusiasts and professionals, this repository serves as a reference for handling DoS attacks using forensic tools like Wireshark!

🔗 Connect
📌 Author: Vaibhav
📌 Contact: [vaibhavdhonde78@gmail.com]

Feel free to ⭐ this repo and contribute by adding insights or suggestions! 🚀

