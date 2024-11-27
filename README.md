```mermaid
flowchart LR
    A[CPU] --> B{Initiate DMA}
    B --> C[DMA Controller]
    C --> D{Transfer Data Directly}
    D --> E{Interrupt CPU}
    E --> A
