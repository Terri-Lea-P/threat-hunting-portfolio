# Hypothesis

An endpoint is staging sensitive employee data by using a PowerShell script to silently install and execute a third-party archiving utility (7zip), resulting in repeated ZIP archive creation in a local “backup” directory consistent with unauthorized data collection activity.

## Conditions to Validate

- ZIP files are created at regular or scripted intervals.
- PowerShell installs and invokes 7zip.
- Archived files contain employee or business-related data.
- Activity is not associated with an approved backup process.
- No outbound network activity is required at this stage.

## MITRE ATT&CK Context

- Tactic: Collection  
- Technique: T1560.001 – Archive Collected Data: Archive via Utility  
- Framework: MITRE ATT&CK

