```mermaid
graph TD
    A[Start Flight Procedures]

    A --> C[Parabola Sequence]
    C --> C1[Hypergravity Ascent Phase]
    C1 --> C1a[Pelican Case Locked - No Interaction]
    C1a --> C1b[Cameras/Arduino Active]

    C1b --> C2[Microgravity Phase]
    C2 --> C2a[Press External Button to Retract Actuators]
    C2a --> C2b[Automatic Fluid Dispense via Primary Pump]
    C2b --> C2c[Monitor Droplet Dynamics via Cameras]

    C2c --> C3[Level Flight Recovery]
    C3 --> C3a[Open Pelican Case]
    C3a --> C3b[Remove Used Tampons to Containers]
    C3b --> C3c[Replace Splatter Sheets - Top/Bottom]
    C3c --> C3d{Primary Pump Functional?}
    C3d -->|Yes| C3e[Install Fresh Tampons]
    C3d -->|No| C3g[Activate Backup Manual Fluid System]
    C3g --> C3h[Pre-Saturate Synthetic Vaginas]
    C3h --> C3e[Install Fresh Tampons]
    C3e --> C3i[Attach Tampons to Linear Actuators]
    C3i --> C3j[Close Pelican Case]

    C3j --> C4[Repeat for X Parabolas]
    C4 --> D[Post-Flight Procedures]
    D --> D1[Power Down All Systems]
    D --> D2[Secure Samples/Media]
    D --> D3[Document Anomalies]

    %% Styling for phase clarity
    style C1 fill:#FF5722,stroke:#E64A19 %% Hypergravity
    style C2 fill:#8BC34A,stroke:#689F38 %% Microgravity
    style C3 fill:#2196F3,stroke:#1976D2 %% Level Flight
    style C4 fill:#9C27B0,stroke:#6A1B9A %% Loop
    style D fill:#607D8B,stroke:#455A64 %% Post-Flight


graph TD
    A[Start Pre-Flight Procedures] --> B[Pack Secondary Bag]
    B --> B1[Prepare 27 Tampons: 3 For 6 Parabolas + 50% Margin]
    B --> B2[Prepare 18 Individual Containers for Used Tampons]
    B --> B3[Verify Backup Tampons/Containers & Labels on Containers]
    A --> C[Hardware Setup]
    C --> C1[Connect Microcontroller Power Supply to Aircraft Circuit - Pelican Case Bottom]
    C1 --> C2[Secure Wiring/Insulate Connections]
    C --> C3[Connect Tubing to IV Container - Synthetic Blood]
    C3 --> C4[Verify Label Tubing Paths]
    A --> D[Day-of Pre-Flight Tests]
    D --> D1[Flow Test: Tubing System Leak Check]
    D1 --> D1a{Leaks?}
    D1a -->|Yes| D1b[Adjust/Replace Tubing]
    D1a -->|No| D2[Linear Actuator Function Test]
    D2 --> D2a{Actuators Functional?}
    D2a -->|No| D2b[Diagnose/Replace Actuators]
    D2a -->|Yes| D3[Camera Verification]
    D3 --> D3a[High-Speed Camera: Frame Rate/Storage Check]
    D3 --> D3b[GoPro: Battery/Recording Confirmation]
    D3a --> D3c{Cameras Operational?}
    D3c -->|No| D3d[Troubleshoot/Replace Cameras or Single Camera System]
    D3c -->|Yes| E[Final Pre-Flight Review]
    E --> E1[Confirm Pelican Case Securement]
    E --> E2[Validate Power Supply for All Devices]
    E --> E3[Document Setup in Log]
    E --> F[Proceed to Flight Protocol]
    
    style A fill:#4CAF50,stroke:#388E3C
    style B fill:#FFC107,stroke:#FFA000
    style C fill:#2196F3,stroke:#1976D2
    style D fill:#9C27B0,stroke:#6A1B9A
    style E fill:#009688,stroke:#00796B
    style F fill:#4CAF50,stroke:#388E3C
```
