# How to manage risk and some common threat actors.

## Risk management

- Primary goal of orgs: protect assets  
- Asset: an item perceived as valuable to an organization.  
- Digital includes: Social Security Numbers (SSNs), or unique national identification numbers assigned to individuals, dates of birth, bank account numbers, mailing addresses.  
- Physical includes: payment kiosks, servers, desktop computers, office spaces.  
- Common strategies to manage risks:  
    - Acceptance: accepting a risk to avoid disrupting business continuity  
    - Avoidance: creating a plan to avoid the risk altogether  
    - Transference: transferring a risk to a third party to manage  
    - Mitigation: lessening the impact of a known risk  
- Risk management processes based on widely accepted frameworks (ex.: NIST RME, HITRUST)

## Most common threats and vulnerabilities

Risk is anything that can impact the CIA of an asset. Basic formula for determining the level of risk equals the likelihood of a threat. Some factors affects it:
- External risk: anything outside the org that has potential to harm organizational assets.  
    - Ex.: threat actors attempting to gain access to private information.  
- Internal risk: current or former employee, vendor, or trusted partner who poses a security risk  
- Legacy systems: old systems that might not be accounted for or updated, but can still impact assets, such as workstations or old mainframe systems.  
    - Ex.: an org might have an old vending machine that takes credit card payments or a workstation that is still connected to the legacy accounting system.  
- Multiparty risk: vulnerabilities and threats that arise when a security incident in one organization impacts multiple other organizations.  
- Software compliance/licensing: software that is not updated or in compliance, or patches that are not installed in a timely manner  
https://owasp.org/www-community/attacks/

## Vulnerabilities

Weakness that can be exploited by a threat. Some include:
- ProxyLogon: a pre-authenticated vulnerability that affects the Microsoft Exchange server. A threat actor can complete a user authentication process to deploy malicious code from a remote location.  
- ZeroLogon: a vulnerability in Microsoft’s Netlogon authentication protocol (a way to verify a person’s identity).  
- Log4Shell: allows attackers to run Java code on someone else's computer or leak sensitive information.  
- PetitPotam: affects Windows New Technology Local Area Network (LAN) Manager (NTLM). Allows a LAN-based attacker to initiate an authentication request.  
- Security logging and monitoring failures: insufficient logging and monitoring capabilities that result in attackers exploiting vulnerabilities without the organization knowing it  
- Server-side request forgery: allows attackers to manipulate a server-side application into accessing and updating backend resources. It can also allow threat actors to steal data.  
