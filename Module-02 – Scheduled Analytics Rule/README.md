# Module 2 – Scheduled Analytics Rule

## Overview

This module demonstrates the creation and deployment of a **Scheduled Analytics Rule** in Microsoft Sentinel using a built-in rule template. Scheduled Analytics Rules continuously analyze ingested log data at defined intervals to detect suspicious activities and generate security alerts.

This exercise introduced the process of configuring analytics rules, mapping MITRE ATT&CK tactics, and enabling automated alert generation.

---

## Objectives

- Explore built-in analytics rule templates
- Create a Scheduled Analytics Rule
- Configure rule scheduling and alert settings
- Map MITRE ATT&CK tactics
- Enable the rule within Microsoft Sentinel

---

## Technologies Used

- Microsoft Sentinel
- Microsoft Defender Portal
- Azure Log Analytics
- Kusto Query Language (KQL)
- MITRE ATT&CK Framework

---

## Skills Demonstrated

- Analytics Rule Configuration
- Detection Engineering
- Security Monitoring
- Alert Generation
- MITRE ATT&CK Mapping
- Microsoft Sentinel Administration

---

## Rule Configuration

| Setting | Value |
|---------|-------|
| Rule Type | Scheduled |
| Query Frequency | Every 5 minutes |
| Lookup Period | Last 1 hour |
| Severity | Medium |
| Status | Enabled |

---

## Lab Activities

- Reviewed available Scheduled Analytics Rule templates.
- Selected an appropriate detection rule.
- Configured scheduling parameters.
- Assigned severity and MITRE ATT&CK mappings.
- Enabled the rule for continuous monitoring.
- Verified successful deployment.

---

## Screenshots

### Built-in Analytics Rule Template

![Scheduled Rule Template](https://github.com/umadevims326-jpg/SOC-Analyst-Lab-Microsoft-Sentinel/blob/40fcfc348d60d4e70f1ea5c0a7438a6c73e72006/portfolio-screenshots01/active_rule_from_Template-1.png)


---

### Enabled Scheduled Analytics Rule

![Enabled Rule](https://github.com/umadevims326-jpg/SOC-Analyst-Lab-Microsoft-Sentinel/blob/40fcfc348d60d4e70f1ea5c0a7438a6c73e72006/portfolio-screenshots01/active_rule-2.png)

---

## Key Learning Outcomes

- Learned how Microsoft Sentinel Scheduled Analytics Rules operate.
- Understood how scheduled detections generate alerts from log data.
- Gained experience configuring detection rules using built-in templates.
- Practiced mapping detections to the MITRE ATT&CK framework.
- Prepared the environment for creating custom analytics rules in subsequent modules.

---

## Portfolio Value

This module demonstrates practical experience configuring Microsoft Sentinel Scheduled Analytics Rules using built-in detection templates. It highlights foundational SOC analyst skills in detection engineering, security monitoring, and alert configuration.
