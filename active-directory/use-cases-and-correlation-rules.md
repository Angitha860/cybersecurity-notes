# Use Cases and Correlation Rules

## What is a Use Case?

A use case is a specific attack scenario that a security team wants to detect.

Examples:

* Brute Force Detection
* Account Compromise Detection
* Privilege Escalation Detection
* Data Exfiltration Detection

## What is Correlation?

Correlation is the process of combining multiple events to identify suspicious activity.

Example:

Password Changed
↓
MFA Disabled
↓
New Admin Account Created

Together these events may indicate an account compromise.

## Example Correlation Rule

IF:

* MFA Disabled
* backup_admin Created
* User Added To Domain Admins

THEN:
Generate High Severity Alert

## Why Correlation Matters

A single event may appear normal.

Multiple suspicious events occurring together can reveal attacker activity.

## Key Takeaway

Correlation helps SOC analysts identify attack patterns rather than investigating isolated events.
