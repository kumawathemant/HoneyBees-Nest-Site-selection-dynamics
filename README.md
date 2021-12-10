# Hive Site Selection in Honeybee Swarms
A study of the dynamics of decision-making in honeybee swarms of arbitrary size N using multi-agent distributed control over a fixed, connected graph

The directories have the following content:

Code: 

- Brute Force Search - shows simulations for varying sized networks and each of their respective unfolding cases. This search was done through a brute force grid search in the Beta parameter space.
- Multi-Agent Simulation - Houses code that displays the dynamics of the HoneyBee Nest Site Selection. These files include the transient behavior, bifurcation characterization along with adaptive control methods.

# Generate_network has network paramerters stored 
# For Multiagent simulation with N=12 agents as mentioned in the report: Run HoneyBees_Bifurcation.m with figure2plot =2 
a. Change BA, BB values to change Beta values for the agents 
b. Total additional three experiments done in the code:
    Run the code with figure2plot = 3 for subcritical pitchfork. (Not mentioned in the report). Subcritical grpah seen when changing BA=1, BB =-1 to BA = 3, BB =-3
    Run the code with figure2plot = 4 for transient analysis of complete grpah with N=12 agents. Note this graph is different from the one in figure 2
# For adaptive control, run adaptive.m. You may change y_threshold, or BA, BB values to change decision threshold, and Beta values respectively. 

Still confused, drop a mail at hkumawat6@gatech.edu

Data:
    Holds the results from each of the cases described above (.fig and .mat files)
