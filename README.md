# Quantum expander testing

This repository gathers progress on quantum expander testing:
> Is a unital quantum channel $\Phi[\cdot] = \frac{1}{d} \sum_{i=1}^d U_i \cdot U_i^\dagger$ a quantum expander, or is it "far" from being a quantum expander?

## Setup
[[Prelim - Quantum channels and expanders]]
[[Prelim - Testing quantum channels]]
[[Problem  - Testing quantum expanders]]

## Upper bounds
We prove a *structural result*:
> A quantum channel is far from any quantum expander in the ACID-norm iff the quantum channel has a large cut. [[ACID cut]]

*Upper bounds* depend on the access model (channel access versus unitary access):
[[Upper bounds - channel access]]
[[Upper bounds - unitary access]]

## Lower bounds
We can prove a $\Omega(N^{1/4})$ (or even $\Omega(N^{1/3})$) lower bound by lifting the quantum lower bound for graph expansion testing.
[[Lower bound - from graph expansion testing]]

## Archive
older stuff:
## Contributors
The following people have contributed:
 - Simon Apers
 - Bahar Bagheri
 - Partha Mukhopadhyay
