An eigenstate is a state that satisfies the equation

```math
\hat{O}|\psi\rangle = \lambda|\psi\rangle,
```

for some operator \(\hat{O}\) (often representing an observable) and eigenvalue \(\lambda\). In many quantum mechanics problems, particularly when dealing with observables, we choose the eigenstates as the basis for the Hilbert space because they have a direct physical meaning—the measurement of the observable always yields one of its eigenvalues, and the system "collapses" into the corresponding eigenstate.

However, saying that an eigenstate is "the same as" one of the basis states requires some clarification:

1. **Eigenstates as a Natural Basis:**  
   When an observable is represented by a Hermitian operator, its eigenstates (if they form a complete set) can be chosen as an orthonormal basis for the Hilbert space. In this sense, they *are* the basis states in which we express any state of the system for the purpose of making measurements related to that observable.

2. **Basis Choice is Not Unique:**  
   The Hilbert space admits many different complete bases. While the eigenstates of a particular operator provide a natural basis for discussing measurements of that operator, they are just one of many possible choices. For example, you could also choose a momentum basis, a position basis, or any other set of complete states even if those states might not be eigenstates of the observable you're considering.

3. **Degenerate Eigenstates:**  
   In cases where an eigenvalue has a degeneracy (i.e., there are multiple independent eigenstates corresponding to the same eigenvalue), you can choose any orthonormal set of states spanning that degenerate subspace as basis states. So while each chosen vector in that basis is an eigenstate, the choice among them is not unique.

4. **Operational Significance:**  
   In practice, when you measure an observable, the eigenstates of that observable dictate which outcomes are possible—the Born rule tells you that the probability of measuring a particular eigenvalue is given by the squared magnitude of the amplitude of the state when expressed in that eigenbasis.

### ASCII Diagram Illustration

```
                        |ψ⟩ (An arbitrary state)
                               |
                               V
         Expand |ψ⟩ in the eigenbasis of observable Ō
                               |
              +--------------+--------------+
              |              |              |
         |eigenstate₁⟩   |eigenstate₂⟩   ... |eigenstate_n⟩
              |              |              |
              V              V              V
  Ō|eigenstate_i⟩ = λᵢ |eigenstate_i⟩   (Each eigenstate has a definite measurement outcome)
```

### Summary

- **Eigenstate:**  
  A state that, when acted on by an operator, yields a scalar multiple of itself. For a Hermitian operator (like an observable), these eigenstates have real eigenvalues.

- **Basis State:**  
  Any state in a set that spans the Hilbert space. When the basis is chosen as the eigenstates of an observable, they directly correspond to the possible measurement outcomes.

- **Connection in Quantum Mechanics:**  
  By expressing an arbitrary state in the eigenbasis of an observable, you can immediately read off the probabilities of different measurement outcomes as per the Born rule. While this eigenbasis is convenient and physically meaningful, it’s just one of many valid bases for the space.

Would you like to further explore how the choice of basis affects the description of quantum systems or how different observables may demand different eigenbases?
