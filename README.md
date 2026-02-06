# SOC-Automation-Lab
End-to-End SOC Automation Lab with Splunk, n8n &amp; Slack

This repository showcases a hands-on SOC automation lab, demonstrating a fully automated security operations workflow—from Windows telemetry generation to alert processing and notification using Splunk, n8n, and Slack.

Lab Overview:
This lab simulates a real-world Security Operations Center (SOC) automation pipeline, integrating multiple virtual machines:

Windows 10 VM – generates system and security telemetry.
Splunk SIEM VM – ingests logs, indexes data, and generates alerts.
n8n Automation VM – orchestrates automated workflows for alert processing.
Slack – receives notifications for security events.
The workflow demonstrates a complete SIEM → SOAR → Notification pipeline in action.

Lab Steps:
Step 1: Install Splunk and Configure the GUI
🖥️ Install Splunk Enterprise on a virtual machine and configure the web interface for log ingestion, searching, and alert creation.

Step 2: Forward Telemetry from Windows VM to Splunk
📡 Configure the Windows 10 VM to send system and security logs to Splunk, enabling real-time monitoring and alerting.

Step 3: Install n8n
🤖 Deploy n8n, the automation platform, on a virtual machine to enable event-driven workflows that process alerts and trigger responses.

Step 4: Build the Automation Workflow
⚡ Create n8n workflows to handle Splunk alerts, simulate SOC responses, and automate the alert response process.

Step 5: Send Results to Slack
📬 Configure Slack notifications so automated messages are delivered whenever n8n workflows are triggered, completing the end-to-end SOC automation pipeline.

References

Full lab documentation and guide: https://medium.com/@safwanawan099/soc-automation-lab-splunk-n8n-slack-61adce8d4a61
