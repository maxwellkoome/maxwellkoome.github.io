---
layout: single
title: "Lab Challenges"
permalink: /lab-challenges/
author_profile: true
---

### 🧪 Challenge 1 – Port Scanning & Banner Grabbing

**Problem:** Identify open ports and detect vulnerable services  
**Approach:** Used Nmap for scan and Netcat for banners  
**Tools:** Nmap, Netcat  
**Screenshots:**  
*![Screenshot](/assets/images/lab1.png)*

**Lessons Learned:**  
- Use `-sV` for service version
- Port 22 sometimes open but secured with Fail2Ban

---

### 🔍 Challenge 2 – SQL Injection Lab

**Problem:** Extract data from a vulnerable login form  
**Approach:** Manual payload testing on input fields  
**Tools:** Burp Suite, Firefox  
**Lessons Learned:** Importance of input sanitization
