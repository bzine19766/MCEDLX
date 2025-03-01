# MCEDLX
Optimized Maximal Clique Enumeration (MCE) Algorithm

Overview

This repository presents an optimized algorithm for Maximal Clique Enumeration (MCE), drawing inspiration from Knuth’s Algorithm X and its efficient implementation via Dancing Links (DLX). By integrating degeneracy ordering and pivoting strategies, our approach enhances the efficiency of maximal clique discovery, particularly in sparse graphs.

Key Contributions

Algorithm X & Dancing Links (DLX): Utilizes an efficient backtracking approach for set-cover problems.

Degeneracy Ordering & Pivoting: Improves pruning efficiency in the search space.

Optimized Theoretical Bound: Establishes a recurrence relation aligning with the theoretical bound of O(3^(n/3)), the maximum number of cliques in an n-vertex graph.

Practical Efficiency: Experimental results on bitwise AND graphs demonstrate superior performance over Tomita’s algorithm, achieving an empirical complexity of approximately O(2^(0.527n)).
