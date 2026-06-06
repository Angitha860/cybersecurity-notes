# True Positive, False Positive, and False Negative

## True Positive

A True Positive occurs when a security alert correctly identifies malicious activity.

Example:

* MFA Disabled
* New Admin Account Created
* Investigation confirms account compromise

Result:

The alert was valid and malicious activity occurred.

## False Positive

A False Positive occurs when a security alert is generated, but the activity is actually legitimate.

Example:

* Impossible Travel Alert
* User was connected through a corporate VPN

Result:

No malicious activity occurred.

## False Negative

A False Negative occurs when malicious activity takes place, but no alert is generated.

Example:

* Attacker creates a new admin account
* Attacker steals files
* SIEM generates no alert

Result:

The attack is missed by the detection system.

## Why False Negatives Are Dangerous

False Negatives are dangerous because security teams may never become aware of the attack, allowing attackers to remain undetected.

## Summary

* True Positive = Alert + Real Attack
* False Positive = Alert + No Attack
* False Negative = No Alert + Real Attack
