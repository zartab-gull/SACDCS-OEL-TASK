

## Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result |
|---|---|---|---|
| TC-01 | Valid delivery request | Submit a valid delivery request while the robot is IDLE. | The request is accepted and the robot transitions to NAVIGATING. |
| TC-02 | Unauthorised command | Submit a command from a user without the required role. | The command is rejected and the event is recorded. |
| TC-03 | Obstacle detection | Introduce an obstacle while the robot is navigating. | The robot detects the obstacle and initiates obstacle avoidance. |
| TC-04 | Obstacle clearance | Clear the obstacle while the robot is in AVOIDING_OBSTACLE. | The robot resumes navigation only after clearance is confirmed. |
| TC-05 | Critical temperature or battery condition | Trigger a specified critical condition and measure the transition time. | The robot enters Safe Mode within 3 seconds. |
| TC-06 | Emergency battery threshold | Trigger the emergency battery condition during a delivery. | The robot abandons the delivery and follows the defined safe-return or protective procedure. |
| TC-07 | Environmental monitoring | Change a monitored chamber parameter. | The system detects and records the changed reading. |
| TC-08 | Environmental recovery | Introduce an environmental deviation and execute corrective action. | The system checks the readings and confirms recovery or activates protection if recovery fails. |
| TC-09 | Event logging | Execute commands and trigger safety events. | The relevant commands, telemetry, and events are recorded. |
| TC-10 | Power failure | Simulate power failure with and without emergency power availability. | Emergency power is used when available; otherwise, failure is recorded and safe shutdown is performed. |
| TC-11 | Simultaneous robot workload | Run the system with 20 robots operating simultaneously. | The system supports the workload without violating safety requirements. |
| TC-12 | Log persistence | Record events, restart the system, and inspect the logs. | All committed logs remain available. |
| TC-13 | Monitoring portal response | Request robot-status information under the specified 20-robot workload. | The status lookup completes within 3 seconds. |

