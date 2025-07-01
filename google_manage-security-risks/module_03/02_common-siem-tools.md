# Introduction 

Types of SIEM tools:
- Self-hosted: require organizations to install, operate, and maintain the tool using their own physical infrastructure, such as server capacity.  
    - Managed and maintained by the org's IT department  
    - Ideal when an org is required to maintain physical control over confidential data  
- Cloud-hosted: maintained and managed by the SIEM providers, making them accessible through the internet.  
    - Ideal for orgs that don't want to invest in creating and maintain their own infrastructure.  
- Hybrid solution: combination of both self and cloud-hosted
    - Ideal solution to leverage the benefits of the cloud while also maintaining physical control over confidential data.  

# Tools

- Splunk: data analysis platform.
    - Splunk Enterprise: provides SIEM tools. 
        - Self-hosted  
        - Used to retain, analyze, and search and org's log data to provide security info and alerts in real-time.  
    - Splunk Cloud: 
        - Cloud-hosted  
        - Used to collect, search, and monitor log data  
        - Helpful for orgs running hybrid or cloud-only enviroments
    - Dashboards:
        - Security posture
            - Displays the last 24h of an org's notable security-related events and trends  
            - Monitor and investigate potential threats in real time, such as suspicious network activity originating from a specific IP address. 
        - Executive summary
            - Analyzes and monitors the overall health of the organization over time.  
            - Provide high-level insights to stakeholders, such as generating a summary of security incidents and trends over a specific period of time.
        - Incident review
            - Identify suspicious patterns that can occur in the event of an incident  
            - Highlighting higher risk items that need immediate review by an analys  
            - Provides a visual timeline of the events leading up to an incident.
        - Risk analysis
            - Helps analysts identify risk for each risk object (e.g., a specific user, a computer, or an IP address)  
            - Shows changes in risk-related activity or behavior, such as a user logging in outside of normal working hours or unusually high network traffic from a specific computer  
            - Analyze the potential impact of vulnerabilities in critical assets   
            - Helps analysts prioritize their risk mitigation efforts.
- Google Chronical: 
    - Cloud-native
    - Designed to retain, analyze, and search data.  
    - Provides log monitoring, data analysis, and data collection  
    - Collect and analyze log data according to:
        - A specific asset  
        - A domain name  
        - A user  
        - An IP address  
    - Dashboards:
        - Enterprise insights
            - Highlights recent alerts  
            - Identify suspicious domain names in logs (indicators of compromise - IOCs)
            - Each result is labeled with a confidence score to indicate the likelihood of a threat  
            - Also provides a severity level that indicates the significance of each threat to he org  
            - Monitor login or data access attempts related to critical asset from unusual locations or devices  
        - Data ingestion and health
            - Shows the number of event logs, log sources, and success rates of data being processed  
            - Ensure that log sources are correctly configured and that logs are received without error  
            - Helps ensure that log related issues are addressed so that the security team has access to the log data they need.  
        - IOC matches
            - Indicates the top threats, risks, and vulnerabilities to the organization  
            - Observe domain names, IP addresses, and device IOCs over time in order to identify trends  
            - Focus to the highest priority threats  
            - Search for additional activity associated with an alert, such as a suspicious user login from an unusual geographic location.  
        - Main
            - A high-level summary of information related to the organization’s data ingestion, alerting, and event activity over time  
            - Access a timeline of security events—such as a spike in failed login attempts, to identify threat trends across log sources, devices, IP addresses, and physical locations.
        - Rule detections
            - Statistics related to incidents with the highest occurrences, severities, and detections over time  
            - List of all the alerts triggered by a specific detection rule, such as a rule designed to alert whenever a user opens a known malicious attachment from an email  
            - Help manage recurring incidents and establish mitigation tactics to reduce an organization's level of risk.
        - User sign in overview 
            - Information about user access behavior across the organization.  
            - A list of all user sign-in events to identify unusual user activity, such as a user signing in from multiple locations at the same time.   
            - Help mitigate threats, risks, and vulnerabilities to user accounts and the organization’s applications.


# More about cybersecurity tools

- Open-source: software built the public in a collaborative way  
    - Allow more customization  
    - Often free and can be user friendly  
    - The source code is readily available to users, as well the training material that accompanies them  
    - These sources allows users to modify and improve project materials  
    - Ex.: Linux, Suricata (open-source network analysis and threat detection software)

- Proprietary: developed and owned by a person or company.  
    - Users typically pay a fee for usage and training  
    - The owners are the only ones who can access and modify the source code  
    - Users need to wait for updates to be made to the software, and sometimes they might have to pay a fee for those updates  
    - Generally allows users to modify a limited number of features to meet individual and organizational needs.  

