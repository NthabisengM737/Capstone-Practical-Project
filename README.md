# Capstone-Practical-Project

## Day in the Life of an IT Support Specialist
Name: Nthabiseng Mklhehlani 
 Date: 20 March 2026

 ---

 ## Overview
This project simulates real-world tasks performed by an IT Support Specialist in a small business environment. It demonstrates practical skills in system setup, networking, server configuration, security implementation, and troubleshooting using a Windows-based system.
 
---
## Objectives
* Configure and manage a Windows system

* Create and manage user accounts with proper permissions

* Set up and troubleshoot a local network

* Deploy a local web server and intranet page

* Implement basic security measures

* Simulate and resolve common IT issues

* Document all processes clearly

---

## Technologies & Tools Used

* Windows Operating System

* Command Prompt (CLI tools)

* Internet Information Services (IIS)

* Windows Defender (Firewall & Antivirus)

* Basic Networking Tools (ipconfig, ping, tracert)

---

## Project Tasks

### 1. System Setup
* Installed and configured WIndows OS

* Renamed machine to IT-SUPPORT-PC01

* Verified system specifications

### 2. User Management 
* Created two users:
  * admin_user (Administrator)
  * employee_user (Standard User)
* Implemented  Role-Based Access Control (RBAC) 
* Tested restricted access for standard users

 ### 3. Networking
* Configured and verfied network settings

* Performed diagnostics using:
  * ipconfig
  * ping
  * tracert
* Tested internet connectivity

### 4. Server Setup
* Installed and configured a local web server using IIS
* Created a custom intranet webpage
* Hosted the page on http://localhost

### 5. File Sharing 
* Created a shared folder ( C:\CompanyFiles)
* Configured permissions:
  * Admin: Full access 
  * Employee: Read-only
* Tested access control

### 6. Security Implementation
* Enabled Windows Firewall 
* Performed antivirus scan
* Applied strong password and access restrictions

### 7. Troubleshooting 

| Problem | Cause | Solution | Outcome |
|--------|------|---------|--------|
| No internet connectivity | IP misconfiguration or disabled network adapter | Renewed IP using `ipconfig /renew` and enabled adapter | Connection restored |
| Access denied to shared folder | Incorrect user permissions | Updated sharing and security permissions | Access granted based on role |
| Application installation failure | Standard user lacks admin rights | Logged in as admin_user to install software | Installation successful |

---
## Network Diagram 
A simple network diagram was created to illustrate the system setup, including the PC, router, local server, and shared resources.

---
## What I learned 
This project strengthened my ability to:
* Configure and manage systems in a real-world scenario
* Troubleshooting common IT issues effectively 
* Implement security best practices
* Document technical processes clearly

## Future Improvements 
* Add remote access configuration 
* Implement advanced firewall rules
* Automate tasks using PowerShell
* Expand server capabilities (e.g., database integration)
