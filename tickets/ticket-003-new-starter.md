# Ticket 003 – New Starter Setup

## Issue
New employee joined the Finance department and requires system access.

## Environment
- Domain: lab.local
- Domain Controller: DC01 (Windows Server 2022)
- Client: PC01 (Windows 10)
- User: lab\new.finance

## Root Cause
New user account had not yet been provisioned in Active Directory.

## Resolution
1. Logged into DC01 as LAB\Administrator
2. Created new user account in LAB-Users OU
3. Set a temporary password and enforced password change at first logon
4. Added user to GG-Finance security group

## Verification
- User successfully logged in
- User was prompted to change password
- Finance network drive was mapped automatically
- User could access Finance share but not HR share
