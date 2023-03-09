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

## Acknowledgments

* The running example is based on the [SOLITUDE project](https://github.com/Solitude-SAMR/UWV_RAM).
