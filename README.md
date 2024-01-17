# 2024-large-deviation-full-counting-statistics-in-adiabatic-open-quantum-dynamics 

Codes for reproducing the data and figures of the draft entitled "Large Deviation Full Counting Statistics in Adiabatic Open Quantum Dynamics"

Authors: Paulo J. Paulino, Igor Lesanovsky, and Federico Carollo

Basic Information about the Directories:
  - The codes are organized in Jupyter notebooks, written in Python.
  - The codes require NumPy, SciPy, QuTiP, and Matplotlib.

Folder Structure:
  - Each notebook is self-contained, representing one part of the data.
  - The "figures" folder contains a file .svg, where the figures were post-processed (adjusted font size, font style, legend size, etc.).
  - The Jupyter notebook **Fig2_adiabatic_dynamics.ipynb** generates the data for Figure 2.
  - The notebook **Fig2_adiabatic_dynamics_numerical_check.ipynb** checks the numerical results of Figure 2. The time-evolution of the *biased* density matrix can be unstable for large τ and s. This notebook employs a method that is slower but more robust against possible errors due to the stiffness of the differential equation.
  - The Jupyter notebooks **Fig3_trajectory_activity.ipynb** and **Fig3_trajectory_entropy.ipynb** generate the data of the trajectories for Figure 3.
  - The notebook **Fig3_rate_function_map_entropy.ipynb** and **Fig3_rate_function_map_activity.ipynb** generates the phase map for the rate function depected in Figure 3.
  - The notebook **Fig3_finite_tau_error.ipynb** generates the data for estimanting the error of the adiabatic approximation for the activity in function of $\gamma \tau$. 
  - The Jupyter notebooks **Plotting_Fig2.ipynb** and **Plotting_Fig3.ipynb** read the generated data and plot them.
  - The figures are post processed in the .sgv file in the folder "Figures". 
