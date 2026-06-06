# Detection Logic and Threat Hunting

## Detection Logic

Detection logic is a rule that generates alerts when suspicious activity occurs.

Example:

IF User Added To Domain Admins
THEN Generate Alert

Example:

IF More Than 10 Failed Logins Within 5 Minutes
THEN Generate Brute Force Alert

## Threat Hunting

Threat Hunting is the proactive search for malicious activity even when no alerts exist.

Example:

No Alerts Generated
↓
Analyst Searches For Recently Created Accounts
↓
backup_admin Found

## Why Threat Hunting Matters

Threat Hunting helps identify attacks that may have been missed by detection systems.

It is especially useful for discovering False Negatives.

## Common Threat Hunting Questions

* Were new accounts created?
* Were users added to privileged groups?
* Was MFA disabled?
* Were logs cleared?
* Were unusual logins observed?

## Key Difference

Detection Logic:

* Generates alerts
* Reactive

Threat Hunting:

* Searches for threats proactively
* Can discover missed attacks
