# Development and Design of an Automatic Test Bench for Robot Motors
This document is a dynamic model of a hardware test bench for robot motor modules.

As a student project, I designed and built a specialized measurement
system that is able to perform complex testing procedures of robot motor modules. 
It both measures and controls motor current, torque, position, temperature and
its derivations – which form the basic key state variables that are important to characterize
a robot motor module. It is also able to 
perform highly automated testing procedures.  

The test rig was desigend with the idea in mind to create highly flexible testing environment 
that can easily be extended and adapted for future demands.

When running dynamic experiments, it is crucial to consider the inherent
dynamics of the test rig itself. Every component within the test rig can be described as an inertia and
an internal stiffness. This leads to a multy-body dynamics problem which I modelled in this
document. Providing the eigenfrequencies, inertia and stiffness, this part presents the basics for further dynamics analysis. As it includes
all components and considers their interactions, it ensures that the complete system is
able to work together.

Ferdinand Elhardt, Oct 2020
