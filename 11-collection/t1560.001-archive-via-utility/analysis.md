# Analysis

## Initial Detection

- Queried endpoint file telemetry for ZIP archive creation.
- Identified repeated ZIP files created on the same endpoint and moved into a local “backup” directory.
- Activity was inconsistent with typical user-driven compression behavior.

## Temporal Correlation

- Selected a representative ZIP creation event.
- Performed a ±2 minute correlation window against process execution telemetry.
- Identified PowerShell activity occurring immediately before and during archive creation.

## Process Execution Review

- PowerShell was used to silently install a third-party archiving utility (7zip).
- 7zip was then invoked to compress employee-related data into ZIP archives.
- Execution pattern indicates scripted, non-interactive behavior.

## Network Validation

- Reviewed network telemetry for the same correlation window.
- No outbound connections or data transfer events observed.
- Activity assessed as data collection and staging only.

## Analyst Assessment

- Behavior is consistent with automated data collection via utility-based archiving.
- No evidence supports successful or attempted exfiltration at the time of analysis.
- Risk assessed as **potential insider misuse or pre-exfiltration staging**, pending further direction.

