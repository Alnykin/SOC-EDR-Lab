# SOC Endpoint Detection and Response Lab Project

The SOC EDR Lab aimed to simulate a real-world Security Operations Center workflow within an attack-and-defend lab environment. The objective was to emulate adversary behavior and develop detection and response logic using LimaCharlie EDR.


## Skills Developed

* Setup and configured LimaCharlie EDR to collect telemetry across Windows and Linux systems.

* Integrated Sigma detection rules to improve sensor visibility into threat activity.

* Generated and deployed a Sliver C2 payload from a Linux machine to a Windows host.

* Launched SC2 sessions to simulate real-world credential theft techniques such as LSASS memory dumping and post-exploitation activity.
  
* Conducted privilege escalation within an active C2 session to analyze attacker techniques.

* Detected credential dumping activity by monitoring access to sensitive processes such as lsass.exe and analyzing related telemetry.

* Deployed and tested custom Detection & Response (D&R) rules to alert on and automatically contain malicious behavior.

* Conducted threat hunting by analyzing process trees, command-line arguments, network connections, file hashes, and parent-child relationships.

* Applied YARA rules to identify malicious artifacts and automate malware containment in key file directories.


## Tools 

LimaCharlie EDR 
Windows Sysmon 
Sigma Ruleset 
Sliver C2 Framework
Powershell
ProcDump 
VirusTotal 
YARA

# Key Outcomes

* Established and monitored an active C2 session to emulate attacker activity.
* Developed detection rules to identify credential dumping attempts.
* Created detection and response (D&R) rules to block malicious actions in real time.
* Implemented automated YARA scans to support proactive defense measures.

# Lessons Learned

* How attackers establish persistence, perform privilege escalation, and credential dumping.
* Leveraging EDR telemetry to design and implement custom detection rules.
* The use of Sigma and YARA rules in proactive threat defense.
* The full attack lifecycle, from implant deployment to detection and containment.
* How observed adversary techniques can be translated into actionable SOC detection logic.

# Walthrough

