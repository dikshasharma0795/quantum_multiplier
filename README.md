# quantum_multiplier
Computes the quantum Fourier transform of reg, one qubit at a time. Apply one Hadamard gate to the nth qubit of the quantum register reg, and then apply repeated phase rotations with parameters being pi divided by increasing powers of two. Further, Evolves the state |F(ψ(reg_a))> to |F(ψ(reg_a+reg_b))> using the quantum Fourier transform.

Performed on QASM Simlator.
