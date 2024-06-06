# Exercise 1

Consider the circuit following quantum circuit:


![imagen](https://github.com/paugarcia32/Quantum-Circuits-with-Qiskit/assets/37461446/431c9d8c-f211-466c-8e4e-303313b82b91)


In which T represents the so-called T-gate. 

1. Analytically prove that this circuit is an equivalent realization of a CCNOT or Toffoli gate.
2. Implement the circuit in Qiskit and compare the results with the ones obtained in a). Show the image of the circuit obtained with Qiskit.
3. Find some processors that are operative and compute the previous quantum circuit in a ’real quantum computer’. Are the results different than theoretically expected? Prove on different processors, are the same results obtained on any of them?. Discuss the results.

# Exercise 2

In quantum computing, a phase estimation algorithm is a quantum algorithm to estimate the phase θ corresponding to an eigenvalue of a given unitary operator. Assume we have an unitary quantum circuit Q and a quantum state |ψ⟩ which we know is an eigenstate of Q, thus:

$$Q|ψ⟩ = e{iθ} |ψ⟩$$

Then, the phase estimation problem is to work out the value of θ

1. Write down a full circuit for the quantum phase estimation algorithm. 0.5 p
2. By tracking the input state through the circuit, write down the final state at the end of the algorithm. What is the probability that the outcome 1 is returned when the first register is measured? 0.5 p

Consider now the single qubit T -gate which performs a $π/4$ phase rotation:

3. Write a script in Qiskit that prints the circuit for simple phase estimation circuit for the T -gate. Present the output results and the printed circuit. 1 p
4. Qiskit provides three different phase estimation algorithms. Write a script which applies each of those three algorithms and plot the corresponding circuit and results in each case for the T -gate. Discuss the results. 1 p


# Exercise 3

Alice (A) and Bob (B) and their child, Charlie (C) have two tickets for Copenhagen’s play. The problem here is that we have three people and just two tickets for the play. We will try to help them to find the best combination for them to go to the play by means of Grover’s algorithm. To do so, we have to write down the conditions.
It is clear that each person (A, B and C) can either not go or go to the play. Additionally, it is also clear that at least one of the adults (A or B) have to go to the play. Since C does not coincide so much with B during the week because B works in a receiver station quite far away, C wants to go with B to see the play. With these constraints:

1. Write down the constraints in a “Boolean way”, that is as conditions with Boolean operators and binary conditions (0 or 1). 0.5 p
2. Write down the solution from the constraints and write it as a string of three bits. 0.5 p
3. Using the constraints and solution you obtained in a) and b), write now a Qiskit script which implements a Grover’s algorithm with the constraints derived in a). Check that the solution is the one expected from your reasoning in b). Provide an image of the generated circuit. 
(Hint: use a proper Qiskit function or class to create an oracle from the simple Boolean expressions previously derived.) 2 p
4. Using the Qiskit oracle.draw, provide the oracle generated for this exercise. 1 p



