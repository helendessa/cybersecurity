# Introduction

Open Web Application Security Project (OWASP): security principles useful to a cybersec analyst.

# Principles

- Minimize the attack surface area.  
    - All potential vulnerabilities that a threat actor can exploit.
        - Attack vectors: pathways attackers use to penetrate security defenses.
            - Ex.: pishing e-mails and weak passwords.  
    - What to do: disable software features, restrict who can access certain assets, or establish more complex passwords.
- Principle of least privilege.  
    - Making sure that users have the least amount of access required to perform their everyday tasks.  
    - Reason is to reduce the amount of damage a security breach can cause.  

- Defense in depth.  
    - Multiple security controls that address risks and threats in different ways.  
    - Ex.: password + MFA, firewalls, intrusion detect systems, permission settings that can be used to create multiple points of defense.

- Separation of duties.  
    - No one should be given so many privileges that they can misuse the system.
    - Prevent individuals from carrying out fraudulent or illegal activities.  

- Keep security simple.  
    - Unnecessarily complicated solutions should be avoided because they can become unmanageable.  
    - The more complex the security controls, the harder it's for people to work collaboratively.  

- Fix security issues correctly.  
    - Correct identify vulnerabilities and conduct tests to ensure that repairs are successful.  

# Additional OWASP security principles

- Establish secure defaults: the optimal security state of an app is its default state for users.  
- Fall securely: when a control fails or stop, it should do so by defaulting to its most secure option.  
    - Ex.: when a firewall fails it should simply close all connections and block all the new ones, rather than 
    start accepting everything.  
- Don't trust services: the org shouldn't explicitly trust that their partners' systems are secure.  
    - Ex.: if a third-party vendor tracks reward points for airline customers, the airline should ensure that the balance is accurate 
    before sharing that information with their customers.
- Avoid security by obscurity: the security of an app shouldn't rely on the source code secret.  
    - It should rely upon many other factors, including reasonable password policies, defense in depth, business transaction limits, solid network architeture,
    fraud and audit controls.  

