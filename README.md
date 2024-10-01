# SOC Setup Project: Enhanced Cybersecurity Monitoring and Response

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Implementation Details](#implementation-details)
  - [Day-by-Day Breakdown](#day-by-day-breakdown)
- [Conclusion](#conclusion)
- [License](#license)

## Project Overview
This project involves the implementation of a Security Operations Center (SOC) environment using the ELK Stack (Elasticsearch, Logstash, Kibana), Elastic Agents, and a ticketing system (osTicket) to enhance cybersecurity monitoring and incident response capabilities. The objective is to create a robust infrastructure for log collection, threat detection, and incident management.

## Technologies Used
- **ELK Stack**: Elasticsearch, Logstash, Kibana
- **Elastic Agent**: Unified agent for log collection
- **Fleet Server**: Centralized management for Elastic Agents
- **Sysmon**: System monitoring tool for Windows
- **Mythic C2**: Command-and-Control framework for simulation
- **osTicket**: Open-source ticketing system for incident management
- **Vultr**: Cloud platform for deployment
- **Debian & Windows Server 2022**: Operating systems used

## Implementation Details

### Day-by-Day Breakdown

1. **Day 1: Create Logical SOC Diagram**
   - Designed a logical diagram outlining the SOC architecture, illustrating the relationships between various components.

2. **Day 2: Learn About ELK Stack**
   - Researched the ELK stack components (Elasticsearch, Logstash, Kibana) and their functionalities.

3. **Day 3: Spin Up Elasticsearch Instance**
   - Deployed an Elasticsearch instance on Vultr, configured within a Virtual Private Cloud (VPC).

4. **Day 4: Install Kibana Instance**
   - Installed and configured Kibana to connect to the Elasticsearch instance.

5. **Day 5: Setup Windows Server 2022**
   - Installed Windows Server 2022, ensuring proper configuration.

6. **Day 6: Learn About Elastic Agent and Fleet Server**
   - Researched functionalities of Elastic Agents and Fleet Server.

7. **Day 7: Install Elastic Agent on Windows Server**
   - Deployed Elastic Agent on Windows Server, enrolling it into the Fleet Server.

8. **Day 8-9: Setup Sysmon for Logging**
   - Installed Sysmon and configured it to capture critical events.

9. **Day 10: Ingest Sysmon and Windows Defender Logs**
   - Configured Logstash to ingest logs from Sysmon and Windows Defender into Elasticsearch.

10. **Day 11: Research Brute Force Attacks**
    - Studied various types of brute force attacks and their defensive measures.

11. **Day 12: Set Up SSH Server and Monitor Logs**
    - Deployed an SSH server on Debian, monitored authentication logs for failed attempts.

12. **Day 13: Install Elastic Agent on SSH Server**
    - Installed Elastic Agent on the SSH server for log collection.

13. **Day 14: Create Alerts for Authentication Activity**
    - Developed alerts for failed SSH login attempts and created dashboards in Kibana.

14. **Day 15: Analyze RDP Risks**
    - Researched RDP risks and implemented security measures.

15. **Day 16: Create Alerts for Brute Force Attempts**
    - Set up alerts for brute force attempts targeting SSH and RDP servers.

16. **Day 17: Update Dashboards with Visualization**
    - Enhanced Kibana dashboards with chloropleth maps of authentication attempts.

17. **Day 18: Introduction to Command-and-Control (C2)**
    - Researched C2 operations and their significance in cyber attacks.

18. **Day 19: Create Attack Diagram Using MITRE Framework**
    - Developed an attack diagram to replicate a brute force attack scenario.

19. **Day 20: Setup Mythic Server**
    - Installed and configured the Mythic C2 framework.

20. **Day 21: Perform Brute Force Attack Simulation**
    - Conducted a simulated brute force attack and exfiltrated a sample file.

21. **Day 22: Create Alerts Based on Mythic Activity**
    - Developed alerts and dashboards based on Mythic activity telemetry.

22. **Day 23: Introduction to Ticketing Systems**
    - Researched ticketing systems in incident response and set up osTicket.

23. **Day 24: Setup and Configure osTicket**
    - Deployed osTicket on a dedicated Windows server.

24. **Day 25: Integrate osTicket with ELK Stack**
    - Configured webhook integration to send alerts from the ELK stack to osTicket.

25. **Day 26-29: Incident Analysis and Response**
    - Analyzed and responded to brute force attacks targeting SSH and RDP servers.

## Conclusion
This SOC setup project successfully demonstrated the integration of various cybersecurity tools to enhance monitoring and incident response capabilities. The project provided hands-on experience with the ELK stack, endpoint management, and threat detection strategies, essential skills for a career in cybersecurity.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
