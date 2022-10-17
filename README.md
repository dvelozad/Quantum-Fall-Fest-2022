# Holonomic quantum computation

## Miembros 

Diego Veloza, Felipe Bermudez, Felipe Abril

## Descripción

This project aims to implement the Holonomic quantum gates proposal by Chunfeng Wu, Yimin Wang, Xun-Li Feng, and Jing-Ling Chen in https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.13.014055. 

Ever since the first proposals of quantum protocols (communication and encryption protocols, teleportation, and others), it was clear that environmental effects would affect their correct execution. Over the years several proposals have been made to mitigate this obstacle, from sophisticated quantum control schemes to the construction of robust topological structures. This proposal is encapsulated in the latter. 

The topological characters present in the system's parameter space have found several applications. Namely, the toric code by Kitaev proved to be a strong enough concept to inspire a large amount of research.

This work explores the implementation of a 3-qubit Hamiltonian capable of implementing single-qubit and two-qubit quantum gates with inherited decoherence protection in the context of a surface code. The idea is to implement the quantum circuit that defines the latter in terms of holonomic gates.

Firstly, we implement a standard surface code. Then, using Pennylane's ApproxTimeEvolution function, we perform a discrete implementation of the so-mentioned Hamiltonian that turns out to be equivalent to the implementation of certain quantum gates depending on the set of Hamiltonian parameters chosen.
