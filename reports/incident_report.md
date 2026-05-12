# Security Incident Investigation Report

## Incident ID

SOC-2026-001

## Detection Summary

Multiple failed authentication attempts followed by successful administrative access were observed from source IP 10.0.0.14.

## Severity

High

## Indicators of Compromise

- Repeated failed login activity
- Successful access after brute-force sequence
- Encoded PowerShell execution
- Unauthorized privilege escalation

## Attack Timeline

09:00 Failed login burst  
09:00 Authentication success  
09:15 Privilege escalation  
09:18 Encoded PowerShell execution

## Analyst Assessment

Likely credential compromise followed by privilege abuse.

## Recommendations

- Disable credentials
- Enforce MFA
- Block suspicious IP
