# Semiclassical Weyl quantization and exact free propagation

## Abstract (Alpha)

Semiclassical momentum treats the reduced Planck constant as a parameter. Its action on Schwartz
maps and its Fourier representation provide a starting point for Weyl quantization and the
transport of quantum observables along the classical free flow.

## Content (Alpha)

### Semiclassical momentum

The scaled momentum acts as $-ih\partial_i$ on Schwartz maps. It agrees with the physical
momentum at $h=\hbar$, is symmetric on the Schwartz domain, and becomes multiplication by
$2\pi h\xi_i$ under the Fourier transform. For $h\ne0$, the Fourier transform of position is a
scalar multiple of momentum applied to the transformed wavefunction. [1]

### Free propagation and Weyl quantization

The free flow sends $(q,p)$ to $(q+tp/m,p)$. The free Hamiltonian acts as a kinetic-energy
multiplier in Fourier coordinates. The free propagator multiplies by a quadratic phase in
these coordinates, preserves the Schwartz submodule, and extends to a strongly continuous
unitary group on the Hilbert space. [TODO]

Weyl ordering symmetrizes the products of position and momentum for quadratic symbols. [TODO]
For a Schwartz phase-space symbol, Fourier synthesis integrates its Fourier coefficients
against Weyl displacements. {2} The resulting operator is bounded on the Hilbert space with
a norm bound uniform in $h$, and real symbols give symmetric operators. [TODO]

### Egorov correspondence

Egorov correspondence relates quantum conjugation to transport along a classical flow. {1}
Free propagation gives exact transport of quadratic symbols on the common Schwartz domain.
For Schwartz symbols, it gives exact transport and equality of expectation values on the
full Hilbert space. [TODO]

The coordinate kernel formula and Wigner pairing express the same observables in position
and phase space, respectively. {3} [TODO] For nonquadratic potentials, a remainder estimate
compares quantum propagation with classical transport. {3} [TODO]

## Lean References

1. Physlib/QuantumMechanics/Semiclassical/Basic.lean — `momentumCLM`, `momentumCLM_hbar`,
   `momentumCLM_apply`, `momentumCLM_inner`, `fourier_momentumCLM`, `momentumCLM_fourier`,
   `fourier_positionCLM`

## References

1. S. Dyatlov, *Notes on fractal uncertainty principle* (2017), Proposition 1.1.3.
   https://math.mit.edu/~dyatlov/files/2017/fupnotes.pdf
2. V. Guillemin and S. Sternberg, *Semi-classical analysis* (2010), Section 15.11.2.
   https://math.mit.edu/~vwg/semiclassGuilleminSternberg.pdf
3. J. Keller and C. Lasser, *Propagation of Quantum Expectations with Husimi Functions*
   (2013), arXiv:1207.7211v2. https://arxiv.org/abs/1207.7211
