# threat-hunting-portfolio

```
threat-hunting-portfolio/
│
├── README.md
│
├── 01-Reconnaissance/
│   ├── T1595-Active-Scanning/
│   │   └── hunt-active-scanning/
│   │       ├── hypothesis.md
│   │       ├── data-sources.md
│   │       ├── queries/
│   │       ├── analysis.md
│   │       ├── findings.md
│   │       └── mitre-mapping.md
│   │
│   └── T1598-Phishing-for-Information/
│       └── hunt-phishing-recon/
│           ├── hypothesis.md
│           ├── logs-used.md
│           ├── detection-logic.md
│           └── conclusions.md
│
├── 02-Resource-Development/
│   └── T1587-Malware-Development/
│       └── hunt-suspicious-build-artifacts/
│
├── 03-Initial-Access/
│   ├── T1566-Phishing/
│   │   ├── hunt-phishing-attachment/
│   │   └── hunt-phishing-link/
│   │
│   └── T1190-Exploit-Public-Facing-App/
│       └── hunt-web-exploit-attempts/
│
├── 04-Execution/
│   ├── T1059-Command-and-Scripting-Interpreter/
│   │   ├── hunt-powershell-abuse/
│   │   └── hunt-cmd-lolbins/
│   │
│   └── T1204-User-Execution/
│       └── hunt-malicious-shortcuts/
│
├── 05-Persistence/
│   ├── T1547-Boot-or-Logon-Autostart/
│   │   ├── registry-run-keys/
│   │   └── startup-folder-abuse/
│   │
│   └── T1053-Scheduled-Task/
│       └── hunt-scheduled-task-persistence/
│
├── 06-Privilege-Escalation/
│   └── T1068-Exploitation-for-Privilege-Escalation/
│
├── 07-Defense-Evasion/
│   ├── T1070-Indicator-Removal/
│   └── T1027-Obfuscated-Files-or-Info/
│
├── 08-Credential-Access/
│   ├── T1003-OS-Credential-Dumping/
│   │   └── hunt-lsass-access/
│   │
│   └── T1110-Brute-Force/
│
├── 09-Discovery/
│   ├── T1087-Account-Discovery/
│   └── T1046-Network-Service-Discovery/
│
├── 10-Lateral-Movement/
│   ├── T1021-Remote-Services/
│   └── T1550-Use-Alternate-Authentication/
│
├── 11-Command-and-Control/
│   ├── T1071-Application-Layer-Protocol/
│   └── T1095-Non-Application-Layer-Protocol/
│
├── 12-Exfiltration/
│   └── T1048-Exfiltration-Over-Alt-Protocol/
│
├── 13-Impact/
│   ├── T1486-Data-Encrypted-for-Impact/
│   └── T1499-Endpoint-Denial-of-Service/
│
├── 90-Shared-Queries/
│   ├── kql/
│   ├── splunk/
│   └── sigma/
│
├── 91-Methodology/
│   ├── hunt-lifecycle.md
│   ├── false-positive-handling.md
│   └── detection-tuning.md
│
├── 92-Tools-and-Labs/
│   ├── homelab.md
│   └── tooling.md
│
└── assets/
    ├── diagrams/
    └── screenshots/
```
