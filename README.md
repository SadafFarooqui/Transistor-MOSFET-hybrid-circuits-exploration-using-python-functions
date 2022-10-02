# Transistor-MOSFET-hybrid-circuits-exploration-using-python-functions

The cell operations like makegraph visualized the netlists as graph that can be manipulated and treated as a set of nodes and edges for better results and prompt discoveries in the future.
The findReplace cell operation enable the replacement of any NET like IN001 to VDD00 to see how it affects the output and structure.
The short_cct and open_cct operations are unarguably the most helpful operations in the circuit that determine what devices are the most crucial for the logic function’s implementation and which ones can be removed without changing the truth table of the logical operation.
The cell operations that are changing the device type like changeMRpoles and changeMOSFET resulted in running simulations after switching poles and replacing NMOS with PMOS and vice versa to see if the logical operation is implemented identically or not.
The commonsubgraphs function highlights the isomorphic or structurally similar subunits in the circuit that leads to determine if a particular subgraph is responsible for the characteristics of the circuit.
The above cell operations and the simulations ran afterwards on the resultant circuits serve as an algorithm for the minimality check which will identify cells and devices that could be removed or replaced by other cells.
The internal lines, input and output lines of a circuit are mapped with the inputs, internal lines and output of the circuit un comparison. The GND00 and VDD00 terminals however remain unchanged.
Some of the common subgraphs contribute to logical functions’ implementation while some are just random repeated structures in several circuits.


![image](https://user-images.githubusercontent.com/82878896/193475301-81eacb50-f75e-4f5a-8d72-d4dc9fe47f07.png)
