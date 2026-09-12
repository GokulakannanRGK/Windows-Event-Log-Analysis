# 🛡️ SOC Analysis – Remote Code Execution Detection in Splunk

This section documents a **SOC investigation focused on detecting and analyzing Remote Code Execution (RCE) activity using Splunk**.

The analysis demonstrates how a SOC analyst can use log data and Splunk searches to identify suspicious command execution, investigate related events, and determine whether activity may indicate an RCE attempt or compromise.

---

## 🔎 Investigation Overview

The investigation focuses on identifying suspicious remote code execution behavior through available security logs.

The analysis includes:

* Identifying suspicious execution activity
* Searching relevant log events in Splunk
* Investigating command execution
* Analyzing source and destination information
* Correlating related events
* Identifying potential indicators of compromise
* Determining whether the activity is suspicious
* Documenting investigation findings

---

## 🧠 SOC Investigation Process

```text
Security Event
      ↓
Splunk Search
      ↓
Identify Suspicious Activity
      ↓
Analyze Related Events
      ↓
Correlate Evidence
      ↓
Identify IOC / Attack Behavior
      ↓
Determine Severity
      ↓
Document Findings
```

---

## 🔍 Detection in Splunk

Splunk is used to search and analyze collected logs to identify patterns associated with suspicious execution activity.

The investigation focuses on fields such as:

* Source IP
* Destination IP
* Username
* Host
* Process
* Command
* Timestamp
* Event ID
* Parent process
* Network activity

Relevant events are filtered and correlated to identify activity that may indicate remote execution.

---

## 🚨 Analysis

During the investigation, suspicious events are examined to determine:

* What activity occurred?
* Which system was involved?
* Which user account was involved?
* What process or command was executed?
* Where did the activity originate?
* What other events occurred around the same time?
* Does the behavior match a known attack technique?

The objective is to distinguish potentially malicious activity from legitimate administrative or system activity.

---

## 🛡️ MITRE ATT&CK Relevance

The investigation can be related to **MITRE ATT&CK techniques associated with remote execution and command execution**, depending on the observed activity.

Mapping the observed behavior to ATT&CK helps understand the attack technique and provides additional context for detection and response.

---

## 📊 Investigation Evidence

The repository contains screenshots and investigation evidence showing:

* Splunk searches
* Relevant log events
* Detected suspicious activity
* Event details
* Analysis findings

---

## 🧰 Tools Used

* Splunk Enterprise
* Windows Event Logs
* Windows Security Logs
* MITRE ATT&CK

---

## 🎯 Skills Demonstrated

* SOC Alert Analysis
* Splunk Log Analysis
* Threat Detection
* Event Correlation
* Remote Code Execution Detection
* Windows Log Analysis
* IOC Identification
* MITRE ATT&CK Mapping
* Security Investigation
* Incident Documentation

---

> This investigation demonstrates the use of Splunk for identifying and analyzing suspicious remote code execution activity from security logs as part of SOC operations.
