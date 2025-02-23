# Blue Team SOC HomeLab
Elastic Defend Detections

## Objective

I created and configured this Elastic Detection HomeLab to establish a controlled environment for simulating and detecting threats. I've had some exposure to Kibana and Elastic in the past but I wanted more practical application. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system and generate test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen my understanding of network security, attack patterns, and defensive strategies. Also, to have some fun ;)

### Skills Showcased

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.
- Practical experience building and configuring a functional SIEM using the Elastic Stack.
- Proficiency in log parsing and data enrichment.
- Expertise in creating dashboards and visualizations in Kibana for threat detection.
- Ability to set up alert rules and threat detection logic based on log analysis.

### Tools Used

- Elastic Stack (Elasticsearch, Kibana, Logstash, Beats) for log ingestion and analysis.
- Network analysis tools (Wireshark) for capturing and examining network traffic.
- Suricata for network intrusion detection.
- Zeek for network security monitoring.
- Telemetry generation tools to create realistic network traffic and attack scenarios.
- Various Linux command line tools for log manipulation and analysis.

### Notable Steps
Installation of Elastic EDR Agent on Kali VM.

![Screenshot 2025-02-22 174626](https://github.com/user-attachments/assets/df9d28c0-8a68-423b-8962-4f25baf21d43)

Successful install. Service Running.

![Screenshot 2025-02-22 173631](https://github.com/user-attachments/assets/39f081e5-c629-4b72-9cbe-504393ef4e58)

Configured nmap Detection Rule.

![Screenshot 2025-02-22 174204](https://github.com/user-attachments/assets/760e07d8-be37-493f-b0a8-52cb77203605)

Triggering rule with nmap scans.

![Screenshot 2025-02-22 174410](https://github.com/user-attachments/assets/0cc9e51b-501b-4c0a-bb29-0ca19fc1eb4c)

Dashboard of events.

![Screenshot 2025-02-22 175903](https://github.com/user-attachments/assets/faeb5eba-8afb-4fff-8a46-e5e7c41de41f)






