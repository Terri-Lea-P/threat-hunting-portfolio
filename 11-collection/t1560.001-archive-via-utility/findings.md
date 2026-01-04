# Findings

## Confirmed Activity

- Repeated ZIP archives were created on a single endpoint and stored in a local “backup” directory.
- PowerShell was used to silently install and execute a third-party archiving utility (7zip).
- Archiving activity was automated and non-interactive.

## Correlated Evidence

- ZIP creation timestamps closely aligned with PowerShell execution.
- No legitimate backup software or scheduled task was identified during the activity window.
- Network telemetry showed no outbound connections or data transfer during or immediately after archiving.

## Conclusion

- Activity is consistent with **unauthorized data collection and staging**.
- No evidence of data exfiltration was observed at the time of investigation.
- Behavior represents a **data staging risk**, potentially indicative of insider misuse or preparatory activity.

## Response Actions

- Endpoint was isolated immediately upon confirmation of activity.
- Findings were escalated to management with supporting telemetry.
- Monitoring remained in place pending further instruction.

