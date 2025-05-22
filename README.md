# Graph Coloring to SAT Converter

This Python script transforms a graph coloring problem into a Boolean satisfiability (SAT) problem in [DIMACS CNF format](https://satcompetition.org/2009/format-benchmarks2009.html). It enables solving graph coloring problems using any standard SAT solver.

---

## Problem Statement

Given:
- A graph with `n` nodes and `m` edges
- `k` available colors

Assign each node exactly one of the `k` colors such that:
- **No two adjacent nodes share the same color**
- **Each node receives exactly one color**

This script converts the above constraints into a set of CNF clauses suitable for SAT solvers.

---

## Usage

```bash
python3 sat-solver.py
