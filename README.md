# 2024-large-deviation-full-counting-statistics-in-adiabatic-open-quantum-dynamics 

Codes for reproducing the data and figures of the article entitled "Large Deviation Full Counting Statistics in Adiabatic Open Quantum Dynamics"

Authors: Paulo J. Paulino, Igor Lesanovsky, and Federico Carollo

Journal: Physical Review Letters, 05/2024

Arxiv: https://arxiv.org/abs/2401.11933

Basic Information about the Directories:
  - The codes are organized in Jupyter notebooks, written in Python.
  - The codes require NumPy, SciPy, QuTiP, and Matplotlib.

Folder Structure:
  - Each notebook is self-contained, representing one part of the data.
  - The "figures" folder contains a file .svg, where the figures were post-processed (adjusted font size, font style, legend size, etc.).

  - Fig. 2
    1. The Jupyter notebook **Fig2_AdiabaticDynamics.ipynb** generates the data for Figure 2.
    2. The notebook **Fig2_AdiabaticDynamics_NumericalCheck.ipynb** checks the numerical results of Figure 2. The time-evolution of the *biased* density matrix can be unstable for large τ and s. This notebook employs a method that is slower but more robust against possible errors due to the stiffness of the differential equation.
    
  - Fig. 3
    1. The Jupyter notebooks **Fig3_Trajectory_Entropy.ipynb** and **Fig3_Trajectory_BlinkingSystem.ipynb** generate the data of the trajectories for Figure 3.
    2. The notebook **Fig3_RateFunctionMap_entropy.ipynb** and **Fig3_RateFunctionMap_BlinkingSystem.ipynb** generate the phase map for the rate function depicted in Figure 
    3. The notebook **Fig3_FiniteTau_error.ipynb** generates the data for estimating the error of the adiabatic approximation for the activity in function of $\gamma \tau$. 
  
  - Fig. SM
    1. The Jupyter notebooks **FigSM_Trajectory_Act.ipynb** and **Fig3_Trajectory_BlinkingSystem.ipynb** generate the data of the trajectories for Figure 3.
    2. The notebook **FigSM_RateFunctionMap_Activity.ipynb** and **FigSM_Trajectory_Activity.ipynb** generate the figure in the SM. 
  
  - Plotting. 
    1. The Jupyter notebooks **Plotting_Fig2.ipynb**, **Plotting_Fig3.ipynb**, and **Plotting_FigSM.ipynb** read the generated data and plot them.
      
  - Figs editing 
    2. The figures are post processed in the .svg file in the folder "Figures". 
