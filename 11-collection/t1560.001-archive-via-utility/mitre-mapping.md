# MITRE ATT&CK Mapping

## Primary Technique

- **T1560.001 – Archive Collected Data: Archive via Utility**
  - PowerShell was used to install and execute 7zip.
  - Employee-related data was compressed into ZIP archives.
  - Activity aligns with utility-based data staging.

## Tactic Alignment

- **Collection**
  - Data was gathered and prepared locally.
  - No evidence of data leaving the endpoint during analysis.

## Related Techniques (Observed but Not Attributed)

- **T1059.001 – Command and Scripting Interpreter: PowerShell**
  - Used as the execution mechanism for installing and running 7zip.
  - Supporting behavior, not the primary objective.

## Explicitly Excluded Techniques

- **Exfiltration (T1020–T1048)**
  - Network telemetry showed no outbound data transfer.
  - No protocol, service, or channel consistent with exfiltration observed.

## Mapping Confidence

- High confidence for **T1560.001** based on direct process and file evidence.
- No secondary technique promotion due to lack of corroborating telemetry.

