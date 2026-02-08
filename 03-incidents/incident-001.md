# Incident 001 – Brute Force Attack

## Detection Source

Rule: Brute Force Detection  
Log: auth.log

## Description

Multiple failed login attempts detected from IP 203.0.113.45 targeting admin account.

## Impact

High risk of credential compromise.

## Status

Contained

## Evidence

- auth.log shows repeated failures within 5 minutes
