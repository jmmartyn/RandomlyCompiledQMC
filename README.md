# Randomly Compiled Quantum Monte Carlo
In ARXIVLINK, we develop *randomly compiled quantum Monte Carlo* (RC-QMC) as a framework to improve the accuracy and efficiency of quantum Monte Carlo simulation algorithms. We apply RC-QMC to both path integral Monte Carlo and the quantum trajectories method. 

Here we provide the associated code for this paper. This includes two notebooks: 
* `QDrift_PIMC_Ising.ipynb` - RC-QMC applied to path integral Monte Carlo (using the [QDrift protocol](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.123.070503)), exemplified on simulating the thermal state of the long-range Ising model. 
* `Randomly_Compiled_Quantum_Trajectories_BoseHubbard.ipynb` - RC-QMC applied to the quantum trajectories method (using [randomly corrected Trotterization](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.109.062431)), exemplified on simulating the dynamics of a dissipative Bose-Hubbard model. 

