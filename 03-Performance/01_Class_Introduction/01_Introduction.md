# Clase 1: Introducción

[🔙 Volver](../README.md)

# Performance Testing Introduction
## "What"is Performance Testing
- Non functional testing
- Testing application performance under user load
- it checks application speed, scalability and stability

    ## Goals
    1. Anticipate before going live
    2. Reproduce crash
    3. Identify infra requirements
    4. Account for future growth

- **Breakpoint Test:** it is conducted to identify the maximum load-bearing capacity of the application.
- **Step-up Test:** it is conducted to find out the application performance at the different user load in same test.
- **Failover Test:** it is done to check the application recovery in case of any application component failure under load.
- **Volume Test:** it is conducted to check application behaviour when it is subjected to a huge volume of data.
- **Load Test:** it is conducted to understand the application behaviour under a specific expected user load.
- **Stress Test:** it is done to determine the system's robustness when it's put under extreme load.
- **Soak Test:** it is done to determine if the system can sustain the continuos expected load for long duration.
- **Spike Test:** it checks application behaviour when it is subjected to sudden increase or decrease of load.


## "Why"
- Performance is a feature.
- Users dont like poorly performing systems.
- Users also dont like systems which are not stable.
- Poor performing systems results in loss of sales and reputation.
    ## Why perfomance testing is so important?
    - Know about maximum load system can handle.
    - Identify system behaviour under different load conditions.
    - Find out system responsiveness under load.
    - Identify any performance bottlenecks.

## "How"
- Typically done using performance testing tools.
- These tools create virtual users to carry out different business trasactions.
- Multiple load generators are used to generate large user load.
- Tools provides different performance metrics.
    ## Commercial Tools
    - HP LoadRunner
    - Neolad by Neotys
    - WebLoad by RadView
    - SmartBear LoadComplete
    - SmartBear LoadUI Pro
    - WAPT Pro
    - SmartBear Load Ninja
    - Loadster
    - IBM Rational Performance Tester

    ## Open Source Tools
    - Apache JMeter
    - Gatling
    - K6.io
    - Locust
    - Tsung
    - Artillery
    - Taurus
    - The Grinder

## "Who"
- Testers play a key role in performance testing.
- Collaboration is essential between different parties.
    ## Parties Involved
    - **Testers:** Overall PT activities.
    - **Business Analysts:** Performance Requirements.
    - **Developers:** Application Issues.
    - **DevOps and DBA:** Infra and DB Issues.


[<< Volver al Inicio](../../README.md) | [Siguiente: Clase 2 >>](../02_Class/02_Class.md)