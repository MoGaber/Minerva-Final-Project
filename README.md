This is my capstone project for my undergraduate university. 
Granular materials are large aggregates of solid particles (these can be sand, powders, or even grain like rice). They range in size from nanometers to centimeters and can be either wet or dry. These materials exhibit very interesting complex behaviors under certain conditions which makes it hard to categorize them as one of the three main known states of matter (solid, liquid, or gas). The reason for that is that they exhibit the behavior of each one of these states of matter but under different conditions. For example, granular materials can form heaps and withstand deformation when they are dropped from a container (imagine you have a container of sand that you empty in one place). This is the behavior of solids. Granular materials can also flow through pipes which is the behavior of liquids. They can also be compressed which is the behavior of gas (Mesri et al, 2009). These materials are exceptionally interesting for scientists and engineers because they have many applications in industrial processes (civil engineering, agriculture, and pharmaceutical processing) (Jaeger, 2000). These complex behaviors of the granular materials are what makes them a very interesting system to study -they seem to be a new phase of matter or at least one that is transitioning between the three phases.  

In this project, I’m going to study granular materials using a computational approach that depends on a discrete-models that can coarse-grain the microscopic interactions of the granular materials to reproduce the behaviors mentioned above. I will talk about the most popular models that were used to study granules, I will replicate a few of them to get a deeper understanding of how the models work and I will build an improved version that is able to reproduce experimentally observed behaviors. 


There are six main files:

- Baxter_Replication: This is a replication of the Baxter et al 1991 paper in which I rerproduce their discrete cellular automata model adn conduct more analysis. The notebook takes about 4 hours to run on a google cloud.
- LGA-FHP: This is my implementation of the lattice gas cellular autommata model.
- FHP-Modified: This is my modification to the LGA model so it can be more suitable for simulating granular materials. The notebook takes about 1 hour to run.
- Gaber_Model_Narrow_Pipe_Wave_Density: This file includes my simulation of the narrow pipe and the reproduction of the wave density and wave propagation. The notebook takes about 1.5 hours to run
- Gaber_Model_Flow_Rate_Graph: This file includes the flow rate simulation. The notebook takes about 2.5 hours to run
- Gaber_Model_Phase_Transition: This file includes the simulation conducted to reproduce the phase transition. The notebook takes about 2.5 hours to run.

