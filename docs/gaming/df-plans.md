# Fortress Plan

```mermaid  
flowchart LR

    A1[" "] --- A2["Farm"] --- A3[" "]
    B1[" "] --- B2["Stairs"] --- B3[" "]
    C1[" "] --- C2["Magma"] --- C3[" "]

    A1 --- B1
    A2 --- B2
    A3 --- B3
    B1 --- C1
    B2 --- C2
    B3 --- C3

    style A2 fill:#2e7d32,color:#fff
    style B2 fill:#455a64,color:#fff
    style C2 fill:#b71c1c,color:#fff