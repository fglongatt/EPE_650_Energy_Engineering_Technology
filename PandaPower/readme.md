# PandaPower Data

This section contains a set of Jupyther notebook dedicated to power system analysis using the well-know python-based software PandaPower.



# Example: Run an AC power flow in PandaPower

Created by: FGL, 13/03/2025 

Modified: 14/02/2026

Email: [fglongatt@fglongatt.org](fglongatt@fglongatt.org)

GitHub respositorty:  [https://github.com/fglongatt ](https://github.com/fglongatt) 

This Jupyter notebook is created to import a pre-existing network model into PandaPower, present information about the network model, and finally run a power flow to show the numerical results.
This notebook uses the case9.json.

The Pandapower networks module contains example networks, simple test networks, randomly generated networks, CIGRE test networks, IEEE case files, and synthetic low-voltage networks from Georg Kerber, Lindner et al., and Dickert et al.

Read more here: https://pandapower.readthedocs.io/en/v2.0.0/networks.html#

This example uses the json file **case9.json**, whose data origin is PYPOWER. 
**NOTE: PandaPower website claims this network was published in Anderson and Fouad’s book ‘Power System Control and Stability’ for the first time in 1980.
However, this is a modified version of the original network.**
![image](https://github.com/user-attachments/assets/a4da1035-6e1f-4fcf-8777-d52537b1c773)

# Example: Run an Optimal Power Flow (OPF) in PandaPower
Created by: FGL, 13/03/2025 

Modified: 14/02/2026

**Email:** [fglongatt@fglongatt.org](fglongatt@fglongatt.org)

**GitHub respositorty:**  [https://github.com/fglongatt ](https://github.com/fglongatt) 

This Jupyter notebook is created to import a pre-existing network model inside PandaPower and run an **optimal power flow (OPF)**, showing the numerical results, including the active power losses in the network. 

## Indicative publications regarding generation costs:

(2022). "Cost Functions for Generation Dispatching in Microgrids for Non-Interconnected Zones in Colombia."  Energies, 15(7), 2418. https://doi.org/10.3390/en15072418] (https://www.mdpi.com/1996-1073/15/7/2418)

L. Nam Hai Pham et al., "Real-Time Cyber-Physical Power System Testbed for Optimal Power Flow Study Using Co-Simulation Framework,"  in IEEE Access, vol. 12, pp. 150914-150929, 2024, doi: 10.1109/ACCESS.2024.3472748. (https://ieeexplore.ieee.org/document/10704672)
