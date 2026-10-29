# NETWORKWALKS-SAMUEL-B084N-WEEK1-WIRESHARK-SOC-LABS
Week 1 extra project documenting hands-on Wireshark traffic analysis and SOC investigation exercises completed during the NetworkWalks Cybersecurity Internship.


# NetworkWalks Wireshark SOC Labs — Week 1 Extra Project

## Project Overview

This repository documents my hands-on Wireshark traffic analysis exercises completed as a Week 1 extra project during the NetworkWalks Cybersecurity Internship.

The exercises focused on inspecting network traffic, analyzing communication protocols, identifying suspicious authentication activity, and investigating traffic patterns relevant to Security Operations Center (SOC) workflows.

## Objectives

- Understand how to inspect and filter network packets using Wireshark.
- Analyze TCP conversations using Follow TCP Stream.
- Identify suspicious hosts and investigate network traffic.
- Examine HTTP traffic and understand the risks of transmitting sensitive information in plaintext.
- Investigate repeated FTP authentication failures.
- Explore SIP signaling and RTP traffic in a VoIP communication session.

## Tools Used

- Wireshark
- Wireshark display filters
- TCP Stream analysis
- Protocol and packet inspection

## Labs and Investigations

### Lab 3: Identify the Attacker's IP

**Objective:** Investigate captured network traffic to identify a potentially malicious host.

**What I practised:**
- Inspecting packet source and destination addresses.
- Filtering traffic by IP address.
- Using packet evidence to investigate suspicious activity.

**Evidence:** 
![](Screenshot%20(480).png)
![](Screenshot%20(484).png)
![](Screenshot%20(489).png)


### Lab 4: Follow TCP Stream — Part 1

**Objective:** Reconstruct a TCP conversation to inspect the exchanged application data.

**What I practised:**
- Following TCP streams.
- Examining client requests and server responses.
- Understanding how packet-level evidence reveals application activity.

**Evidence:** 
![](Screenshot%20(499).png)
![](Screenshot%20(500).png)
![](Screenshot%20(504).png)


### Lab 5: Follow TCP Stream — Part 2

**Objective:** Investigate HTTP traffic to locate a hidden note within an HTML page.

**What I practised:**
- Reconstructing HTTP conversations.
- Inspecting HTML response content.
- Identifying information exposed through HTML comments.

**Security lesson:** Comments and debugging information left in published web pages can expose information that should not be public.

**Evidence:** 
![](Screenshot%20(509).png)
![](Screenshot%20(513).png)
![](Screenshot%20(518).png)


### Lab 6: HTTP Plain Text Credentials

**Objective:** Examine HTTP traffic for credentials transmitted without encryption.

**What I practised:**
- Inspecting application-layer traffic.
- Understanding the risks associated with plaintext authentication.
- Recognizing why encrypted communication, such as HTTPS, is important.

**Evidence:**
![](Screenshot%20(526).png)
![](Screenshot%20(528).png)
![](Screenshot%20(529).png)


### Lab 7: Catch the Brute Force Attacker

**Objective:** Investigate repeated FTP login attempts in a packet capture.

**What I practised:**
- Filtering FTP traffic.
- Examining authentication requests and server responses.
- Recognizing failed authentication responses.
- Understanding how repeated failures can indicate password-guessing activity.

**Evidence:** 
![](Screenshot%20(535).png)
![](Screenshot%20(540).png)
![](Screenshot%20(542).png)


### Lab 8: Catch the Call Scammer

**Objective:** Investigate a VoIP session by examining signaling and media traffic.

**What I practised:**
- Filtering SIP and RTP packets.
- Examining SIP call setup and termination messages.
- Identifying RTP packets carrying voice media.

**Evidence:** 
![](Screenshot%20(549).png)
![](Screenshot%20(550).png)
![](Screenshot%20(556).png)
![](Screenshot%20(557).png)


## Key Takeaways

Through these exercises, I strengthened my understanding of:

- Network traffic filtering and packet inspection.
- TCP session reconstruction.
- HTTP security and information exposure.
- Authentication failure analysis.
- SIP signaling and RTP media traffic.
- Using network evidence to support security investigations.

## Relevance to SOC Analysis

These exercises helped me practise foundational skills used in security monitoring and incident triage, including identifying suspicious activity, inspecting protocol behavior, and using packet evidence to support investigation findings.

## Project Evidence

Screenshots documenting the investigations are included in the repository.


## Acknowledgements

Thanks to NetworkWalks and the internship instructor for the learning opportunity and practical exercises.

**Project:** Week 1 Extra Project  
**Focus:** Wireshark Traffic Analysis | Network Security | SOC Fundamentals
