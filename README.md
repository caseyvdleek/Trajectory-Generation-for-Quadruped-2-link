# Trajectory-Generation-for-Quadruped-2-link
The generation of smooth, steady motion gait trajectories for a quadruped with 2-link legs. These trajectories are synthesized using the original data from the 3-link legged quadruped obtained in the MSc(Eng) project as truth data in a non-linear least squares optimization.
In order to remove any discontinuities in the orginal end-effector trajectory minor changes in the link lengths and/or centre of motion coordinates were found to be feasible. The result is that a smooth end-effector is realised with mostly closed phase space trajectories.
From the Matlab code both the human-biped (red) and 'robot'-biped (cyan) trajectories are represented. Depending on which optimization algorithm is deployed, the initial variables search values and to a lesser extent the lower & upper bound values when using the Levenberg-Marquardt algorithm it is possible to synthesize trajectories that are human-biped, 'robot'-biped or hybrid versions where there is a transition from one configuration type to another whilst still generating the required end-effector trajectory.   
