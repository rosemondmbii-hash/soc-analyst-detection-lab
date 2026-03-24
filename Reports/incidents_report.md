# Incident Report

## Incident Summary
Suspicious activities were detected including brute force login attempts, unauthorized access, and file deletion within the domain environment.

---

## Severity Level
High

---

## Affected Systems
- Domain environment
- File storage system

---

## Timeline of Events
- 22:30 – Multiple failed login attempts detected (admin account)
- 22:35 – Successful login after repeated failures
- 22:37 – Unauthorized file access observed
- 22:40 – Sensitive file deletion detected

---

## Findings
- Multiple failed login attempts followed by successful login
- Sensitive file accessed and deleted
- Guest account access observed

---

## Indicators of Compromise (IOCs)
- Suspicious IP Address: 192.168.1.10
- Target Account: admin
- Unusual login time
- File deletion activity

---

## Analysis
The activity pattern is consistent with a brute force attack leading to unauthorized access.  
Post-compromise actions indicate potential data exfiltration or malicious intent.

---

## Actions Taken
- Blocked suspicious IP address
- Disabled compromised account
- Forced password reset
- Enabled multi-factor authentication (MFA)
- Initiated log monitoring for further anomalies

---

## Recommendations
- Implement account lockout policy
- Enforce strong password policies
- Enable continuous monitoring via SIEM
- Conduct user access review
- Apply least privilege principle

---

## Conclusion
The incident highlights gaps in authentication controls and monitoring. Immediate remediation and improved security controls are required to prevent recurrence.
