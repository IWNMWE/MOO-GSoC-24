![GSoC mlpack image](src/gsoc-mlpack.png)

**Organization: [mlpack](https://github.com/mlpack)**

**Project: [Adding NSGA-3 and AGE-MOEA Multi Objective Optimizers](https://summerofcode.withgoogle.com/programs/2024/projects/CIHE5bCy)**

**Mentors: [Marcus Edel](https://github.com/zoq) and [Omar Shrit](https://github.com/shrit)**


Here are the outcomes achieved by the optimizers and test suites I developed this summer.
| ![NSGA3 On DTLZ1](src/dtlz1.png) | ![AGEMOEA On Fleming](src/fleming.png) | ![AGEMOEA On ZDT3](src/ZDT3.png) 
|:-------------------------:|:-------------------------:|:-------------------------:|
| NSGA3 On DTLZ1 | AGEMOEA On Fleming | AGEMOEA on ZDT3 |
| ![MOEAD On MAF1](src/MAF1.png) | ![MOEAD On MAF3](src/MAF3.png) | ![AGEMOEA On ZDT1](src/ZDT.png)
| MOEAD On MAF1 | MOEAD On MAF3 | AGEMOEA on ZDT1

## Project Overview.

Multi-objective optimization is crucial across various fields as it enables balancing conflicting goals, such as performance versus cost in engineering or profit versus impact in economics. This approach leads to more comprehensive and effective solutions, better suited to complex real-world challenges.


This project aimed to enhance ensmallen's capabilities in multi objective optimization by implementing optimizers such as AGE-MOEA and NSGA-3 and various problems from the MAF Benchmark test suite. 

## Project Objectives

- Implement the AGE-MOEA optimizer algorithm. [Annibale Panichella](https://doi.org/10.1145/3321707.3321839)
- Implement the NSGA-3 optimizer algorithm. [Deb et al. 2013](https://www.egr.msu.edu/~kdeb/papers/k2012009.pdf)
- Implement the MAF benchmark test suite. [Cheng et al. 2017](https://www.researchgate.net/publication/315446832_A_benchmark_test_suite_for_evolutionary_many-objective_optimization)
- Implement the Inverse Generational Distance metric.
- Conduct thorough testing to ensure the reliability and effectiveness of the implemented algorithms.
- Provide comprehensive documentation for the newly added optimizers and test suite.

## Current State of the project.

AGE-MOEA and IGD performance indicator have been fully implmentedf and merged into teh repo along with their respective documententation and tests.

MAF and NSGA-3 has been fully implemented and tested. Some of the MAF problems have  been also been added as tests for optimizers.The PR containing the MAF changes have been approved and are ready to merge.

Simulated Binary Crossover (SBX) has been implemented as a part of the AGEMOEA implementation PR and Hyperplane Normalization has been implemented as a seperate classs in the NSGA-3 implementation PR.

Here is an overview of the pull requests (PRs) I submitted:

## Challenges
There were serveral challenges faced throughout all stages of this project: 

**Debugging Complexity:** Debugging these optimizers turned out to be the biggest challenge faced during the whole project.


