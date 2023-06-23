# QW
Hello! we are team Quanta.

This repository contains code that produces simulation on quantum walk from our team members. 
We solve the problem number 7, whose subject is quantum_walk in quantum hackathon.

<Folder Number 1> : Solved the number 1, Implementing a quantum walk

____________________________________________________________________________________________________________________________________
<Folder Number 2> : Solved the number 2, Noise analysis

1)Number2.ipynb : Implementation quantum walk plots on a ibm-canberra
2)problem2_transpile.ipynb :the plot of the depth measured during the transpile stage.and Plot the number of remaining two-qubit gates after transpiling the circuit.
____________________________________________________________________________________________________________________________________
<Folder Number 3> : Solved the number 3, Error mitigation strategies. 

1)Number3_3rd_suggestion_machinelearning.ipynb :make EfficientSU2 Circuit mimic the original wavefunction!

2)Number3_suggestion2_mitigation_via_reset.ipynb : Next, let me introduce the error mitigation strategy using the reset function, as shown on slide 23.To solve Problem 1, we designed a circuit that implements a shift operation that can be applied to arbitrary states. However, by setting the initial state to a specific state, |0000000111>, we only need to calculate the shift operator for a few possible states. This allowed us to significantly reduce the circuit depth and the number of CNOT gates.


3)partition_method.ipynb :  It's about suggestion 1. (Slide number20) In this circuit, I used 8 qubits to represent the -15 to 15 space, using control qubits of maximum size 4. Compared to the initial circuit we implemented, although more qubits are used, considering the use of a maximum of 5 control qubits, it can be considered significant.
