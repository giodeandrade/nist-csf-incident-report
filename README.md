# NIST CSF Incident Response Simulation

## Objective

This project was completed as part of the **Google Cybersecurity Certificate - Course 3: Connect and Protect: Networks and Network Security**, specifically Module 4: *Use the NIST Cybersecurity Framework to respond to a security incident*.

The activity simulated a cybersecurity incident in which a company experienced a Distributed Denial of Service (DDoS) attack. The objective was to analyze the incident and apply the NIST Cybersecurity Framework (CSF) to structure the response and recovery process, while identifying gaps in protection and planning for future resilience.

### Skills learned

- Applied the five NIST CSF functions (Identify, Protect, Detect, Respond, Recover) in a real-world scenario.
- Developed analytical thinking in the context of cybersecurity incident handling.
- Gained experience creating incident response and recovery plans.
- Strengthened understanding of DDoS attacks and mitigation strategies.
- Improved documentation and communication skills for incident reporting.

### Tools used

- NIST Cybersecurity Framework (CSF)
- Incident analysis and reporting documentation
- Network security configuration planning tools
- Intrusion Detection and Prevention Systems (IDS/IPS) concepts

## Steps

### Summary

A DDoS attack targeted the organization’s network, causing a two-hour outage. The attack was executed using a flood of ICMP packets, exploiting a misconfigured firewall that lacked proper rules to block such traffic. Network services were unavailable during the incident. The response team blocked the malicious traffic, prioritized restoration of critical services, and implemented long-term mitigation measures including firewall reconfiguration and deployment of network monitoring tools.

---

### Identify

- **Attack Type:** Distributed Denial of Service (DDoS) via ICMP flood.
- **Impacted Systems:** Internal network and services relying on external connectivity.
- **Vulnerability:** A firewall was improperly configured, allowing unrestricted ICMP traffic.
- **Associated Risks:** Loss of availability, productivity disruption, potential reputational damage.

---

### Protect

- Developed and enforced proper firewall rules to restrict ICMP traffic.
- Established internal procedures for secure firewall configuration.
- Conducted staff training on basic network security protocols.
- Implemented a plan to regularly audit network device configurations.

---

### Detect

- Integrated network monitoring software to track traffic anomalies.
- Enabled real-time alerts for unusual ICMP traffic or usage spikes.
- Deployed IDS/IPS solutions to detect and log suspicious traffic patterns.
- Established routine log analysis and anomaly detection procedures.

---

### Respond

- Contained the attack by blocking ICMP traffic and temporarily disabling non-essential services.
- Investigated the source and nature of the traffic to identify potential attackers.
- Updated firewall rules and network configurations.
- Informed stakeholders and documented response steps and findings.
- Conducted a post-incident review to assess effectiveness and improve response plans.

---

### Recover

- Restored critical services in a prioritized manner.
- Verified system and data integrity post-incident.
- Implemented long-term controls including IDS/IPS policies and updated firewall configurations.
- Documented the incident and created a knowledge base for future reference.

---

### Reflections / Notes

This incident response simulation reinforced the importance of proactive network security measures and regular auditing of configurations. Applying the NIST Cybersecurity Framework provided structure and clarity throughout the incident lifecycle, from identification through recovery. The exercise improved both technical and strategic skills essential for handling real-world cybersecurity threats.
