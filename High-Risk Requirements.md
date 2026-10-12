

## High-Risk Requirements

| Risk ID | Related Requirement | Risk Description | Required Control |
|---|---|---|---|
| HR-01 | FR-05 | Delayed activation of Safe Mode may damage the cargo or robot. | Verify that Safe Mode activates within 3 seconds of a critical condition. |
| HR-02 | FR-03, FR-04 | Incorrect movement at a railway crossing may cause a serious accident. | Enforce railway-crossing interlocks and verify safe crossing conditions before movement. |
| HR-03 | FR-02 | Unauthorised or stale commands may cause unsafe robot behaviour. | Authenticate commands, check user roles, and reject invalid or outdated commands. |
| HR-04 | FR-07, FR-08 | Failure to detect or correct chamber-environment deviations may damage sensitive cargo. | Monitor environmental readings, verify corrective actions, and activate protection when recovery fails. |
