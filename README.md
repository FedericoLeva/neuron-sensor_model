# neuron-sensor_model
- The SPICE NETLIST files are supplied to give examples
of transient and transfer-function circuit simulation analysis. 
Each simumlation containts active/passive coupled to intracellular/extracellular 
sensing circuits. The transient analysis include different AP generation
mechanisms: HH and external voltage source boundary for intracellular,
and transmembrane current sources for extracellular. Please, include
inside the "SPICE_circuit_for_transient_analysis.cir" file the:
Injm.txt, Ijm.txt, Inm.txt, K_memristor_HH.txt, Na_memristor_HH.txt,
and suitable OpAmp model library paths.


- The Sentaurus simulation input decks are supplyed to give examples
of mixed-mode TCAD-circuit transient simulation analysis.
Sentaurus Mesh inputs for extracellular mushoorm and intracellular 
nanowire electrodes are given as starting point to run the SDevice 
inputs for passive-extracellular and active-intracellular 
mixed-mode TCAD-circuit transient simulations. In these cases, 
external voltage source boundary for intracellular, and transmembrane 
current sources for extracellular generate the AP. Additionally, the Sentaurus
parameter file couples the SDevice inputs to set the intrinsic model paramers.

- The datasets include the data shown in the figures througout the paper as ASCII files.
In addition, a comparison between the analytical tfs with those extracted by AC circuit
simulation are supplied.
 
They are intended to help to verify that the model actually works.
