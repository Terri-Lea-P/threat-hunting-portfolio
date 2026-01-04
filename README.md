# threat-hunting-portfolio

> **Note on MITRE ATT&CK technique ranges**
>
> The technique ID ranges shown next to each tactic are **illustrative only**.  
> They are used as **human-readable scope markers** to indicate general coverage areas, **not** as strict or contiguous MITRE ATT&CK ID blocks, and **not** as a schema or authoritative mapping.  
>  
> Individual technique coverage is defined explicitly at the technique folder level.

```
threat-hunting-portfolio/
│
├── README.md
│
├── 01-reconnaissance/                         ← T1590–T1599 (expanded example)
│   ├── t1595-active-scanning/
│   │   ├── hypothesis.md
│   │   ├── data-sources.md
│   │   ├── queries/
│   │   ├── analysis.md
│   │   ├── findings.md
│   │   └── mitre-mapping.md
│   │
│   └── t1598-phishing-for-information/
│       ├── hypothesis.md
│       ├── data-sources.md
│       ├── queries/
│       ├── analysis.md
│       └── findings.md
│
├── 02-resource-development/                   ← T1583–T1608
├── 03-initial-access/                         ← T1078–T1190
├── 04-execution/                              ← T1059–T1204
├── 05-persistence/                            ← T1136–T1547
├── 06-privilege-escalation/                   ← T1068–T1611
├── 07-defense-evasion/                        ← T1027–T1562
├── 08-credential-access/                      ← T1003–T1558
├── 09-discovery/                              ← T1016–T1087
├── 10-lateral-movement/                       ← T1021–T1550
├── 11-collection/                             ← T1005–T1119
├── 12-command-and-control/                    ← T1071–T1132
├── 13-exfiltration/                           ← T1020–T1048
├── 14-impact/                                 ← T1485–T1499
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
