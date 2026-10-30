# Competitive Programming Solutions

[![Problems Solved](https://img.shields.io/badge/Problems%20Solved-844-brightgreen.svg)](#platform-overview)
[![Platforms](https://img.shields.io/badge/Platforms-14-blue.svg)](#platform-overview)
[![Languages](https://img.shields.io/badge/Languages-C%2B%2B%20%7C%20Python%20%7C%20PHP-orange.svg)](#languages-breakdown)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A curated collection of **844 solved competitive programming and algorithmic problems** from 14 online judges and programming contest platforms.

---

## Table of Contents

- [Overview](#overview)
- [Platform Breakdown](#platform-breakdown)
- [Languages Breakdown](#languages-breakdown)
- [Repository Structure](#repository-structure)
- [Naming Conventions](#naming-conventions)
- [How to Compile and Run](#how-to-compile-and-run)
- [Algorithmic Topics Covered](#algorithmic-topics-covered)
- [License](#license)

---

## Overview

This repository archives solutions to algorithmic problems tackled over multiple years of competitive programming practice, contest participation, and interview preparation. The code solutions are kept in their original implementation form to preserve the context and thought process of when they were submitted and accepted.

---

## Platform Breakdown

| Platform | Directory | Solved | Primary Languages | Platform Link |
| :--- | :--- | :---: | :--- | :--- |
| **Codeforces** | [`codeforces/`](codeforces/) | 550 | C++ (544), Python (6) | [codeforces.com](https://codeforces.com/) |
| **Quera** | [`quera/`](quera/) | 153 | C++ (139), Python (9), PHP (4), HTML (1) | [quera.org](https://quera.org/) |
| **SGU (Saratov)** | [`sgu/`](sgu/) | 40 | C++ (40) | [acmsguru](https://codeforces.com/problemsets/acmsguru) |
| **Project Euler** | [`project-euler/`](project-euler/) | 36 | C++ (36) | [projecteuler.net](https://projecteuler.net/) |
| **Vjudge** | [`vjudge/`](vjudge/) | 35 | C++ (35) | [vjudge.net](https://vjudge.net/) |
| **SPOJ** | [`spoj/`](spoj/) | 13 | C++ (13) | [spoj.com](https://www.spoj.com/) |
| **SZKOpuł** | [`szkopul/`](szkopul/) | 5 | C++ (5) | [szkopul.edu.pl](https://szkopul.edu.pl/) |
| **CodeChef** | [`codechef/`](codechef/) | 4 | C++ (4) | [codechef.com](https://www.codechef.com/) |
| **AtCoder** | [`atcoder/`](atcoder/) | 2 | C++ (2) | [atcoder.jp](https://atcoder.jp/) |
| **AIZU Online Judge** | [`aizu/`](aizu/) | 2 | C++ (2) | [onlinejudge.u-aizu.ac.jp](https://onlinejudge.u-aizu.ac.jp/) |
| **USACO** | [`usaco/`](usaco/) | 1 | C++ (1) | [usaco.org](https://usaco.org/) |
| **Timus Online Judge** | [`timus/`](timus/) | 1 | C++ (1) | [acm.timus.ru](https://acm.timus.ru/) |
| **UVa Online Judge** | [`uva/`](uva/) | 1 | C++ (1) | [onlinejudge.org](https://onlinejudge.org/) |
| **LightOJ** | [`lightoj/`](lightoj/) | 1 | C++ (1) | [lightoj.com](https://lightoj.com/) |
| **Total** | | **844** | | |

---

## Languages Breakdown

| Language | Extension | Solutions | Percentage |
| :--- | :--- | :---: | :---: |
| **C++** | `.cpp` | 824 | 97.6% |
| **Python** | `.py` | 15 | 1.8% |
| **PHP** | `.php` | 4 | 0.5% |
| **HTML / Web** | `.zip` | 1 | 0.1% |

---

## Repository Structure

```text
competitive-programming/
├── aizu/           # AIZU Online Judge solutions
├── atcoder/        # AtCoder Grand Contest (AGC) solutions
├── codechef/       # CodeChef contest solutions
├── codeforces/     # Codeforces round solutions (Div 1, Div 2, Educational)
├── lightoj/        # LightOJ problem solutions
├── project-euler/  # Project Euler mathematical challenges
├── quera/          # Quera contest and college problems
├── sgu/            # Saratov State University (acmsguru) problems
├── spoj/           # Sphere Online Judge (SPOJ) solutions
├── szkopul/        # Polish Olympiad in Informatics (SZKOpuł)
├── timus/          # Timus Online Judge solutions
├── usaco/          # USA Computing Olympiad solutions
├── uva/            # UVa Online Judge problems
├── vjudge/         # Virtual Judge classic graph & algorithm problems
├── .gitignore      # Comprehensive rules for build artifacts and OS files
├── LICENSE         # MIT Open-Source License
└── README.md       # Repository documentation and statistics
```

---

## Naming Conventions

Solutions follow standard naming formats corresponding to the platform's problem identification:

- **Codeforces**: Formatted as `<contest_id><problem_letter>.cpp` (e.g., `158a.cpp` represents Contest 158, Problem A) or titled by problem name for special contest tasks.
- **Quera**: Formatted as `<problem_id>.<ext>` matching the Quera question URL (e.g., `3406.cpp` -> `https://quera.org/problemset/3406/`).
- **Project Euler**: Formatted as `<problem_number>.cpp` (e.g., `40.cpp` -> Problem 40).
- **SGU / acmsguru**: Formatted as `<problem_id>.cpp` (e.g., `102.cpp`).
- **AtCoder**: Formatted as `<contest_code>_<problem_letter>.cpp` (e.g., `agc002_f.cpp`).
- **Vjudge / SPOJ**: Named by the problem title or problem code (e.g., `GSS1.cpp`, `Dijkstra.cpp`).

---

## How to Compile and Run

### C++ Solutions

All C++ solutions can be compiled with any standard C++11/C++14/C++17 compliant compiler:

```bash
# Compile with optimizations
g++ -O2 -std=c++17 path/to/solution.cpp -o solution

# Execute
./solution < input.txt
```

### Python Solutions

```bash
python3 path/to/solution.py < input.txt
```

### PHP Solutions

```bash
php path/to/solution.php < input.txt
```

---

## Algorithmic Topics Covered

The solutions span a wide variety of algorithms and data structures:

- **Graph Algorithms**: BFS, DFS, Dijkstra, Floyd-Warshall, Bellman-Ford, Kruskal's & Prim's MST, Articulation Points & Bridges, Strongly Connected Components (Tarjan / Kosaraju), Topological Sort, Maximum Flow & Bipartite Matching.
- **Data Structures**: Fenwick Trees (Binary Indexed Trees), Segment Trees (with Lazy Propagation), Disjoint Set Union (DSU), Treaps, Sqrt Decomposition, Monotonic Queues / Stacks.
- **Dynamic Programming**: Bitmask DP, Tree DP, Knapsack variants, Longest Common Subsequence (LCS), Interval DP, Digit DP.
- **Mathematics & Number Theory**: Sieve of Eratosthenes, Modular Arithmetic, Extended Euclidean Algorithm, Combinatorics, Matrix Exponentiation, Fast Fourier Transform (FFT).
- **String Algorithms**: KMP, Aho-Corasick, Trie, Z-algorithm, Hashing.
- **Greedy & Search**: Binary Search, Ternary Search, Two Pointers, Meet-in-the-Middle.

---

## License

This repository is distributed under the [MIT License](LICENSE). You are free to study, reference, and build upon these solutions.
