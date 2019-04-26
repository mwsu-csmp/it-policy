# Remote Access Tools Policy

## Overview
Remote desktop software, also known as remote access tools, provide a way for computer users
and administrators to access work computer systems from home, and vice
versa. Examples of such software include LogMeIn, GoToMyPC, VNC (Virtual Network
Computing), and Windows Remote Desktop (RDP). While these tools can save significant time
and money by eliminating travel and enabling collaboration, they also provide a back door into
the Phoenix Lab that can be used for theft of, unauthorized access to, or
destruction of assets. As a result, only approved, monitored, and properly controlled remote
access tools may be used on Phoenix Lab computer systems.

## Purpose
This policy defines the requirements for remote access tools used in the Phoenix Lab.

## Scope
This policy applies to remote access where communication originates outside of the Phoenix Lab
network (such as elsewhere on the Missouri Western network or the Internet).

## Policy
All remote access tools used to communicate with Phoenix Lab systems must comply with the following 
policy requirements.

### Remote Access Priviliges 
  - Privileges for remote access will be assigned to security groups, not individual users.
  - All CSMP faculty user accounts will be members of a security group which allows remote access.
  - Student user accounts will only be assigned to a separate security group for student remote
    access.  
  - Students must be sponsored by a faculty member to receive remote access priviliges.
  - Student accounts with remote access priviliges must be annotated as such.
  - All students accounts must be removed from the student remote access security group at the end
    of each semester.
  - At the end of each semester, review members of the faculty remote access security group and 
    remove any user accounts of faculty members who are no longer with CSMP.

### Remote Access Methods
  - All remote access must be configured to require the use of a username and password.
  - Only protocols that utilize encryption of credentials (such as SSH or HTTPS) shall be used.
  - All remote connections must be made directly to individual hosts within the Phoenix Lab.
  - No user shall attempt to create a VPN connection or network bridge to the Phoneix Lab.

### Security Posture 
  - Phoenix labs hosts will be configured to only allow inbound connection on known ports that 
    require encryption of credentials.
  - All Phoenix Lab hosts must be updated with patches and antivirus protection at leastly monthly.
  - At no time shall Phoenix Lab hosts be dual-homed.
  - Any Phoenix Lab hosts that do not require remote access must have remote access disabled.

## Remote Access Tools
Remote access tools must use standards-based protocols (i.e., SSH, HTTPS, etc).  

## Policy Compliance
## Compliance Measurement
The Phoenix Lab owner will verify compliance to this policy through various methods, including but
not limited to, periodic walk-thrus, video monitoring, business tool reports, internal and external
audits, and feedback to the policy owner.
## Exceptions
Any exception to the policy must be approved in advance.
## Non-Compliance
An employee or student found to have violated this policy or the MWSU user agreement may be subject to disciplinary action.

