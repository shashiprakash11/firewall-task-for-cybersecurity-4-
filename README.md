# firewall-task-for-cybersecurity-4-

# Windows Firewall Configuration – Cybersecurity Task

This repository contains the work I did as part of a cybersecurity exercise where I learned how to configure and test firewall rules on **Windows Defender Firewall with Advanced Security**.

---

## 🔹 What I Did
- Opened the Windows Firewall management console (`wf.msc`).
- Created an **Outbound Rule** to block traffic on port **80 (HTTP)**.
- Tested the rule by trying to access HTTP-only websites such as [neverssl.com](http://neverssl.com), which failed to load after applying the rule.
- Added an **Inbound Rule** to allow traffic on port **22 (SSH)** for demonstration purposes.
- Finally, removed the test block rule to restore normal network access.

---

## 🔹 Tools Used
- Windows Defender Firewall  
- Web browser (for testing)  

---

## 🔹 Key Learnings
- Understood the difference between **inbound** (traffic coming in) and **outbound** (traffic going out) rules.  
- Practiced blocking and allowing traffic on specific ports.  
- Verified how firewall rules directly affect network connectivity.  

---

## 🔹 Screenshots
I've added the screeshots showing the rules i've created and the test results.

---

## 🔹 Outcome
This task gave me hands-on experience with Windows Firewall. I learned how to create, test, and manage rules to control network traffic effectively. It also reinforced my understanding of how firewalls secure systems by filtering data at the port level.
