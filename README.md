# ITQC-laser-stabilization

This repository has been created as part of a semester project at ITQC.

data-collection-MOKU.ipynb contains code for using the PI controller as well as collecting data at the same time using the Moku:Pro. An RF generator is also part of the code. One can modify the code so that the MOKU does only RF generation, or only engages the controller or just collects data, or any combination of the above.

SINARA-Stabilizer.ipynb passes IIR parameters, that implement a PI controller, to the SINARA. Note that filter_design.py should be kept in the same directory while running the notebook.
