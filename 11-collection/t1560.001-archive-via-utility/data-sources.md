# Data Sources

## Endpoint Telemetry

- **Defender for Endpoint**
  - `DeviceFileEvents`  
    - Identified ZIP archive creation and movement to a local “backup” directory.
  - `DeviceProcessEvents`  
    - Correlated ZIP creation with PowerShell activity.
    - Observed silent installation and execution of 7zip.
  - `DeviceNetworkEvents`  
    - Validated absence of outbound network activity during the collection window.

## Scope and Limitations

- Single endpoint in scope (`tp--tp--tp`).
- Analysis limited to ±2 minutes around archive creation events.
- No proxy, firewall, or DLP telemetry reviewed.

## Known Gaps

- Archive contents not inspected beyond metadata.
- User intent not directly observable.
- No evidence of data transfer off-host within the observed window.

