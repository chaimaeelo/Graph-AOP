# Dual-Critical Graph Tester

This project provides Python code to experiment with dual-critical graphs, spanning trees, and arithmetic in finite fields GF(2^k).  
It includes tools for constructing spanning trees, computing determinants in GF(2^k), building fundamental cycles, and performing randomized tests of dual-criticality (following Szegedy–Szegedy’s approach).

---

## Features

- **Spanning Trees**

  - Extract a spanning tree of a connected graph using BFS.
  - Extract unique spanning trees up to isomorphism.

- **Arithmetic in GF(2^k)**

  - Addition, multiplication, modular reduction, inversion, and irreducibility checks.
  - Determinant computation of matrices over GF(2^k).

- **Dual-Criticality Test**

  - Randomized algorithm to check whether a graph is dual-critical.
  - Prints debug information (spanning tree edges, fundamental cycles, constructed matrix, determinant).

- **Visualization**
  - Visualize the input graph and its spanning tree using `matplotlib`.

---

## Requirements

- Python 3.8+
- [networkx]
- [matplotlib]

Install with:

```bash
pip install networkx matplotlib
```
