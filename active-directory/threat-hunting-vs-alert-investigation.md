# Threat Hunting vs Alert Investigation

## Alert Investigation

Alert Investigation occurs when a security alert is generated and an analyst investigates the activity.

Example:

User Added To Domain Admins
↓
SIEM Alert Generated
↓
SOC Investigation

## Threat Hunting

Threat Hunting is the proactive search for malicious activity even when no alert exists.

Example:

No Alerts Generated
↓
Analyst Searches For New Accounts
↓
backup_admin Found

## Why Threat Hunting Matters

Threat Hunting helps identify attacks that may have been missed by detection systems.

It is especially useful for finding False Negatives.

## Key Difference

Alert Investigation:

* Reactive
* Starts with an alert

Threat Hunting:

* Proactive
* Starts with a hypothesis or suspicion
