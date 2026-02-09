# Architecture

```mermaid
graph LR
    Executor --> Agent/Environment
    Evaluator --> Executor
    Evaluator --> Metrics
```

## Components
* Environment
* Executor/Runner
* Metrics
* Evaluator

## Data sources
* CyBench
* CAIBench