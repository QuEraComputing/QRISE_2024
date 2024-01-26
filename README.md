# QRISE - 2024

Welcome to the repository for QuEra's 2024 challenge for QRISE. 

## Challenge statement: 

Create a compilation visualizer for neutral-atom based quantum computers. This program should be able to:
*	Ingest a quantum algorithm in terms of a list of gates and qubit register
* 	Use a theoretical model for a neutral-atom quantum computer based on qubit shuttling architectures with processing, memory, and measurement zones. The model can include performance parameters for shuttling (speeds, coherence loss), 2-qubit and 1-qubit gate fidelities, gate speeds, physical sizes of zones (which you may choose to allow a user to change/define)
*	Output a visualization of the atom moves and gate applications (in terms of beam pulses) that compile the algorithm of choice. It should output the time expected to be necessary to run the algorithm, and expected performance given accumulation of noise
*	Bonus points if your program can perform a couple of logical qubit encoding protocols, automatically transforming the original logical qubit into a full compiled program including routines for error correction

## Context: 
Neutral atoms have recently set themselves apart from all other technologies from quantum computing by demonstrating experimentally the capacity to operate protocols on up to 48 logical qubits. While the full pipeline for error correction with feedforward has not yet been demonstrated, these demonstrations have advanced the era of error-corrected quantum computation by several years with respect to previous expectations.

The features that allow this advance include the high capacity for parallelization of operations (including transversal gates), large scale registers of qubits (with hundreds of them today, and plans to scaling those to 10,000s without need for interconnects), and high-performing 2-qubit gates (99.5% fidelity demonstrated so far). All of this is catalyzed by the capacity to shuttle qubits through the quantum devices, actually enabling these machines to have dedicated and specialized zones for memory, processing, and measurement, with a quantum information bus that allows roughly any-to-any connectivity. Altogether, these features makes neutral-atom architectures with shuttling closer to full computers, than just processors.

The flexibility of moving atoms and performing multi-qubit gates at high performance mean that the compilation space for neutral-atom hardware is extremely rich. And the recent experimental demonstrations of late 2023 mean that 2024 and probably 2025 will be the years of compilation. Of demonstrations of efficient compilation of quantum algorithms that leverage these advantages unique to neutral-atom hardware, as well as of demonstrations of efficient compilation of logical quantum algorithm protocols enhanced by error-correction deployed at the physical qubit level.

At QuEra Computing, we have recently unveiled our ambitious roadmap for productizing error-corrected quantum processors. As part of our product line, we intend to build a platform for emulating or simulating protocols for logical qubit operations. The goal is that this tool will be closely tied to our hardware, informed by its realistic conditions, and will enable users to start estimating what it will take to run error-corrected protocols on early fault-tolerant quantum computers. This challenge is our call for you to participate on this challenge with us and showcase what your vision is for what this product could look like.

## Main references:

* https://arxiv.org/abs/2112.03923
* https://arxiv.org/abs/2312.03982

Supporting references:
* https://arxiv.org/abs/2306.03487
* https://arxiv.org/abs/2311.15123
* https://arxiv.org/abs/2311.16082
* https://arxiv.org/abs/2311.16214
* https://arxiv.org/abs/2311.16035


## Submission process

* write up
* video? 

Fork repo?