[🔙 << Clase 9](../09_Class/09_Class.md) | [Clase 11 >>](../11_Class/11_Class.md)

[🔙 Volver](../README.md)


# Load Test
## What is load test?
- Many confuse load test with performance test but they are not the same
    - Load test is a type of performance testing.
- Checking application performance under peak load conditions.
- Goal is to validate that a system can handle the expected load with acceptable performance.

## Load test approach (Planning)
- Load test NFR( Non Functional Requirements )are referred. The NRF's typically have details like
    - Expected response time
    - Peak load details
    - Users or TPS load
- Workload Model is prepared according to these NFR's

## Load test approach (Design & Execution)
- Load test scripts are prepared according to Workload Model.
- Load test is run for certain duration (1 or 2 hours)
    - Steady state (1 or 2 hours)
    - Ramp up and ramp down periods
- Metrics are measured during load test run
    - Response time
    - Errors
    - TPS
    - User Load
    - CPU and Memori utilization
- Errors or unexpected behavior are noted down

[🔙 << Clase 9](../09_Class/09_Class.md) | [Clase 11 >>](../11_Class/11_Class.md)
