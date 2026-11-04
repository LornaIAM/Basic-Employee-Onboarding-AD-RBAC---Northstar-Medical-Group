# Basic Employee Onboarding (AD)(RBAC)

## Northstar-Medical-Group
Active Directory infrastructure rebuild for a fictional company called “Northstar Medical Group”. Includes domain setup, organizational structure, user provisioning, RBAC implementation, and incident resolution

## Problem Statement
Northstar Medical Group was using an MSP (Managed Service Provider) to handle their infrastructure and run their IT operations. At the time Northstar Medical Group was smaller and did not have the bandwidth to handle these processes. Fast forward, the Group has grown and along with their growth the strain on their infrastructure and IT Operations with the MSP had become more egregiously apparent. The Active Directory was completely unorganized; there was no structure to adding users which consistently caused inconsistent access and permissions for the employees. The outdated manual processes used caused great delay and even more confusion for the access management of the workforce users of the hospital. These issues then cascaded down to causing departments to become very unorganized. Along with the internal issues the onboarding issues were also a disaster. These problems then put Northstar Medical Group in a very vulnerable position to potentially face non-compliance with HIPPA regulations that could expose the facility to federal enforcement actions and substantial civil monetary penalties from the Office for Civil Rights (OCR).


## Solution Overview
My first approach was to replace Northstar's manual, ad hoc process with a purpose-built Active Directory environment organized by department and governed by role-based access. I built the NMG.com domain on a Windows Server 2019 domain controller, then designed four department OUs (Finance, HR, IT, Operations), each with a matching security group. The first problem this solved was providing a centralized system where everything and everyone could be housed in an organized and efficient method and securing the onboarding process. 

With the Active Directory domain in place, my next priority was solved because it created an efficient user provisioning security so that each user has only the access that they should have based on their job duties. The Security Groups for each Organizational Unit I created implemented the user provisioning because it confirms that each role has the correct access and permissions within their respective departments. Lastly, I focused on creating a more streamline process for redundant and sometimes massive tasks such as onboarding. 

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
* Built NMG.com domain from scratch
* [Add your second key accomplishment here]
* [Add your third key accomplishment here]
