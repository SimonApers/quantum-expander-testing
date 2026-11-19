# Quantum expander testing

This repository gathers progress on quantum expander testing:
> Is a unital quantum channel $\Phi[\cdot] = \frac{1}{d} \sum_{i=1}^d U_i \cdot U_i^\dagger$ a quantum expander, or is it "far" from being a quantum expander?

## Setup
- [Prelim - Quantum channels and expanders](Prelim%20-%20Quantum%20channels%20and%20expanders.md)
- [Prelim - Testing quantum channels](Prelim%20-%20Testing%20quantum%20channels.md)
- [Problem  - Testing quantum expanders](Problem%20%20-%20Testing%20quantum%20expanders.md)

## Upper bounds
We prove a *structural result*:
> A quantum channel is far from any quantum expander in the ACID-norm iff the quantum channel has a large cut. [ACID cut](ACID%20cut.md)

*Upper bounds* depend on the access model:
- channel access: [Upper bounds - channel access](Upper%20bounds%20-%20channel%20access.md)
- unitary access:[Upper bounds - unitary access](Upper%20bounds%20-%20unitary%20access.md)

## Lower bounds
We can prove a $\Omega(N^{1/4})$ (or even $\Omega(N^{1/3})$ ) lower bound by lifting the quantum lower bound for graph expansion testing.
- [Lower bound - from graph expansion testing](Lower%20bound%20-%20from%20graph%20expansion%20testing.md)

## Archive
older stuff:
## Contributors
The following people have contributed:
 - Simon Apers
 - Bahar Bagheri
 - Partha Mukhopadhyay
