<b> CapSim </b><br /><br />

CapSim is a numerical model designed to simulate contaminant transport in sediments. It was primarily developed to model contaminant transport through sediment caps for the purposes of design but it can also be used to simulate contaminant migration in uncapped sediments (e.g. for the evaluation of natural recovery) and in-situ treatment of sediments. The model is built on a foundation of sediment and cap modeling dating back to 1991 and early versions were described in EPA guidance for capping in 1998 .  The current version is an extremely robust tool that includes capabilities for modeling contaminant transport in sediments under a wide range of conditions including: <br /><br />

•	Dynamics of multiple species with linked reactions in sediments, conventional and amended cap materials and sediment amendments<br /> 
•	Multiple layers of materials with widely varying physical and chemical conditions<br />
•	Diffusion/dispersion <br />
•	Bioturbation <br />
•	Groundwater upwelling and tidal (or other oscillating) flows<br />
•	Sediment consolidation <br />
•	Sediment deposition <br />
•	Linear and nonlinear sorption<br />
•	Equilibrium or non-equilibrium sorption <br />
•	Exchange at the sediment-water interface <br /><br />

CapSim is largely menu-driven program and gathers the input information by a series of input windows. It also contains a "solver" module in responsible for simulation and a "proprocessor" module to output the results. The current version CapSim is coded in Python 2.7 and required following Python modules:  <br />

•	Numpy<br />
•	Matplotlib<br />
•	PIL<br />
•	Py2exe<br />

To test the program, download Python 3.7 and the required modules. Then download all scripts and run 'capsim.py'. 

<b>Update summary</b><br />

This version of CapSim was adapted for compatibility with Python 3. The following changes were made:<br />

•	cPickle is no longer supported in Python 3, because the functionality was integrated into pickle. Replaced cPickle with pickle.<br />
•	All files to be pickled or unpickled read and written in bytes instead of text, for compatibility with pickle.
•	_winreg renamed to winreg
•	FileDialog, MessageBox, and Font are now imported from the Tkinter package
•	Replaced obsolete operator <> with synonym !=
