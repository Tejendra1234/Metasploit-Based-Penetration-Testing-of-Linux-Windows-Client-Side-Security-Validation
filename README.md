# **Metasploit-Based Penetration Testing of Linux and Windows Systems with Client-Side Security Validation**

# 

## **Project Overview**



This project demonstrates hands-on penetration-testing exercises performed using the Metasploit Framework in a controlled virtual lab environment. The project covers network reconnaissance, service enumeration, Linux and Windows server-side exploitation, client-side security validation, and Web Delivery testing. It applies concepts from Week 8 Network Penetration Testing training and independently performed practical exercises. Screenshots and supporting notes are maintained to document the testing process and observed results.



### **Project Objectives**



The primary objective of this project is to understand and apply the Metasploit Framework in an authorized lab environment. The project focuses on learning module discovery, auxiliary enumeration, network reconnaissance, service identification, and controlled exploitation of vulnerable lab systems. It also aims to develop practical experience with session handling, target verification, evidence collection, security impact analysis, and defensive remediation recommendations.



### **Lab Environment**



The testing environment uses Kali Linux as the primary penetration-testing system, with Metasploitable 2 and an additional Linux target used in the CSEC/Marlinspike practical for Linux-side exercises. A Windows virtual machine is used for Windows exploitation, client-side security validation, and Web Delivery exercises. Oracle VirtualBox provides the virtualization environment, while the Metasploit Framework is the primary testing framework and Nmap is used for network reconnaissance and service enumeration. Exact virtual machine configurations, IP addresses, network adapter settings, and software versions should be recorded where verified by the collected evidence.



## **Practical Exercises**



#### **1. Lab Setup**



The initial practical involved preparing the virtual lab environment and examining the virtual machines and their network configurations. Screenshots were collected to document the VM inventory, network adapter settings, IP addresses, and connectivity between the testing system and the targets.



#### **2. Reconnaissance and Service Enumeration**



Network reconnaissance was performed against authorized lab targets to identify reachable systems, open ports, running services, and potential vulnerabilities. Nmap was used for host discovery, service detection, and vulnerability-related enumeration. The collected results helped identify services and targets for subsequent practical exercises.



#### **3. Auxiliary Module Enumeration**



The Metasploit Framework was used to explore relevant auxiliary modules and inspect their available options. Service-related enumeration included FTP checks and module discovery. This exercise helped develop familiarity with the Metasploit search workflow and the process of selecting appropriate modules for authorized lab testing.



#### **4. Linux Server-Side Testing**



Linux-side practical exercises were performed against vulnerable lab systems using the Metasploit Framework. The exercises included Samba, UnrealIRCd, and ProFTPD in the CSEC/Marlinspike environment. The workflow involved inspecting modules, reviewing module options, performing authorized exploitation attempts, interacting with the resulting sessions, and verifying target access where successful.



#### **5. Windows Server-Side Testing**



Windows testing included an MS17-010/EternalBlue practical in the authorized virtual lab. The exercise involved identifying the relevant module, reviewing the target's vulnerability status, conducting the lab exploitation exercise, and verifying the resulting Meterpreter session. Basic filesystem navigation was also performed to demonstrate session interaction with the Windows target.



#### **6. Client-Side Security Validation**



The client-side practical involved an HTA-based exercise in the controlled Windows lab environment. The workflow included configuring the lab server, initiating the test from the Windows target, verifying the resulting session, examining privilege-related security controls, and performing basic file interaction. The exercise also included observing the effects of firewall configuration changes and security event-log operations within the lab. These actions highlight the importance of maintaining endpoint protections and preserving security logs during incident investigation.



#### **7. Web Delivery**



The Web Delivery practical was performed in the controlled lab environment using the Metasploit Framework and a Python HTTP server as part of the delivery workflow. The exercise involved configuring the module, generating the delivery command, preparing the test file, accessing it from the Windows lab target, and verifying the reported session outcome. The practical provided experience with delivery workflows and reinforced the importance of preventing unauthorized execution of untrusted files.



#### **Project Structure**



The project directory contains separate folders for documentation, notes, and practical evidence. The `docs` folder is intended for project documentation, the `notes` folder contains the transcript coverage checklist, and the `evidence` folder contains screenshots organized into subfolders for lab setup, reconnaissance, auxiliary enumeration, Linux testing, Windows testing, and client-side exercises. Web Delivery evidence is currently stored in the client-side lab folder.



#### **Evidence Collection and Verification**



Screenshots and supporting notes are used to document the practical exercises, including virtual machine configuration, network connectivity, service enumeration, module inspection, exploitation results, session verification, and target interaction. Findings should be included only when supported by the available evidence. A vulnerability detection result should not automatically be treated as proof of successful exploitation. Each exercise should distinguish between successfully verified results, unsuccessful attempts, observations, and activities that could not be independently reproduced.



#### **Security Considerations and Recommendations**



The practical exercises demonstrate the importance of maintaining secure configurations across Linux and Windows systems. Recommended defensive measures include applying security patches, removing or disabling unnecessary services, restricting exposed network services, enforcing least-privilege access controls, and maintaining properly configured host firewalls and endpoint protection. Organizations should also monitor suspicious processes and network activity, restrict the execution of untrusted files, investigate unexpected privilege changes, and protect security logs against unauthorized modification or deletion.



#### **Project Limitations**



The results apply to the specific lab environments and software configurations used during the practical exercises. The findings should not be generalized to all systems running the same services or operating systems. Screenshots and command outputs support only the activities they directly demonstrate. This project is intended as a practical learning exercise and does not replace a comprehensive professional penetration test or an independently validated security assessment.



#### **Conclusion**



This project provided hands-on experience with the Metasploit Framework, network reconnaissance, auxiliary enumeration, controlled Linux and Windows exploitation, session handling, target verification, client-side security validation, and Web Delivery testing. The exercises reinforced the importance of understanding vulnerabilities, validating results, collecting appropriate evidence, assessing potential security impact, and documenting defensive remediation measures.



#### **Disclaimer**



This project was performed for educational purposes within authorized virtual lab environments. All testing was intended to remain within the designated lab scope. The techniques and observations documented in this project are intended to support cybersecurity learning, security validation, and defensive awareness.

