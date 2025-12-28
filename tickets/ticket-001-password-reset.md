# Ticket 001 – Password Reset

## Issue
User reports they forgot their domain password and cannot log in.

## Environment
- Domain: lab.local
- Domain Controller: DC01 (Windows Server 2022)
- Client: PC01 (Windows 10)
- User: lab\finance.user

## Root Cause
User entered an incorrect password and could not authenticate.

## Resolution
1. Logged into DC01 as LAB\Administrator
2. Opened Active Directory Users and Computers
3. Navigated to LAB-Users OU
4. Right-clicked user → Reset Password
5. Set a temporary password
6. Enabled “User must change password at next logon”

## Verification
- User successfully logged in to PC01
- User was prompted to change password
- Login completed successfully

