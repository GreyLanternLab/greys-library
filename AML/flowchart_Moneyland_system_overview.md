```mermaid
flowchart LR
  %% Moneyland — system overview (based on Bullough's themes)
  %% Copy-paste into Obsidian / GitHub markdown that supports Mermaid.

  A[Source of Wealth\n(extraction / illicit gains)] -->|cashflow| B[Secrecy & Distance\n(offshore jurisdictions)]
  B --> C[Structures\n(shell companies / trusts / nominees)]
  C --> D[Facilitators\n(lawyers • accountants • bankers)]
  D --> E[Integration / Parking\n(real estate • funds • art • businesses)]
  E --> F[Legitimacy & Protection\n(passports • PR • philanthropy • lobbying)]
  F --> G[Influence & Impunity\n(political power • weak enforcement)]
  G -->|feedback loop: more access| D

  %% Pressure points
  subgraph P[Counter-Forces / Friction]
    P1[Investigative journalism & leaks]
    P2[AML compliance & reporting]
    P3[Beneficial ownership registers]
    P4[Sanctions & asset freezes]
    P5[Anti-SLAPP / legal reform]
  end

  P1 -. exposes .-> C
  P2 -. flags .-> D
  P3 -. reveals .-> C
  P4 -. blocks .-> E
  P5 -. protects critics .-> F
```
