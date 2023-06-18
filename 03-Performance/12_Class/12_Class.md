[🔙 << Clase 11 >>](../11_Class/11_Class.md) | [Clase 13 >>](../13_Class/13_Class.md)

[🔙 Volver](../README.md)


# Stress Test
## What is Stress Test?
- Checking application performance under extreme load (load beyond regular) conditions
- System is pushed past the limit of available resources to check how the application behaves
- Applied load can be 150% to 500% of peak load in stress test

## Stress test approach (Planning)
- Stress test NFR's are referred. The NFR's typically have details like
    - Expected response time
    - User or TPS load
- Workload Model is prepared according to these NFR's
- Stress test scripts are prepared according to workload model
- Stress test is run for centain duration (1 or 2 hours)
    - Steady state (1 or 2 hours)
    - Ramp up and ramp down periods
- Metrics are measured during stress test run
    - Response Time
    - Erros
    - TPS
    - User Load
    - CPU and Memory utilization
- Errors or unexpected behavior are noted down

## Sample Stress test NFR's
| NFR ID| Requirement | Acceptance Criteria | Remarks |
|-------|-----------------|-----------------|-----------------|
| 1 | User Load | Application should be able to handle 200 concurrent users load| 200% of peak load |
| 2 | Response Time | Average response time of all the pages should be less than 3 seconds | 90th percentile should be less than 4 seconds |
| 3 | Errors | Error rate should not exceed 5% |  |
| 4 | Transactions per second | 700 orders should be submitted in one hour |  |
| 5 | Resources utilization | if CPU usage and memory usage should exceeds 90%, application should remain stable | Applicable for web, app and DB servers |

## User Graph
<img src="../assets/RampGraph.png" alt="Difference" width="800" height="">

## Common Issues
- Application crash
- Increased error  rate after certain load
- Slower response time
- Increased resource utilization
- One or mode application components failing or misbehaving
- Any specific performance issue

[🔙 << Clase 11 >>](../11_Class/11_Class.md) | [Clase 13 >>](../13_Class/13_Class.md)
