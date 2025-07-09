# Introduction
Before discussing tools further, let's briefly discuss logs, which are the source of data that the tools we'll cover are
designed to organize.

Log: a record of events that occur within an organization's systems.
    - Ex.: records of employees signing into their computers or accessing web-based services. 
    - Help security identify vulnerabilities and potential security breaches.

## Security Information and Event Management (SIEM) tools
An application that collects and analyzes log data to monitor critical activities in an organization.

- Collect real-time information.  
- Allow security analysts to identify potential breaches as they happen.  
- Reduce the amount of data an analyst must review by providing alerts for specific types of risks and threats.  
- Provide a series of dashboards that visually organize data into categories.  
- Collect data from mutiple places.    
- Analyze filtered events and patterns.  
- Incident analysis.  
- Search for threats.  
- Mittigate risks.  
- Differents hosts options (on-premise, cloud).  
- Ex.: Splunk Enterprise, Google's Chronicle.  

## Playbooks
A manual that provides details about any operation, such as how to respond to an acident.
- Guide analysts in how to handle a security task before, during, and after it has occurred.  
- Ensure that you are following proper protocols and procedures.  
- Can pertain to security or compliance reviews, access managemenet, etc.
- Ex.: forensics case:
    - Chain of custody: process of documenting evidence possession and control during an incident life-cycle.  
        - Document who, what, where, and why you have the collected evidence.  
        - Evidence must be kept safe and tracked.  
    - Protecting and preserving evidence: properly working with fragile and volatile data evidence.  
        - Order of volatility: sequence of outlining the order of data that must be preserved from first to last.  
            - Volatile data: data that may be lost if the device powers off.  
        - Improperly managed evidence can no longer be used.  
        - Priority: preserve the data.  

## Network protocol analyzer or packet sniffer
- Capture and analyze data traffic within a network.  
- Keeps a record of all data that a computer within a org's network encounters.  
- Ex.: Wireshark, tcpdump.  

