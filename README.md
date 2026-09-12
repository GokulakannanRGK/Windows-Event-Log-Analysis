# 🔎 Analysis & Response

This section contains a collection of small **cybersecurity analysis and incident-response investigations** performed as part of my practical learning.

The investigations focus on identifying suspicious activity, understanding the behavior of potential threats, analyzing available evidence, and determining appropriate response actions.

---

## 🎯 Objectives

* Practice real-world cybersecurity analysis
* Identify suspicious files and activities
* Analyze potential attack indicators
* Investigate phishing attempts
* Analyze potentially malicious `.LNK` files
* Identify signs of an infected USB device
* Investigate suspicious system activity
* Understand basic incident-response procedures
* Document findings and response actions

---

# 🧪 Investigations & Analysis

## 📁 LNK File Analysis

Analysis of suspicious **Windows Shortcut (`.LNK`) files** to understand how shortcut files can be abused to execute malicious commands or programs.

### Areas Analyzed

* LNK file properties
* Target path
* Command-line arguments
* Associated executable/script
* Suspicious parameters
* File metadata
* Potential execution behavior

### Investigation Focus

```text
Suspicious LNK
      ↓
Inspect Properties
      ↓
Identify Target
      ↓
Analyze Arguments
      ↓
Identify Suspicious Behavior
      ↓
Determine Risk
      ↓
Document Findings
```

---

# 🎣 Phishing Attack Analysis

Investigation of phishing-related artifacts to understand how attackers attempt to trick users into revealing information or executing malicious content.

### Areas Analyzed

* Sender information
* Email subject
* Suspicious URLs
* Domain information
* Email content
* Attachments
* Indicators of compromise
* Social-engineering techniques

### Investigation Process

```text
Phishing Alert
      ↓
Analyze Email
      ↓
Inspect Sender
      ↓
Analyze URL / Domain
      ↓
Check Indicators
      ↓
Determine Threat
      ↓
Document Findings
      ↓
Recommend Response
```

---

# 💾 Infected USB Detection

Practical analysis focused on identifying signs that a USB storage device may contain suspicious or malicious files.

### Areas Analyzed

* Suspicious files
* Hidden files
* Shortcut files
* Autorun-related behavior
* Unusual file extensions
* Unknown executables
* File timestamps
* Potential malware indicators

### Investigation Process

```text
USB Device
     ↓
Inspect Files
     ↓
Identify Suspicious Items
     ↓
Analyze File Properties
     ↓
Check Indicators
     ↓
Determine Possible Infection
     ↓
Isolate / Avoid Execution
     ↓
Document Findings
```

---

# 🕵️ Additional Investigations

This section also contains smaller investigations involving:

* Suspicious files
* Security events
* Potential malware activity
* IOC analysis
* Unusual system behavior
* Windows artifacts
* Basic incident investigation
* Security alerts

Each investigation is documented according to the available evidence and investigation scope.

---

# 🛡️ Analysis & Response Approach

The general approach followed during these investigations is:

```text
Identify
   ↓
Collect Evidence
   ↓
Analyze
   ↓
Validate Indicators
   ↓
Determine Risk
   ↓
Contain / Avoid Further Execution
   ↓
Document
   ↓
Recommend Response
```

---

# 🧰 Tools & Resources

Tools and resources used during different investigations include:

* Windows Event Viewer
* PowerShell
* Command Prompt
* VirusTotal
* AbuseIPDB
* Windows File Properties
* File and metadata analysis tools
* MITRE ATT&CK
* Cyber Kill Chain

---

# 📸 Evidence & Documentation

Each investigation may contain supporting:

* Screenshots
* File analysis
* Event logs
* IOC information
* Investigation notes
* Findings
* Response recommendations

The evidence is organized with the corresponding investigation wherever possible.

---

# 🧠 Skills Demonstrated

Through these investigations, I am developing practical skills in:

* Threat Analysis
* Phishing Analysis
* Malware Investigation
* Windows Artifact Analysis
* LNK File Analysis
* USB Threat Detection
* IOC Identification
* Security Investigation
* Incident Response
* Evidence Documentation
* Threat Intelligence
* Windows Security

---

# 🚀 SOC Relevance

These investigations simulate common activities that can be encountered by a **SOC Analyst**, such as:

* Investigating suspicious attachments
* Analyzing phishing reports
* Examining potentially malicious files
* Investigating compromised devices
* Identifying indicators of compromise
* Determining the severity of an event
* Recommending containment and response actions

The goal is to move beyond simply identifying a threat and understand the complete process of:

**Detection → Analysis → Validation → Response → Documentation**

---

> This section represents my hands-on cybersecurity analysis and incident-response learning through small, practical investigations.

