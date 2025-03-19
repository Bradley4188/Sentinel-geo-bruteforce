# 🌍 Honeypot Attack Tracker with Azure Sentinel  

## 🚀 Project Overview  
This project sets up a live **honeypot** on a **Windows 10 Pro Virtual Machine** to attract and monitor real-world **RDP brute-force attacks** from across the globe. The honeypot is connected to **Azure Sentinel** (SIEM) for real-time threat detection and analysis.  

A custom **PowerShell script** is used to:  
- Extract attacker IP addresses from event logs.  
- Look up geolocation information (country, city, coordinates).  
- Plot the attacks on the **Azure Sentinel Map** for easy visualization of global attack patterns.  

---

## 🌟 Key Features  
✅ Live monitoring of RDP brute-force attacks.  
✅ Geolocation lookup and mapping using PowerShell.  
✅ Real-time analysis with Azure Sentinel.  
✅ Insights into global attack sources and patterns.  

---

## 🎯 Goal  
To gain insight into global attack behavior, enhance threat detection skills, and demonstrate the power of Azure Sentinel for security monitoring.  

---

## 🛠️ Technologies Used  
- **Azure Sentinel** (SIEM)  
- **Windows 10 Pro**  
- **PowerShell**  
- **Geolocation API**  
- **VirtualBox**  

---

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/krRFrK5.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
