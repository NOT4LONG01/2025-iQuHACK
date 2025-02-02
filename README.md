# Hackers @ MIT iQuHACK 2025 

2025-Quantum-Factorization-With-Quantum-Rings Challenge: Crack the Code with Quantum Factorization

# QIYA

Hyeongmin Lim(Yonsei University) / lemin@yonsei.ac.kr

Joonsuk Jung(Yonsei University) / dignp5@yonsei.ac.kr

Changjae Im(Yonsei University) / imcj99@yonsei.ac.kr

Seokwon Choi(Yosei University) / seokwon0106@yonsei.ac.kr

# What we've done

We extended Shor’s algorithm to factorize an N bit integer by modifying and generalizing the quantum circuit implementation.

Inspired by the 15 to 5 x 3 factorization example from the Qiskit Textbook (https://github.com/marwahaha/qiskit-textbook/blob/22169dadee48c9abb886656bc3d6bcafcd00e7b2/content/ch-algorithms/shor.ipynb#L11), we adapted the algorithm to accommodate a larger input size.

A key focus was to adopt it to optimal number, considering between speed and accuracy.

From previous research (https://arxiv.org/pdf/quant-ph/0205095) has shown that  we could reduce the number of qubits. And we found out that when factoring an n -qubit integer, the number of ancilla qubits required for QPE scales proportional to log n. Based on this insight, we allocated a suitable number of qubits to ensure computational efficiency.

The overall circuit structure follows the conventional Shor’s algorithm design, with several technical modifications. Also, we adjusted the number of shots to improve the speed of the simulation. 

To sum up, this extended Shor’s algorithm developed in this study allows for more generalized N-bit integer factorization.