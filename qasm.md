# OpenQASM


OpenQASM is a language that allows quantum developers to represent quantum circuits in a programmatic way developed for IBM quantum experience. There is a direct equivalence between a circuit drawing and its QASM representation. The language is specified in the [OpenQASM paper](https://arxiv.org/abs/1707.03429) and is a quick way to get started developing quantum circuits.

## Summary

The goal of QASM is to "enable experiments with small depth quantum circuits." QASM is an intermediate representation used to describe simple quantum circuits as basic code blocks -- straight line code segment with no branches. QASM can be used to describe a circuit and generate a diagram, or QASM can be written from a diagram. The purpose of a simple language that has a one to one correspondence with quantum circuits is to create human readable quantum code that can be used standalone, or as part of a more fully featured framework. Qiskit uses QASM as an intermediate representation, a kind of assembly language for quantum circuits. In fact you can easily import QASM code directly into qiskit and circuits created in qiskit are rendered into QASM for simulation or execution on quantum hardware. 

The language itself has elements of C and Assembly code with a small set of operations. Storage consists of quantum and classical registers - 1d arrays of bits or qubits. The operation set (detailed in table 1 [here](https://arxiv.org/abs/1707.03429)) is small but a parameterized unitary gate allows users to create custom gates in addition to predefined ones. Measurements can be made on qubits and stored in classical registers.  

While the scope of OpenQASM is limited to simple circuits, most popular algorithms have previous QASM implementations. The simplicity of the implementation makes QASM an ideal place to start for developers that want to learn to author and simulate quantum circuits.

## Strangeworks links

Some library entries using QASM

[Play with one qubit](https://quantumcomputing.com/strangeworks/play-with-one-qubit)

[Solve the RubiQ's sphere](https://quantumcomputing.com/strangeworks/solve-this-rubiq-s-sphere)

[For whom the Bell entangles](https://quantumcomputing.com/strangeworks/for-whom-the-bell-entangles)

[Quantum walk, four nodes](https://quantumcomputing.com/strangeworks/quantum-walk-four-nodes)


## External links

[OpenQASM paper](https://arxiv.org/abs/1707.03429)

[OpenQASM repository](https://github.com/Qiskit/openqasm)

[OpenQASM documentation](https://qiskit.github.io/openqasm/)

## Code samples

```
# declare quantum and classical registers
qreg qname[size];
creg cname[size];

# Hadamard gate
H a;

#controlled not 
CX a, b;

# define generic unitary gate 
U(theta,phi,lambda) a;

# measure takes qubit and puts it into classical register
measure qname -> cname;
```