# NETWORKWALKS-WK1-CYBERSECURITY-LABS-PRACTICE-USING-WIRESHARK
**Networkwalks Week 1 Wireshark SOC labs: packet analysis practice, TCP stream inspection, HTTP security, brute-force detection, and VoIP investigation.**

## Course Links

[![Wireshark Labs](https://img.shields.io/badge/Networkwalks-Wireshark_Labs-2563EB?style=for-the-badge)](https://networkwalks.com/wireshark/)
[![Identify Attacker IP](https://img.shields.io/badge/Lab_1-Identify_Attacker_IP-0F766E?style=for-the-badge)](https://networkwalks.com/wireshark-lab3/)
[![Follow TCP Stream 1](https://img.shields.io/badge/Lab_2-Follow_TCP_Stream_1-0F766E?style=for-the-badge)](https://networkwalks.com/wireshark-lab4/)
[![Follow TCP Stream 2](https://img.shields.io/badge/Lab_3-Follow_TCP_Stream_2-0F766E?style=for-the-badge)](https://networkwalks.com/wireshark-lab5/)
[![HTTP Credentials](https://img.shields.io/badge/Lab_4-HTTP_Credentials-7C3AED?style=for-the-badge)](https://networkwalks.com/wireshark-lab6/)
[![Brute Force Attacker](https://img.shields.io/badge/Lab_5-Brute_Force_Attacker-DC2626?style=for-the-badge)](https://networkwalks.com/wireshark-lab7/)
[![Call Scammer](https://img.shields.io/badge/Lab_6-Call_Scammer-F59E0B?style=for-the-badge)](https://networkwalks.com/wireshark-lab8/)
[![Submit Internship Work](https://img.shields.io/badge/Networkwalks-Internship_Submission-111827?style=for-the-badge)](https://networkwalks.com/submission/)




A portfolio record of my Week 1 SOC project for the Networkwalks internship. This project involved six browser-based Wireshark labs focused on analyzing network traffic.

PROJECT OVERVIEW

Each lab contains 10 tasks. The exercises provided practice with identifying suspicious activity, inspecting network conversations, and understanding information that can be exposed through network traffic.


USED OS 

Kali Linux VM

Training environment:**
Networkwalks browser-based labs  

**Tool practiced:** Wireshark  

## Labs and Results

### 1. Identify the Attacker’s IP

**Focus:** Find the attacker’s IP address in the traffic.

**Score:** 100
**Screenshot:** 
<img width="1366" height="768" alt="Screenshot_2026-10-28_10_58_56" src="https://github.com/user-attachments/assets/948019c6-22da-46cd-8ca8-804be4fc7c2d" />

---

### 2. Follow TCP Stream 1

**Focus:** Rebuild a conversation and inspect what was sent.

**Score:** 90 
**Screenshot:**  <img width="1366" height="768" alt="Screenshot_2026-10-28_10_53_02" src="https://github.com/user-attachments/assets/fb80d072-cd40-4c13-975d-83487653ef36" />

---

### 3. Follow TCP Stream, Part 2

**Focus:** Practise following a TCP stream and locating hidden data.

**Score:** 90 
**Screenshot:**<img width="1366" height="768" alt="Screenshot_2026-10-28_10_47_17" src="https://github.com/user-attachments/assets/c1f4c2f9-d0ab-4371-b41f-275ea86f0343" />



---

### 4. HTTP Plain Text Credentials

**Focus:** Identify usernames and passwords sent in clear text over HTTP.

**Score:** 90
**Screenshot:<img width="1366" height="768" alt="Screenshot_2026-10-28_10_43_21" src="https://github.com/user-attachments/assets/024f4aa7-808f-4b4b-948f-7a29220e091d" />



---

### 5. Catch the Brute Force Attacker

**Focus:** Spot repeated login attempts and identify who is guessing passwords.

**Score:** 100 
**Screenshot:**<img width="1366" height="768" alt="Screenshot_2026-10-28_10_34_55" src="https://github.com/user-attachments/assets/5cd5a7e6-4c74-4be4-9e84-edc45585ed4b" />


---

### 6. Catch the Call Scammer

**Focus:** Investigate a capture, review the call, and identify the scammer.

**Score:** 90  
**Screenshot:** <img width="1366" height="768" alt="Screenshot_2026-10-28_10_28_34" src="https://github.com/user-attachments/assets/81daf477-1be6-414d-b943-bce6ba7d7a0e" />


## Skills Practised

- Navigating packet captures in Wireshark
- Identifying IP addresses in network traffic
- Following TCP streams to reconstruct conversations
- Inspecting traffic for hidden data
- Recognizing clear-text credentials in HTTP traffic
- Identifying repeated login attempts associated with brute-force activity
- Reviewing VoIP traffic and audio evidence

## Skills Acquired

- A more structured approach to inspecting network traffic
- Practice connecting packet-level observations to a security question
- Improved familiarity with Wireshark’s stream-following workflow
- Greater awareness of how unencrypted protocols can expose sensitive information
- Practice recognizing patterns that may indicate suspicious activity

## Lessons Learned

- Packet captures can contain useful evidence about communications and suspicious behavior.
- Following a TCP stream can make a conversation easier to understand than reviewing individual packets alone.
- Credentials sent over unencrypted HTTP may be visible in captured traffic.
- Repeated login attempts can be a clue that password guessing is taking place.
- Network traffic should only be tested or captured in environments you own or have permission to assess.
- Screenshots and notes should be reviewed for passwords, tokens, personal information, and unrelated traffic before sharing.


