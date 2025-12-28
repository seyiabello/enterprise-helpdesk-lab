# Ticket 002 – Account Lockout

## Issue
User reports they cannot log in after multiple failed login attempts.

## Environment
- Domain: lab.local
- Domain Controller: DC01 (Windows Server 2022)
- Client: PC01 (Windows 10)
- User: lab\finance.user

## Root Cause
Account was locked due to multiple incorrect password attempts triggering the account lockout policy.

## Resolution
1. Logged into DC01 as LAB\Administrator
2. Opened Active Directory Users and Computers
3. Navigated to LAB-Users OU
4. Opened user account properties
5. Unlocked the user account

## Verification
- User successfully logged in to PC01 after account was unlocked
