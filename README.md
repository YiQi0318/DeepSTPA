# STPA for Learning-Enabled Systems: A Survey and A New Method

## Description
* DeepSTPA control loop  
![Image text](https://raw.githubusercontent.com/YiQi0318/DeepSTPA/main/IMG-folder/ftp.png)
DeepSTPA control loop structures (grey shaded) in addition to the traditional STPA control loop (green shaded).
The horizontal axis signifies the ML lifecycle highlighting how data is being processed, while the vertical axis signifies finegrained functionalities and development activities. The solid line signifies control action, and the dashed line represents feedback information. The boxes filled with same colour represent the same artifacts but appear in different ML lifecycle stages.

* The control loop of running example using DeepSTPA  
![Image text](https://raw.githubusercontent.com/YiQi0318/DeepSTPA/main/Running_example_DeepSTPA.png)
This figure shows the control loop of running example using DeepSTPA. Each purple number denotes a component-wise control structure, 
while the yellow numbers show the control loop inside components. 
The blue arrows suggest that the component can delve into the control loops of stage on a functionality/activity dimension. 
The red solid line represents the control operation and the green solid line depicts the feedback process.

* The complete safety analysis results with running example using DeepSTPA (version 1)  
We used DeepSTPA to analyse the running example. This is the first version, and I will continue to update it later.

* We present our survey on 29 papers selected through a systematic literature search. We summarise and compare relevant research from five perspectives (attributes of concern, object under study, modifications to STPA, derivatives of the analysis, and process modelled as a control loop) to conclude insights.

| Year | Paper List | Attributes of Concern | Object under Study | Modification of the Method | Derivatives of the Analysis | Process modelled as a Control Loop |
|     :---:      |     :---:      |     :---:      |     :---:      |     :---:      |     :---:      |     :---:      |
| 2015 | [1](https://elib.uni-stuttgart.de/handle/11682/3550) | Safety | N/A | Yes (XSTAMPP) | Requirements | Operation Process|
| 2016 | [2](https://ieeexplore.ieee.org/document/7527748) | Safety, Privacy | Smart Television | Yes (STPA-priv) | Requirements | Operation Process|
| 2017 | [3](https://www.sciencedirect.com/science/article/pii/S1877705817312109) | Safety | Autonomous Vehicle | No | Requirements, New-architecture | Operation Process|
| 2017 | [4](https://ieeexplore.ieee.org/document/8054835) | Safety, Privacy | E-health | No | Requirements | Operation Process|
| 2017 | [5](https://www.sciencedirect.com/science/article/pii/S1877705817312079) | Safety | Drone | No | Requirements | Operation Process|
| 2018 | [6](https://pureportal.coventry.ac.uk/en/publications/integrating-autonomous-vehicle-safety-and-security-analysis-using) | Safety, Security | Autonomous Vehicle | Yes (STPA with six-step model) | Requirements | Development Process, Operation Process|
| 2018 | [7](https://www.sciencedirect.com/science/article/pii/S0925753517309876) | Safety | Robotic Flight Simulator | Yes (STPA with UPPAAL) | Requirements, New-architecture | Operation Process|
| 2019 | [8](https://www.sciencedirect.com/science/article/pii/S2214212619302042) | Safety, Security | Aeronautic | Yes (STPA-sec) | Requirements | Operation Process|
| 2019 | [9](https://drops.dagstuhl.de/opus/volltexte/2019/10338/) | Safety, Security | Autonomous Vehicle | No | Requirements, Test-case | Operation Process|
| 2019 | [10](https://www.matec-conferences.org/articles/matecconf/abs/2019/22/matecconf_icsc_eswc2018_02002/matecconf_icsc_eswc2018_02002.html) | Safety | Autonomous Ship | No | Requirements, Test-case | Operation Process|
| 2020 | [11](https://ieeexplore.ieee.org/document/9282673) | Safety, Security | Autonomous Vehicle | Yes (STAMP SnS) | Requirements | Development Process, Operation Process |
| 2020 | [12](https://www.sciencedirect.com/science/article/pii/S1110016820303045) | Safety | Collaborative Robots | Yes (STPA with Bowtie) | Comparative Study | Operation Process|
| 2020 | [13](https://ajss.dz/index.php/ajss/article/view/100) | Safety | Autonomous Mobile Multi-robots | Yes (STPA with FTA) | Requirements | Operation Process|
| 2021 | [14](https://ieeexplore.ieee.org/document/9722016) | Safety | Automatic Crane | No | Requirements | Operation Process |
| 2021 | [15](https://ieeexplore.ieee.org/document/9653486) | Safety | Autonomous Vehicle | No | Requirements | Operation Process |
| 2021 | [16](https://www.sciencedirect.com/science/article/pii/S2405896321007837) | Safety | Collaborative Robots | No | Requirements | Operation Process|
| 2021 | [17](https://www.sciencedirect.com/science/article/pii/S0951832021001551) | Safety | Autonomous Vehicle | No | Requirements, Test-case | Operation Process|
| 2021 | [18](https://www.sciencedirect.com/science/article/pii/S0951832021001745) | Safety | Autonomous Ship | Yes (STPA with UFoI-E) | Comparative Study | Operation Process|
| 2021 | [19](https://ieeexplore.ieee.org/document/9582542) | Safety | Autonomous Vehicle | Yes (SysML-STPA) | Requirements, New-architecture | Operation Process|
| 2021 | [20](https://asmedigitalcollection.asme.org/risk/article-abstract/8/3/031104/1115198/Comparison-of-the-HAZOP-FMEA-FRAM-and-STPA-Methods?redirectedFrom=fulltext) | Safety | Autonomous Vehicle | No | Comparative Study | Operation Process|
| 2021 | [21](https://www.sciencedirect.com/science/article/pii/S0925753520305348)| Safety | Unmanned Underwater Vehicle | Yes (SE-STPA) | Requirements | Operation Process|
| 2021 | [22](https://www.iieta.org/journals/ijsse/paper/10.18280/ijsse.110101) | Safety | Autonomous Mobile Multi-robots | Yes (STPA with AHP) | Requirements | Operation Process|
| 2021 | [23](https://www.sciencedirect.com/science/article/pii/S0029801821000044) | Safety | Autonomous Ship | Yes (STPA-SynSS) | Requirements | Operation Process|
| 2022 | [24](https://iopscience.iop.org/article/10.1088/1742-6596/2311/1/012021/meta) | Safety | Autonomous Ship | No | Requirements | Operation Process|
| 2022 | [25](https://ieeexplore.ieee.org/document/9985097) | Safety | Autonomous Vehicle | No | Requirements | Operation Process|
| 2022 | [26](https://link.springer.com/chapter/10.1007/978-3-031-16245-9_3) | Safety | Autonomous Mobile Multi-robots, Collaborative Robots | No | Requirements, Test-case | Operation Process|
| 2022 | [27](https://www.sciencedirect.com/science/article/pii/S0029801822019266) | Safety, Reliability | Autonomous Ship | Yes (STPA with SLIM) | Requirements | Operation Process|
| 2022 | [28](https://link.springer.com/chapter/10.1007/978-3-031-14835-4_11) | Safety | N/A | Yes (STPA with Multilevel Runtime Monitoring) | Requirements | Operation Process|
| 2023 | [29](https://www.sciencedirect.com/science/article/pii/S0951832023000534) | Safety | Autonomous Mobile Multi-robots | Yes (STPA with SPN) | Requirements | Operation Process|

## Acknowledgment

* The running example is based on the [SOLITUDE project](https://github.com/Solitude-SAMR/UWV_RAM).
