
## Requirements Traceability Matrix (RTM)

| Requirement ID | Requirement Summary | State / Operation | Constraint ID | Test Case ID | Risk Level |
|---|---|---|---|---|---|
| FR-01 | Accept a valid delivery request. | IDLE → NAVIGATING | CON-08 | TC-01 | Medium |
| FR-02 | Authenticate users and authorise commands. | Command authorisation | CON-07 | TC-02 | High |
| FR-03 | Detect obstacles and initiate avoidance. | NAVIGATING → AVOIDING_OBSTACLE | CON-01 | TC-03 | High |
| FR-04 | Resume navigation only after obstacle clearance. | AVOIDING_OBSTACLE → NAVIGATING | CON-01 | TC-04 | High |
| FR-05 | Enter Safe Mode within 3 seconds of a critical condition. | Any applicable active state → SAFE_MODE | CON-06 | TC-05 | High |
| FR-06 | Abandon delivery and return when emergency battery threshold is reached. | Active delivery state → RETURNING or SAFE_MODE, according to safety conditions | CON-05 | TC-06 | High |
| FR-07 | Monitor chamber and robot environmental conditions. | Sensor monitoring operation | CON-09 | TC-07 | High |
| FR-08 | Correct environmental deviations and verify recovery. | Environmental recovery operation | CON-10 | TC-08 | High |
| FR-09 | Record commands, telemetry, events, and delivery status. | Logging operation | CON-11 | TC-09 | Medium |
| FR-10 | Handle power failure safely. | Power-failure operation | CON-12 | TC-10 | High |
| NFR-01 | Support at least 20 simultaneous robots. | System-wide operation | CON-13 | TC-11 | High |
| NFR-02 | Reject unauthorised commands. | Command authorisation | CON-07 | TC-02 | High |
| NFR-03 | Meet the 3-second Safe Mode response time. | Safe Mode transition | CON-06 | TC-05 | High |
| NFR-04 | Preserve committed logs across restarts. | Logging and restart handling | CON-11 | TC-12 | High |
| NFR-05 | Return portal status lookups within 3 seconds under the specified workload. | Monitoring portal | CON-13 | TC-13 | Medium |

