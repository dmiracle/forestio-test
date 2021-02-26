# QASM
[link to project page]()

https://arxiv.org/abs/1707.03429

https://github.com/Qiskit/openqasm

QASM is a language that allows qdevs to represent quantum circuits in a programmatic way developed for IBM quantum experience.

## Summary

"enable experiments with small depth quantum circuits" [1]

intermediate representation

basic block -- straight line code segment with no branches.

possible use modes: QASM -> Circuit Diagram or Circuit Diagram -> QASM

simple human readable language that describes a quantum circuit.

C / Assembly like language

Storage consists of quantum and classical registers - 1d arrays of bits or qubits

`qreg name[size];`

controlled not `CX a, b`

general unitary gate `U(theta,phi,lambda) a;`

define custom user defined gates

measure takes qubit and puts it into classical register `measure qb -> cb`

see table 1 in paper

## Strangeworks links


## External links


## Code samples