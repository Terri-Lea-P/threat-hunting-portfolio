# threat-hunting-portfolio

```
threat-hunting-portfolio/
│
├── readme.md
│
├── 01-reconnaissance/
│   ├── t1595-active-scanning/
│   │   └── hunt-active-scanning/
│   │       ├── hypothesis.md
│   │       ├── data-sources.md
│   │       ├── queries/
│   │       ├── analysis.md
│   │       ├── findings.md
│   │       └── mitre-mapping.md
│   │
│   └── t1598-phishing-for-information/
│       └── hunt-phishing-recon/
│           ├── hypothesis.md
│           ├── logs-used.md
│           ├── detection-logic.md
│           └── conclusions.md
│
├── 02-resource-development/
│   └── t1587-malware-development/
│       └── hunt-suspicious-build-artifacts/
│
├── 03-initial-access/
│   ├── t1566-phishing/
│   │   ├── hunt-phishing-attachment/
│   │   └── hunt-phishing-link/
│   │
│   └── t1190-exploit-public-facing-app/
│       └── hunt-web-exploit-attempts/
│
├── 04-execution/
│   ├── t1059-command-and-scripting-interpreter/
│   │   ├── hunt-powershell-abuse/
│   │   └── hunt-cmd-lolbins/
│   │
│   └── t1204-user-execution/
│       └── hunt-malicious-shortcuts/
│
├── 05-persistence/
│   ├── t1547-boot-or-logon-autostart/
│   │   ├── registry-run-keys/
│   │   └── startup-folder-abuse/
│   │
│   └── t1053-scheduled-task/
│       └── hunt-scheduled-task-persistence/
│
├── 06-privilege-escalation/
│   └── t1068-exploitation-for-privilege-escalation/
│
├── 07-defense-evasion/
│   ├── t1070-indicator-removal/
│   └── t1027-obfuscated-files-or-info/
│
├── 08-credential-access/
│   ├── t1003-os-credential-dumping/
│   │   └── hunt-lsass-access/
│   │
│   └── t1110-brute-force/
│
├── 09-discovery/
│   ├── t1087-account-discovery/
│   └── t1046-network-service-discovery/
│
├── 10-lateral-movement/
│   ├── t1021-remote-services/
│   └── t1550-use-alternate-authentication/
│
├── 11-command-and-control/
│   ├── t1071-application-layer-protocol/
│   └── t1095-non-application-layer-protocol/
│
├── 12-exfiltration/
│   └── t1048-exfiltration-over-alt-protocol/
│
├── 13-impact/
│   ├── t1486-data-encrypted-for-impact/
│   └── t1499-endpoint-denial-of-service/
│
├── 90-shared-queries/
│   ├── kql/
│   ├── splunk/
│   └── sigma/
│
├── 91-methodology/
│   ├── hunt-lifecycle.md
│   ├── false-positive-handling.md
│   └── detection-tuning.md
│
├── 92-tools-and-labs/
│   ├── homelab.md
│   └── tooling.md
│
└── assets/
    ├── diagrams/
    └── screenshots/

```
