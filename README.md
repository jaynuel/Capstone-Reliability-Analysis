# Capstone-Reliability-Analysis
**Yeshiva University - Katz School of Science** <br>
**Data Analytics and Visualization MS** <br>
**Work done in collaboration with A.O. Olivera,** <br> 
**Mechanical & Electrical Engineering Student at**  
**University of Puerto Rico – Mayaguez Campus** <br>


**date:**          December, 2021 <br>
**from:**         Jesus Olivera, Capstone Project <br>

**subject:**    Reliability Analysis <br>

### Implementation of a novel combinatorial algorithm in conditional and redundancy systems using advanced computational techniques

![image](https://user-images.githubusercontent.com/71087767/141351706-ba85c7b6-de82-4e49-a7f5-9008965ec3cf.png)

#### Introduction<br>
The “k out of n” case refers to a reliability block diagram (RBD) that contains redundancy and components in fail mode. To obtain the total reliability, the Pascal Triangle coefficients must be used to know how many combinations exist depending on the number of total components and working components. Existing literature and methods only output how many combinations are possible, but do not output the exact combinations’ arrangements.

The novel algorithm, developed by A.O. Olivera, outputs all combination’s arrangements for a specific case. The function steps depend on three cases: Case 1 occurs when the number of working components is not equal to the number of failing components; Case 2 occurs when the number of working components equals the number of failing components; and Case 3, occurs when all components are failing, or all components are succeeding. The conditional reliability refers to mechanical, electrical or software arrangement in where their components/parts are not in series or parallel configurations. The actual solving procedure requires using Monte Carlos analysis with millions or billions of runs (because the application requires higher convergence factors). This study intends to use advanced computational techniques to effectively implement novel closed form solutions to conditional and redundancy systems. As a model to follow the complete process will be explained using a complex generic case study (~406 GB of data to be processed). 

#### Problem Statement<br>
National laboratories have shown interest in having closed form solutions to different hard reliability problems, making algorithms more computationally efficient while avoiding probabilistic analysis if the option of developing closed form solution is available. For this reason, a complex generic case study was shared with me to optimize the algorithm and perform a VV (Verification and Validation) analysis. The engineers develop an algorithm, but they are not able to fully run the script by the lack of computational techniques and capacity. There are two ways of solving the complex reliability case study (1) system reductions or (2) by pathways. The system reduction’s method approximates the total reliability. This project is focused on doing VV of the pathway’s methodology which results in an exact solution. Then, and error analysis will be done to determine system reduction effectiveness. 

![image](https://user-images.githubusercontent.com/71087767/141351745-3b124007-c7c8-40c9-909d-a89792935c45.png)

#### Objective<br>
The objective of this study is to solve the algorithm in conditional cases by optimizing its MATLAB code and reducing required computational resources by implementing advanced code, algorithm and compute optimization techniques. The results obtained will be compared with the proposed approximation (system reduction’s methodology).    

![image](https://user-images.githubusercontent.com/71087767/141351774-a40dbc3c-4eb8-45b6-893c-809737a3cf46.png)

#### Previous research and current knowledge<br>

The first section of this paper will provide an overview of the Comb() and conditional algorithms developed by A.O. Olivera, and the second portion of the paper will focus on optimizing the algorithm and enhancing computational resources to obtain the exact solution for the proposed case study; work developed by Jesus Olivera. 
Importance
The importance of obtaining the total reliability of a system resides in the ability of understanding how much effect each component has on the overall performance of a system, thus enhance product usability, performance, expected life, functionality, etc.

![image](https://user-images.githubusercontent.com/71087767/141352107-89153760-2aa6-419e-a258-d9cca3a48c0a.png)

#### Broader Impact<br>
Understanding the relationship and the effects each of the components have in a system will provide the necessary insights needed to increase its overall performance. Modern technology requires higher performance due to the dramatic increase in energy usage. Every day new technologies are developed posing unconventional configurations and requirements. Space, energy, automotive industry, and others are always looking for developing systems with higher efficiencies, in where higher systems efficiencies is proportional to higher reliabilities. Currently, it is only possible to obtain reliability data about an individual system by applying the proposed method, and the overall system reliability design can be obtained in minutes or second’s time laps. The process of calculating overall reliability will be moved from a probabilistic method that uses Monte Carlo to a close form solution, a discrete solution of an equation, which yields to a novel overall reliability design calculation.

![image](https://user-images.githubusercontent.com/71087767/141351857-68780d49-3d62-4096-94d6-9824fc4e06f9.png)




