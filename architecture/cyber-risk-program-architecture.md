# Cyber Risk Management Program Architecture

The diagram below illustrates how the components of the cyber risk management program interact across governance, risk evaluation, operations, and executive reporting.

```mermaid
flowchart TD

A[Cyber Risk Identification]
B[Risk Assessment]
C[Risk Scoring Model]
D[Risk Register]
E[Risk Ownership Assignment]
F[Risk Treatment Decision]
G[Risk Mitigation]
H[Risk Acceptance]
I[Risk Monitoring]
J[Executive Risk Reporting]
K[Cyber Risk Committee Oversight]

A --> B
B --> C
C --> D
D --> E
E --> F
F --> G
F --> H
G --> I
H --> I
I --> J
J --> K
