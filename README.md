# NETWORKWALKS-WK1-CYBERSECURITY-LABS-PRACTICE-USING-WIRESHARK
**Networkwalks Week 1 Wireshark SOC labs: packet analysis practice, TCP stream inspection, HTTP security, brute-force detection, and VoIP investigation.**


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

**Score:** _Add score_  
**Screenshot:** 


---

### 5. Catch the Brute Force Attacker

**Focus:** Spot repeated login attempts and identify who is guessing passwords.

**Score:** _Add score_  
**Screenshot:** _Add screenshot_

---

### 6. Catch the Call Scammer

**Focus:** Investigate a capture, review the call, and identify the scammer.

**Score:** _Add score_  
**Screenshot:** _Add screenshot_

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

## Evidence

Add screenshots for each lab in the corresponding section above. Before publishing, check that each image shows only information you are allowed to share and does not reveal credentials or other sensitive data.

## Course Links

- [Networkwalks Wireshark labs](https://networkwalks.com/wireshark/)
- [Identify the Attacker’s IP](https://networkwalks.com/wireshark-lab3/)
- [Follow TCP Stream 1](https://networkwalks.com/wireshark-lab4/)
- [Follow TCP Stream, Part 2](https://networkwalks.com/wireshark-lab5/)
- [HTTP Plain Text Credentials](https://networkwalks.com/wireshark-lab6/)
- [Catch the Brute Force Attacker](https://networkwalks.com/wireshark-lab7/)
- [Catch the Call Scammer](https://networkwalks.com/wireshark-lab8/)
- [Internship submission page](https://networkwalks.com/submission/)

