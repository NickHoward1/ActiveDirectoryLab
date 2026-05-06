<h1>SOC Analyst Pathway Portfolio (TryHackMe)</h1>

<h2>Description</h2>

<b>This project showcases the work I’ve completed as part of the SOC Analyst pathway on TryHackMe. It includes a range of screenshots from the labs and challenges I’ve worked through, along with clear explanations of the tools I used and the approaches I took.<br/>
<b><br/>
<b>The aim is to demonstrate not just what I’ve done, but how I’ve done it highlighting my thought process, the skills I’ve developed, and the knowledge I’ve built up along the way. Altogether, this serves as evidence of my hands-on experience and my readiness to step into a Junior SOC Analyst role.

<br />

<h2>Languages</h2>

- <b>Search Processing Language</b> 

<h2>Environments Used </h2>

- <b>Cloud-Hosted Virtual Lab Environment</b> - Linux or Windows machines set up for specific scenarios.

<h2>Tools </h2>
Wireshark, Nmap, Splunk, Elastic Stack

<h2>Wireshark: PCAP's and filters</h2>

<p align="left">
 
<img src= "https://github.com/NickHoward1/ActiveDirectoryLab/blob/f2e1bf63ee4da7b2978ba4d3a949e646a290e7ea/Screenshot%202026-05-06%20at%2007.32.02.png" width="300" height="300" />     <img src= "https://github.com/NickHoward1/ActiveDirectoryLab/blob/f2e1bf63ee4da7b2978ba4d3a949e646a290e7ea/Screenshot%202026-05-06%20at%2007.32.02.png" width="300" height="300" />

<h2>Project walk-through: Potential Phishing Attack</h2>

<p align="left">
 <br/>
The screenshots below show the SOC simulation environment and the tools I used to triage this alert. I started by assigning the alert to myself and reviewing the description to understand why it was triggered.

From there, I investigated further by opening the SIEM and using Splunk to check the relevant logs. I also took the flagged link from the alert and analysed it in a sandbox environment using a VM (IP/URL analysis), which came back clean.

Based on the log analysis and link check, I was able to confirm this was a false positive with no escalation required. I documented my findings in a report and then closed the case. <br/>

<a href="https://ibb.co/spvfVPgP"><img src="https://i.ibb.co/V0W1qNLN/Screenshot-2026-04-27-at-10-58-08.png" alt="Screenshot-2026-04-27-at-10-58-08" border="0"></a>

 <a href="https://ibb.co/NdJfZs2J"><img src="https://i.ibb.co/pBMNJxjM/Screenshot-2026-04-27-at-14-27-29.png" alt="Screenshot-2026-04-27-at-14-27-29" border="0"></a>

 <a href="https://ibb.co/RTNkC1bg"><img src="https://i.ibb.co/TM1xHZ2w/Screenshot-2026-04-27-at-14-15-53.png" alt="Screenshot-2026-04-27-at-14-15-53" border="0"></a>


<br />

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
