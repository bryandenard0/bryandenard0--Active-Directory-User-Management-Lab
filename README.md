# Active Directory Home Lab: User Management

## Project Summary

This lab demonstrates basic user account management within Active
Directory. The objective was to create and configure a new user account,
apply initial password policies, and simulate a standard first‑login
password reset scenario commonly used in enterprise environments.

This exercise reinforces core identity and access management tasks
performed by IT support and systems administrators.

------------------------------------------------------------------------

## Environment

-   Windows Server
-   Active Directory Domain Services (AD DS)
-   Active Directory Users and Computers (ADUC)

------------------------------------------------------------------------

## Objectives

-   Create a new Active Directory user account
-   Configure initial login credentials
-   Enforce password reset at first login

------------------------------------------------------------------------

## Implementation Steps

### Created New User Account

Using Active Directory Users and Computers, a new domain user was
created with the following details:

**Name:** Bruce T. Wayne\
The account was placed in the appropriate default container for standard
users.
<img width="1918" height="1079" alt="Creating a new user" src="https://github.com/user-attachments/assets/e3043c60-3695-4586-a6b1-f2d9f6b6e4be" />

### Configured Initial Password

An initial password was assigned to the account during creation. The
option requiring the user to change their password at first login was
enabled to align with standard security practices.
<img width="1919" height="1079" alt="Set Password for New User" src="https://github.com/user-attachments/assets/71928231-5775-4539-8788-d72aa8b353ce" />

### Enforced First Login Password Reset

The account was configured so that the password expires after the first
successful login. This ensures that only the end user knows their
permanent credentials and maintains compliance with common
organizational security policies.
<img width="1919" height="1079" alt="Set Password for New User" src="https://github.com/user-attachments/assets/a110909b-7e35-4755-86de-1aa2d44a66ec" />

------------------------------------------------------------------------

## Validation

-   Confirmed user account appears in Active Directory
-   Verified account properties and password settings
-   Confirmed "User must change password at next logon" setting is
    enabled

------------------------------------------------------------------------

## Skills Demonstrated

-   Active Directory user provisioning\
-   Identity and access management basics\
-   Password policy enforcement\
-   Administrative account configuration\
-   ADUC navigation and management

------------------------------------------------------------------------

## Use Case

This lab simulates a typical helpdesk or system administrator task:
provisioning a new employee account and enforcing secure credential
setup for first‑time access.

------------------------------------------------------------------------

## Future Enhancements

-   Create security groups and assign permissions
-   Add user to department-based Organizational Units
-   Apply Group Policy for password and lockout policies
-   Test login from domain-joined workstation
-   Automate user creation with PowerShell

------------------------------------------------------------------------

## Author

Home Lab Project -- Active Directory User Management
