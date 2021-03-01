# Qiskit

[qiskit.org](https://qiskit.org/)

[<img alt="GitHub Logomark" src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="32">](https://github.com/Qiskit/qiskit)

Fully featured IBM behemoth, tools for q-bending.


### From the qiskit page
> Qiskit [quiss-kit] is an open source SDK for working with quantum computers at the level of pulses, circuits and application modules.


## Summary
- access to circuits
- hardware access
- noise mitigation
- quantum algorithms

Qiskit is the big-boy in the quantum computing space. The framework covers a broad range of quantum topics. Qiskit gives users access to the fundamentals through circuit building. It lets users explore the well known algorithms in the quantum space, think Shor, Grover, VQE, QAOA -- all the famous ones. In addition IBM has experts in a range of applications from finance, machine learning and chemistry building industry specific quantum applications. Finally qiskit has simulators that can get users ready to deploy their code on to actual quantum computers, and since it's IBM, they have actual quantum computers. If you were stuck on a desert island with a dilution fridge and could only bring one framework, you would not regret bringing qiskit.


### Qiskit elements
![](imgs/avatar.png)
### Terra
> Terra provides the foundations for Qiskit. It allows the user to write quantum circuits easily, and takes care of the constraints of real hardware. 

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

### Aqua
> Quantum Algorithms & Applications in Python

### Ignis
> Ignis provides tools for quantum hardware verification, noise characterization, and error correction. 

## Strangeworks Links


## External Links

[Qiskit textbook](https://qiskit.org/textbook/preface.html)

## Code snippets