# Log Sources

## What is a Log Source?

A log source is any system, application, or device that generates logs which can be collected and analyzed by a SIEM or security team.

Logs help analysts monitor activity, detect threats, and investigate incidents.

## Common Log Sources

### Windows Logs

Records system and security events on Windows systems.

Examples:

* Successful Logins (4624)
* Failed Logins (4625)
* Account Changes
* Group Membership Changes

### Application Logs

Records activity occurring within applications.

Examples:

* User Logins
* Password Resets
* File Uploads
* Application Errors

### Firewall Logs

Records network traffic that is allowed or blocked.

Examples:

* Blocked Connections
* Allowed Connections
* Port Scans

### VPN Logs

Records remote access activity.

Examples:

* VPN Login Success
* VPN Login Failure
* User Connection History

### Antivirus Logs

Records security detections.

Examples:

* Malware Detected
* File Quarantined
* Scan Results

### Active Directory Logs

Records user and group management activity.

Examples:

* User Created
* User Deleted
* Added To Domain Admins
* Password Changes

## Why Log Sources Matter

Different log sources provide different pieces of evidence during an investigation.

SOC analysts correlate logs from multiple sources to understand what happened during an attack.

## Key Takeaway

Log sources are the systems and applications that generate the logs used for monitoring, detection, and investigation.
