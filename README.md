# Collatz T-map Census: √3/2 Contraction

**The T-map contracts at √3/2: a Collatz census below 10^6, a length-16 parity-vector bijection, and a coral inverse tree**

Author: Benjamin Stanley Frohman (ORCID: 0009-0006-7068-3718)  
Affiliation: Lewisville, Texas  
Date: 18 September 2026  

## Abstract

The accelerated Collatz map

T(n) = n/2 if n even,  
(3n + 1)/2 if n odd

has a unique coin-flip geometric mean: one even step contributes a factor 1/2, one odd step a factor 3/2, and

√(1/2 · 3/2) = √3 / 2.

A complete census of every positive integer below 10^6 measures that mean as 0.865312 against √3/2 = 0.866025. Relative error 8 · 10^{-4}. On the same window every orbit reaches 1, the delay record is (837799, 524), and the first sixteen parity vectors are in bijection with residue classes modulo 2^k. The inverse graph on a 433-node window is a tree. These are resolved statements. They are not the Collatz conjecture.

This is a resolution note for a finite window, not a proof that every orbit of T reaches the cycle {1, 2}. The Collatz conjecture remains open.

What is resolved by direct computation and finite conjugacy check:
1. every n < 10^6 reaches 1;
2. the delay-record list ending at 837799 with 524 accelerated steps;
3. the geometric mean of T(n)/n on that window equals √3/2 to three digits;
4. the parity-vector map is bijective for every length k = 1, …, 16;
5. a 433-node inverse fragment is a tree (432 edges).

## Zenodo Deposit Instructions

This is a new record and a new DOI. Title the record by the √3/2 contraction, not by the Collatz conjecture solved.

Upload the PDF and the .tex. Does not prove the Collatz conjecture.

Related identifiers:
- 10.5281/zenodo.23629486
- 10.5281/zenodo.23629484
- 10.5281/zenodo.23629488

License: Apache License 2.0

## Status

Computational finite-window resolution. Does not prove Collatz.
