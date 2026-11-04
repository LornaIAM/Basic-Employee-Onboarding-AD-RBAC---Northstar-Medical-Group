# Basic Employee Onboarding (AD)(RBAC)

## Northstar-Medical-Group
Active Directory infrastructure rebuild for a fictional company called “Northstar Medical Group”. Includes domain setup, organizational structure, user provisioning, RBAC implementation, and incident resolution

## Problem Statement
* Northstar Medical Group was using a third party MSP (Managed Service Provider) to handle their infrastructure and run their IT operations. At the time Northstar Medical Group was smaller and did not have the bandwidth to handle these processes. Fast forward, the Group has grown and along with their growth the strain on their infrastructure and IT Operations with the MSP had become more egregiously apparent. The Active Directory was completely unorganized; there was no structure to adding users which consistently caused inconsistent access and permissions for the employees. The outdated manual processes used caused great delay and even more confusion for the access management of the workforce users of the hospital. These issues then cascaded down to causing departments to become very unorganized. Along with the internal issues the onboarding issues were also a disaster. These problems then put Northstar Medical Group in a very vulnerable position to potentially face non-compliance with HIPAA regulations that could expose the facility to federal enforcement actions and substantial civil monetary penalties from the Office for Civil Rights (OCR).


## Solution Overview
* My approach was to replace Northstar's manual, ad hoc process with a purpose-built Active Directory environment organized by department and governed by role-based access. I built the NMG.com domain on a Windows Server 2019 domain controller, then designed four department OUs (Finance, HR, IT, Operations), each with a matching security group. The new environment now provides a centralized system where the users are managed in an organized and efficient way. I created the Security Groups to control the workforce access and then provisioned each user by placing them in their respective departments OUs and Security Group. This fixed Northstar's previous security issue, where users had access that did not match their job duties. I also simulated a mock ticket where a user was misprovisioned and which caused the user to have the wrong level of access.


## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built the Active Directory NMG.com domain from scratch
* Designed four department OUs with matching Security Groups and provisioned all 15 users into them using a flat RBAC model
* Diagnosed and resolved a mis provisioned-user incident (NMG-0047) and documented the fix with screenshots
* I was able to document my steps to solving the mock ticket so that anyone who reads my issue can fully understand the issue and the solution. This process can also be included in policies in the future to anyone having the same issue
