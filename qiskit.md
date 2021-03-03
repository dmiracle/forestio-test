# [Qiskit](https://qiskit.org/)

Fully featured IBM behemoth, tools for q-bending.

> Qiskit [quiss-kit] is an open source SDK for working with quantum computers at the level of pulses, circuits and application modules.


## Summary
- access to circuits
- hardware access
- noise mitigation
- quantum algorithms

Qiskit is the big-boy in the quantum computing space. The framework covers a broad range of quantum topics. Qiskit gives users access to the fundamentals through circuit building. It lets users explore the well known algorithms in the quantum space, think Shor, Grover, VQE, QAOA -- all the famous ones. In addition IBM has experts in a range of applications from finance, machine learning and chemistry building industry specific quantum applications. Finally qiskit has simulators that can get users ready to deploy their code on to actual quantum computers, and since it's IBM, they have actual quantum computers. If you were stuck on a desert island with a dilution fridge and could only bring one framework, you would not regret bringing qiskit.


## Qiskit elements
![](imgs/avatar.png)
### Terra
> Terra provides the foundations for Qiskit. It allows the user to write quantum circuits easily, and takes care of the constraints of real hardware. 

The fundament of qiskit is terra. Terra contains all the building blocks for creating circuits, designing experiments, and visualizing results. The data structures that make up Providers, Backends, Jobs, and Results are defined in Terra. 

```
qiskit.circuit
qiskit.pulse
qiskit.transpiler
qiskit.providers
    Provider
    Backend
    Job
    Result
qiskit.quantum_info
qiskit.visualization
```
### Aer
> Aer is a high performance simulator for quantum circuits that includes noise models 
In order to get code ready to run on real hardware it is important to be able to run experiments on simulators. These simulators are defined in Qiskit-Aer. On the strange works platform we give users access to the simulators built into the Aer package. These include the standard qasm-simulator that can run a quantum circuit many times and display a histogram of measurement results. The aer state-vector simulator will run a single iteration of a circuit, maintaining and displaying state vector information so you can get that sweet-sweet phase info. Pulse simulators allow developers to investigate noise effects and unitary simulators weill reduce circuits to unitary matrices that can be used in further calculations.

### Aqua
> Quantum Algorithms & Applications in Python

### Ignis
> Ignis provides tools for quantum hardware verification, noise characterization, and error correction. 

## Strangeworks Links

[Roll with the demand](https://quantumcomputing.com/strangeworks/roll-with-the-demand)

[Teleport a fly](https://quantumcomputing.com/strangeworks/teleport-a-fly)

[Shor: tales from decrypt](https://quantumcomputing.com/strangeworks/shor-tales-from-decrypt)

[QFT: qubits in disguise](https://quantumcomputing.com/strangeworks/qft-qubits-in-disguise)

## External Links
[qiskit.org](https://qiskit.org/)

[<img alt="GitHub Logomark" src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="32">](https://github.com/Qiskit/qiskit)

[Qiskit textbook](https://qiskit.org/textbook/preface.html)

## Code snippets