# Introduction
There are eight security domains, or categories, identified by CISSP. Uses:  
- Organize daily tasks;  
- Identify gaps;  
- Establish security posture.  
    - Ability to manage defense of critical assets and data and react to change.

## 01) Security Risk and Management
Focused on defining:
- Security goals and objectives
    - Can reduce risks to critical assets and data (like PII, or personally identifiable information).  
- Risk mitigation
    - Right procedures and rules in place to quickly reduce the impact of a risk like a breach.  
- Compliance
    - Primary method used to develop an organization's internal security policies, regulatory requirements,
    and independent standards.
- Business continuity
    - Ability to maintain everyday productivity by establishing risk disaster recovery plans.
- Legal regulations
    - Following rules and expectations for ethical behavior to minimize negligence, abuse, or fraud. 

Information security (InfoSec) is related to this domain.
- Set of processes established to secure information.   
- An organization may use playbooks and implement training as a part of their security and risk management program, based on their needs and perceived risk. 
There are many InfoSec design processes, such as:
- Incident response  
- Vulnerability management  
- Application security  
- Cloud security  
- Infrastructure security  

Ex.: a security team may need to alter how personally identifiable information (PII) is treated in order to adhere to the European Union's General Data Protection Regulation (GDPR).

## 02) Asset Security
Focused on securing digital and physical assets. Also related to storage, maintenance, retention, and destruction of data.
- Assets such as PII or SPII should be handled and protected, whether stored on a computer, transfered over a network, or pshysically collected.  
- Orgs need to have policies and procedures that ensure data is properly stored, maintained, retained, and destroyed.  
    - Ex.: Oversee the destruction of hard drives to make sure that they're properly disposed of.   
Related to security analists. 


## 03) Security Architecture and Engineering 
Focused on optimizing data security by ensuring effective tools, systems, and proccesses are in place to protect
an org's assets and data.
- One of the core concepts: shared responsability.
    - All individuals within an org take an active role in lowering risk and maintaining both physical and virtual security.  
    - By having policies that encourage users to recognize and report security concerns, many issues can be handled quicly and effectively.  
Related to security architects and engineers.
Additional design principles related to this domain, which are discussed later in the program, include:
- Threat modeling  
- Least privilege  
- Defense in depth  
- Fail securely  
- Separation of duties  
- Keep it simple  
- Zero trust  
- Trust but verify  

Ex.: the use of a security information and event management (SIEM) tool to monitor for flags related to unusual login or user activity that could indicate a threat actor is attempting to access private data.

## 04) Communications and Network Security
Focused on managing and securing physical networks and wireless communications.

## 05) Identity and Access Management (IAM)
Focused on access and authorization to keep data secure by making sure users follow established policies to control and manage assets.
Ex.: if everyone at a company is using the same adm login, there's no way to track who has access to what data. In a breach, separate valid user activity from the threat actor would be impossible.
There are four main components:
- Identification
    - A user verifies who they are by providing a user name, an access card, or biometric data.
- Authentication
    - The verification proccess to prove a person's identity, as enter a password or PIN.
- Authorization
    - Takes place after a user's identity has been confirmed and relates to their level of access, which depends on the role in the org.
- Accountability
    - Monitoring and recording user actions, like login attempts, to prove systems and data are used properly.

Principle of least privilege: granting only the minimal access and authorization required to complete a task.  
Ex.:  a cybersecurity analyst might be asked to ensure that customer service representatives can only view the private data of a customer, such as their phone number, while working to resolve the customer's issue; then remove access when the customer's issue is resolved.


## 06) Assessment and Testing
Focused on conducting:
- Security control testing  
- Collecting and analyzing data  
- Security audits to monitor risks, threats, and vunerabilities   
This involves:
- Examining org goals and objectives  
- Evaluating if the controls being used actually achieve those goals. 
- Find vunerabilities via pentest.   

## 07) Security Operations
Focused on conducting investigations and implementing preventative measures.  
Requires a sense of urgency.  
If there's an active attack: mitigate -> prevent it from escalating futher -> forensic investigation.  
Digital forensic: identify when, how, and why the breach occurred.

This includes using strategies, processes, and tools such as:
- Training and awareness  
- Reporting and documentation  
- Intrusion detection and prevention  
- SIEM tools   
- Log management  
- Incident management  
- Playbooks  
- Post-breach forensics  
- Reflecting on lessons learned  

## 08) Software Development Security
Focused on secure coding practices, guidelines used to create secure apps and services.  
Each phase of software development lifecycle undergoes security reviews.  
