# QCA-TLogic-Ripple-Carry-Adder

## What is QCA?
Quantum-dot Cellular Automata (QCA) is a nano-scale computing technology
that represents binary data using the position of electrons in quantum dots
rather than voltage levels. It offers:
- Ultra-low power consumption compared to CMOS
- Extremely high device density
- Faster switching at the nanometer scale

## Why Ripple Carry Adder?
The Ripple Carry Adder (RCA) is a fundamental arithmetic circuit used in
ALUs and processors. Implementing RCA in QCA demonstrates the feasibility
of building complete arithmetic logic in nano-scale technology, which is
critical for future ultra-low-power computing systems.

## Why T-Logic?
Traditional QCA design uses majority gates, which require complex wiring
routing and multi-layer crossings. **T-Logic** is an alternative QCA logic
family that:
- Reduces cell count compared to majority-gate designs
- Simplifies circuit layout
- Enables cleaner multilayer QCA structures
- Improves overall area efficiency

## Circuits Designed
| Circuit | Description |
|---------|-------------|
| T-Logic XOR Gate | Fundamental building block using QCA T-gates |
| Full Adder | Designed using T-Logic XOR and majority gates |
| Ripple Carry Adder (RCA) | Cascaded Full Adders for multi-bit addition |
| Ripple Carry Subtractor (RCS) | Subtraction using complement logic |
| Comparator | Magnitude comparison circuit in QCA |

## Key Results & Advantages
- Reduced cell count vs standard majority-gate QCA implementation
- Multilayer QCA structures eliminate wire crossing issues
- Validated all circuit outputs through QCA Designer simulation
- Demonstrates T-Logic as a viable alternative for arithmetic circuit design
- Compared the T-Logic approach with standard majority-gate-based QCA design

## Technology
| Tool | Purpose |
|------|---------|
| QCA Designer | Circuit design and simulation |
| T-Logic Gates | Alternative QCA logic family |
| Multilayer QCA | 3D wire crossing without signal interference |

## Tools Used
- **QCA Designer** — open-source QCA circuit design and simulation tool

## Author
**Sarisa Raghuveer** — B.Tech ECE, IIIT Sri City (2023–2027)
