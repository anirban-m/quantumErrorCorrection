# Hamiltonian

Here we study the impact of a simple bit flip noise model with a specified number of noisy channels on energy estimation of a simple two qubit Hamiltonian

$
H=J_{XY} (XX+YY) +J_{Z} ZZ
$

# Noise model

one qubit errors<br>
QuantumError on 1 qubits. Noise circuits:<br>
  P(0) = 0.07, QasmQobjInstructions = [[{'name': 'x', 'qubits': [0]}]<br>
  P(1) = 0.93, QasmQobjInstructions = [[{'name': 'id', 'qubits': [0]}]<br>
NoiseModel:<br>
  Basis gates: ['cx', 'id', 'u1', 'u2', 'u3']<br>
  Instructions with noise: ['u3', 'u1', 'u2']<br>
  Qubits with noise: [0, 1, 2, 4]<br>
  Specific qubit errors: [('u1', [0]), ('u1', [1]), ('u1', [2]), ('u1', [4]), ('u2', [0]), ('u2', [1]), ('u2', [2]), ('u2', [4]), ('u3', [0]), ('u3', [1]), ('u3', [2]), ('u3', [4])]<br>
  
 # Error correction
 
 Three qubit bit-flip repititon code
 ![repititioncode](https://github.com/anirban-m/quantumErrorCorrection/blob/main/download%20(8).png)
