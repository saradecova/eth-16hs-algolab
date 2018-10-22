# Algolab HS2016
In this repository you find my solutions to the problems posed as part of the "AlgoLab" course at ETH Zurich.
(See http://www.cadmo.ethz.ch/education/lectures/HS16/algolab/index.html)

You can do whatever you want with my solutions except for claiming they are yours.
The code is written by me, I did not come up with algorithmic ideas..

The test files (including reference outputs) are provided as part of the course. For some problems I added some extra test cases.

# Typical approaches/techniques:
* Binary-search

# Tricks/Pitfalls

* Rounding errors in Min_circle
  * Use: Exact_predicates_exact_constructions_kernel.h
  * Use: Exact_predicates_exact_constructions_kernel.h
  * convert to double: ceil(to_double(et))
* Bias for non-negative weights max-flow-min-cost
* LP: Different kernels for different precisions (see http://doc.cgal.org/latest/Number_types/group__nt__gmp.html)
  * Gmpz.h: Arbitrary precision integer
  * Gmpzf.h: Multiple-precision floating-point number (m*2^e), generally faster than MP_Float.h
  * Gmpq.h: Arbitrary precision rational
  * MP_Float.h: Arbitrary precision float


(... spoilers below)

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

..

(... spoilers now)

## Solved Problems (careful spoilers)

1. week (5/6)
  * Build the sum 100/100
  * *Dominoes* 0
  * Even Matrices 100/100
  * Even Pairs 100/100
  * False coin 100/100
  * PotW: *Deck of cards* 100/100
2. week (2/5)
  * Evolution: 100/100 -- "Skip-tree"
  * PotW: Octopussy 100/100 -- EDF* (*= with dependencies)
3. week (1/5)
  * PotW: *Attack of the clones* 100/100 -- EDF scheduling; index-tricks
4. week (1/5)
  * PotW: *TheeV* 100/100 -- Binary search, Min-Circle
5. week (3/6)
  * Lights at the Museum 100/100 -- Bruteforce/Split-and-List
  * PotW(A): On her Majesty's secret service 100/100 -- Dijkstra; exp-bin-search w/ max. cardinality matching
  * PotW(B): Poker Chips 100/100 -- Huge DP
6. week (1/4)
  * PotW: A New Hope 100/100 -- Big DP in heap (bottom-up)
7. week (1/5)
  * PotW: Knights 100/100 -- Max flow
8. week (1/5)
  * PotW: Stamps 100/100 -- LP
9. week (1/5)
  * PotW: Casino Royale 80/80 -- Mincost Max-flow; tricky bias
10. week (1/4)
  * PotW: Sith 100/100 -- Binary search; Delaunay (->sparse graph), max-connected-component
11. week (1/4)
  * Carsharing 100/100 -- Like Casino Royale (mincost-maxflow)
  * PotW: Planks 60/100 -- (You can do Split-and-List)
12. week (4/6)
  * Placing Knights 100/100 -- Max bipartite matching
  * Radiation 100/100 -- LP with tricks
  * New tiles 100/100 -- DP over lines (employing inner line monotonicity)
  * PotW: The Empire Strikes Back 100/100 -- LP, Delaunay
13. week (2.5/4)
  * DHL 60/100 -- DP, Greedy (TODO)
  * Sweepers 100/100 -- Euler-tours; maxflow (bordercases with connected-components)
  * PotW: The Phantom Menace 100/100 -- maxflow
14. week: Christmas Challenge (Cantonal Courier) 100/100 -- maxflow (still not 100% sure why it works)




