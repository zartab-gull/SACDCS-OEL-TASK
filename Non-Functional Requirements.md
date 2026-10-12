
## Non-Functional Requirements

| Requirement ID | Requirement Description | Acceptance Criterion |
|---|---|---|
| NFR-01 | The system shall support at least 20 robots operating simultaneously. | The system completes a load test involving 20 robots without violating safety requirements. |
| NFR-02 | The system shall reject unauthorised commands. | All unauthorised-command test cases are rejected. |
| NFR-03 | The system shall enter Safe Mode within the specified time limit. | Safe Mode is activated within 3 seconds of detecting the specified critical condition. |
| NFR-04 | The system shall preserve committed safety and operational logs across a restart. | Previously committed logs remain available after restarting the system. |
| NFR-05 | The monitoring portal shall return a robot-status lookup within 3 seconds under the specified 20-robot workload. | The lookup response time does not exceed 3 seconds during the defined load test. |

