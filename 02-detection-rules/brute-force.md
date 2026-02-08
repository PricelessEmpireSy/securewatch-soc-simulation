# Brute Force Detection Rule

## Detection Logic

Trigger an alert when 3 or more failed login attempts occur  
from the same IP address within 5 minutes.

## Data Source

auth.log

## Severity

High

## Analyst Actions

1. Identify source IP  
2. Block the IP  
3. Force password reset  
4. Monitor for recurrence.
