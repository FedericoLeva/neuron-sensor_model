# HH_neuron_model
- The SPICE NETLIST files are supplied to give examples
of transient and transfer-function circuit simulation analysis. 
Each simumlation containts active/passive coupled to intracellular/extracellular 
sensing circuits. The transient analysis include different AP generation
mechanisms: HH and External voltage source boundary for intracellular.
and Transmembrane current sources for extracellular. Please, include
inside the "SPICE_circuit_for_transient_analysis.cir" code the:
Injm.txt, Ijm.txt, Inm.txt, K_memristor_HH.txt, Na_memristor_HH.txt,
and a suitable OpAmp model library paths.


- The Sentaurus simulation input decks are supplyed to give examples
of mixed-mode TCAD-circuit transient simulation analysis.
Additionally, Sentaurus Mesh
 
They are intended to help to verify that the model actually works.
