Design and power optimization of 8T SRAM using NMOS footer-based power gating for low-power VLSI applications.

# Power Reduction in 8T SRAM using Power Gating
## Author
- **Chinmayi P R**  
  B.Tech Electronics and Communication Engineering  
  PES University, Bengaluru

## Overview
This project focuses on the design and power optimization of an 8-Transistor (8T) SRAM cell. The 8T architecture improves read stability by decoupling the read and write paths. Power reduction is achieved using NMOS footer-based power gating.

## Architecture
- 6T cross-coupled inverter core for data storage
- 2T read buffer controlled by Read Word Line (RWL)
- Separate Write Word Line (WWL) for write operation

## Power Optimization
An NMOS footer transistor is inserted in the ground path:
- ON state: Normal SRAM operation
- OFF state: Reduced leakage power during idle mode

## Simulation Results

| Parameter | Normal 8T SRAM | Optimized 8T SRAM |
|---------|---------------|------------------|
| Voltage | 659.9 mV | 655.5 mV |
| Current | 9.588 nA | 906.3 fA |
| Power | 6.328 nW | 0.6026 pW |


## Tools Used
- Cadence Virtuoso
- CMOS Technology Library  

## Conclusion
The optimized 8T SRAM design demonstrates significant leakage power reduction while maintaining operational stability, making it suitable for low-power VLSI and embedded applications.

