# ARCH-COMP 2024
ARCH-COMP AINNCS Category 2024 Model Files

Event info: https://cps-vo.org/group/ARCH/FriendlyCompetition


## Benchmarks 

We plan to reuse benchmarks from 2023 but feel free to propose new benchmarks or modifications to existing ones: https://github.com/verivital/ARCH-COMP2024/issues/1

| Benchmark | Instance | Specification | Network | Visualization | Comment |
|-----------|----------|---------------|-----------|---------------|---------|
| [ACC](./benchmarks/ACC) | safe-distance | default | relu | distance over time | - | 
| [Airplane](./benchmarks/Airplane) | continuous | t\in[0,20] | relu | [2,7] | modified spec | 
| [Airplane](./benchmarks/Airplane) | discrete | t\in{0,1,...,20} | relu | [2,7] | modified spec | 
| [Attitude Control](./benchmarks/Attitude-Control) | avoid | default | sigmoid | [1,2] | - | 
| [Docking](./benchmarks/Docking) | constraint | default | tanh | [1,2] and [3,4] | - | 
| [Double Pendulum](./benchmarks/Double_Pendulum) | less-robust | Specification 1 | less robust | [3,4] | modified spec | 
| [Double Pendulum](./benchmarks/Double_Pendulum) | more-robust | Specification 2 | more robust | [3,4] | modified spec | 
| [NAV](./benchmarks/NAV) | standard | default | nn-nav-point | [1,2] | new | 
| [NAV](./benchmarks/NAV) | robust | default | nn-nav-set | [1,2] | new | 
| [QUAD](./benchmarks/QUAD) | reach | default | sigmoid | dim 3 over time | - | 
| [Single Pendulum](./benchmarks/Single_Pendulum) | reach | default | relu | 1 over time | modified spec | 
| [TORA](./benchmarks/Benchmark9-Tora) | remain | Specification 1 | relu | [1,2] and [3,4] | - | 
| [TORA (Heterogeneous)](./benchmarks/Tora_Heterogeneous) | reach-sigmoid | Specification 2 | sigmoid | [1,2] | - | 
| [TORA (Heterogeneous)](./benchmarks/Tora_Heterogeneous) | reach-tanh | Specification 2 | tanh | [1,2] | - | 
| [Unicycle](./benchmarks/Benchmark10-Unicycle) | reach | default | relu | [1,2] | - | 
| [VCAS](./benchmarks/VCAS) | `TODO` | default | `TODO` | relu | `TODO` | 


### [2023 Benchmarks](https://github.com/verivital/ARCH-COMP2023)

- Adaptive Cruise Controller (ACC)

- Airplane

- Attitude Control 

- Double Pendulum

- Single Pendulum

- QUAD

- TORA with heterogeneous and sigmoid controller

- TORA with ReLU controller (benchmark 9)

- Unicycle (benchmark 10)

- VCAS

- 2D Spacecraft Docking


### Competition History

Prior year reports:
- 2023: https://easychair.org/publications/paper/Vfq4b
- 2022: https://easychair.org/publications/paper/C1J8
- 2021: https://easychair.org/publications/paper/Jq4h
- 2020: https://easychair.org/publications/paper/Jvwg
- 2019: https://easychair.org/publications/paper/BFKs

Repeatability archives: https://gitlab.com/goranf/ARCH-COMP/

