# SOC Severity Levels

## Why Severity Levels Matter

SOC analysts receive many alerts every day.

Severity levels help prioritize which alerts should be investigated first.

## Low Severity

Low-risk or potentially benign activity.

Examples:

* Single failed login
* Login at an unusual time

Action:

* Monitor
* Investigate if additional indicators appear

## Medium Severity

Suspicious activity that requires investigation.

Examples:

* Multiple failed logins followed by a successful login
* Possible brute force activity

Action:

* Investigate
* Gather additional evidence

## High Severity

Strong indicators of compromise.

Examples:

* MFA Disabled
* User Added To Domain Admins
* Creation of suspicious administrative accounts

Action:

* Immediate investigation
* Consider containment

## Critical Severity

Potential organization-wide impact.

Examples:

* Domain Admin Compromise
* Ransomware Activity
* Large-Scale Data Exfiltration

Action:

* Immediate response
* Containment and escalation

## Key Takeaway

Severity is determined by potential impact and risk, not simply by the number of events.
