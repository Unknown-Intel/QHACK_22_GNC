# factqr

One of the most well known quantum algorithm is Shor's Algorithm which utilizes period-finding to find a single factor of a integer, here is our take on factoring integers using a quantum computer via VQE. We created a method to generate a Hamiltonian of a number such that the eigenvalue that is 0  will have an associate eigenvector that would describe the composite nature of that number. 

Our heuristic is able to take any set of base values up to the number of qubits available and compute the exponents with regards to the given bases, which shows flexibility in our architecture.

### Possible Implmentations:
1. Data Compression (https://github.com/Unknown-Intel/QZip)
