## Functional Requirements

| Requirement ID | Requirement Description | Priority |
|---|---|---|
| FR-01 | The system shall accept a valid delivery request and transition from IDLE to NAVIGATING. | High |
| FR-02 | The system shall authenticate users and authorise commands according to their assigned roles. | High |
| FR-03 | The system shall detect obstacles, suspend normal navigation, and initiate obstacle avoidance. | High |
| FR-04 | The system shall resume navigation only after the detected obstacle has been cleared. | High |
| FR-05 | The robot shall enter Safe Mode within 3 seconds when a critical battery or chamber-temperature condition is detected. | High |
| FR-06 | When the emergency battery threshold is reached, the robot shall abandon the delivery and return to the warehouse using the defined safe-return procedure. | High |
| FR-07 | The system shall monitor chamber temperature, humidity, vibration, door status, and power status. | High |
| FR-08 | The system shall respond to environmental deviations and verify sensor readings after corrective action. | High |
| FR-09 | The system shall record commands, telemetry, safety events, and delivery-status changes. | High |
| FR-10 | During power failure, the system shall activate emergency power when available; otherwise, it shall record the failure and perform a safe shutdown. | High |

