**Incident Response Scenario:**

Local IT in Spain are complaining on a massive files corruption in few shared folders, they 
mentioned there is a strange suffix added to all files. The files can't be open no more by anyone.

• Write what can these symptoms imply on <br>
• What would be your recommended investigation plan to confirm/confute your original <br>
assumption and to find the root cause for the incident? <br>
• What would be your recommended containment action plan? <br>
• What would be your recommended recovery plan?<hr>


**MY ANALYSIS AND REPORT**

**Deduction from Symptoms:**<br>
	Massive file corruption and added suffix indicates the presence of a malware. <br>
	Inability to open files further proves it is a ransomware. i.e. A type of malware that encrypts (locks) users’ files without their permission.
  
**Recommended Investigation Plan**<br>
Check if there is any popup requesting users’ to make payment before assessing those files. This is the typical end goal of ransomware attacks: to receive money before unlocking files.
Then, to find the root cause of the problem, check system logs and event records of users in the IT department for recent file downloads or suspicious links clicked.
This is because malware is usually transmitted via malicious files and links.

**Recommended Containment Plan**<br>
Devices that contain these shared folders should be contained and isolated from the organization’s network.
Further analysis and investigation should then be carried out to confirm the root cause of the incident, exact malware family type and likely threat actor/group involved from the TTP (Techniques, Tactics, and Procedures) used.

**Recommended Recovery Plan**<br>
	Update all software in the department and use trusted antivirus or antimalware programs.
Set up policies guiding sharing of files and links in the department, and further enforce effective security awareness training to all staff.
