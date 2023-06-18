[🔙 << Clase 12](../12_Class/12_Class.md) | [Clase 14 >>](../14_Class/14_Class.md)

[🔙 Volver](../README.md)


# Soak Test
## What is Soak Test?
- Checking application performance under [average load](../05_Class/05_Class.md) conditions
- Typically run for longer duration (Eg. 4 hours to 48 hours)
    - Can be run over a weekend
- Goal is to check if application can sustain continuous load for extended period
- Also known as Endurance Testing or Longevity Testing

## Soak Test Approach (Planning)
- Soak test NFR's are referred. The NFR's typically have details like
    - Expected response time
    - Average load details
    - User or TPS load
- Workload Model is prepared according to these NFR's

## Soak test Approach (Design & Execution)
- Soak test scripts are prepared according to Workload Model
- Soak test is run for certain duration (Eg. 4 to 48 hours)
    - Steady state (4 to 48 hours)
    - Ramp up and ramp down periods
- Metrics are measured during soak test run
    - Response Time
    - Errors
    - TPS
    - User load
    - CPU and Memory utilization
- Errors or unexpected behavior are noted down

## Soak test NFR's Example
| NFR ID| Requirement | Acceptance Criteria | Remarks |
|-------|-----------------|-----------------|-----------------|
| 1 | User Load | Application should be able to handle 100 concurrent users load| Test should run for 8 hours |
| 2 | Response Time | Average response time of all the pages should be less than 2 seconds | 90th percentile should not be more than 4 seconds |
| 3 | Errors | Error rate should not exceed 2% |  |
| 4 | Transactions per second | More than or equal to 2500 orders should be submitted |  |
| 5 | Resources utilization | CPU usage should not exceed 60% and memory usage should not exceed 70% , application should remain stable | Applicable for web, app and DB servers |

## Common Issues
- Memory leaks
- Application crash
- Slower response time
- Increased DB resource utilization
- One or more application components failing or misbehaving

[🔙 << Clase 12](../12_Class/12_Class.md) | [Clase 14 >>](../14_Class/14_Class.md)