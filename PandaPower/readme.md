# PandaPower Data

This section contains a set of Jupyther notebook dedicated to power system analysis using the well-know python-based software PandaPower.



# Example: Run an AC power flow in PandaPower

Created by: FGL, 13/03/2025 

Email: [fglongatt@fglongatt.org](fglongatt@fglongatt.org)

GitHub respositorty:  [https://github.com/fglongatt ](https://github.com/fglongatt) 

This Jupyter notebook is created to import a pre-existing network model inside PandaPower, present information about the network model, and finally run a power flow showing the numerical results.
This notebook uses the case9.json.

The Pandapower networks module contains example networks, simple test networks, randomly generated networks, CIGRE test networks, IEEE case files and synthetic low voltage networks from Georg Kerber and Lindner et al. and Dickert et al.

Read more here: https://pandapower.readthedocs.io/en/v2.0.0/networks.html#

This example uses the json file **case9.json**, whose data origin is PYPOWER. 
**NOTE: PandaPower website claims this network was published in Anderson and Fouad’s book ‘Power System Control and Stability’ for the first time in 1980.
However, this is a modified version of the original network.**
![image](https://github.com/user-attachments/assets/a4da1035-6e1f-4fcf-8777-d52537b1c773)

# Example: Run an Optimal Power Flow (OPF) in PandaPower
Created by: FGL, 13/03/2025 

**Email:** [fglongatt@fglongatt.org](fglongatt@fglongatt.org)

**GitHub respositorty:**  [https://github.com/fglongatt ](https://github.com/fglongatt) 

This Jupyter notebook is created to import a pre-existing network model inside PandaPower and run an **optimal power flow (OPF)**, showing the numerical results, including the active power losses in the network. 
