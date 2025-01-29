# Network Monitoring Lab

## Overview
This project explores network monitoring using Splunk, a powerful tool for searching, monitoring, analyzing, and visualizing machine-generated data. The lab focuses on understanding data sources, performing searches, advanced searching techniques, dashboards, and visualizations. The practical application of these skills is demonstrated through hands-on exercises and real-world log analysis.

## Key Components

### 1. Introduction to Splunk
Splunk is a comprehensive tool that processes structured and unstructured data, transforming it into meaningful insights. It is widely used for log analysis, security monitoring, and operational intelligence. The project begins with an overview of Splunk’s functionalities, including indexing, searching, and dashboard creation.

### 2. Data Sources in Splunk
Splunk processes data from various sources, including:
- System logs (Windows Event Logs, Sysmon)
- Network traffic (Suricata, Stream)
- Firewall logs (Fortinet FortiGate)
- Custom application logs

Understanding how Splunk organizes data using sources and source types is essential for effective search and analysis.

### 3. Basic Search Techniques
Using Splunk’s Search Processing Language (SPL), we conducted free-form searches to filter and analyze log data. Key aspects covered include:
- Search pipelines for refining queries
- Field-based searches using key-value pairs
- Boolean expressions and wildcards for flexibility
- Event viewing and data interpretation

### 4. Advanced Searching (SPL & Transforming Commands)
Building upon basic searches, we explored advanced SPL commands such as:
- `stats`, `chart`, and `timechart` for data aggregation
- `top` and `rare` for frequency analysis
- Subsearches for nested queries
- Filtering and sorting techniques for enhanced data analysis

### 5. Dashboards and Visualization
Splunk’s visualization capabilities were utilized to create meaningful dashboards. The project included:
- Pie charts for HTTP status code distribution
- Bar charts for web activity by IP
- Line charts for HTTP method trends
- Dashboard creation for centralized monitoring

### 6. Hands-On Log Analysis
Using real-world logs from the ‘Boss of the SOC’ dataset, we analyzed network activity, identified potential threats, and correlated events across multiple data sources. Key tasks included:
- Identifying attacker IPs from intrusion detection logs
- Investigating web application scanning activity
- Analyzing firewall logs for unauthorized access attempts
- Extracting insights from Windows Event Logs

## Conclusion
This project provided hands-on experience in network monitoring, log analysis, and threat detection using Splunk. By leveraging advanced search techniques and visualizations, we gained insights into security monitoring and operational intelligence. The practical exercises reinforced the importance of structured log analysis in cybersecurity and incident response.

