## GPU-Accelerated Gradient Descent Based Load Flow Analysis

### Overview
The project explores an innovative approach to load flow analysis in power systems using gradient descent methods accelerated by GPU parallelization.

### Abstract
In this project, we introduce a gradient descent approach to load flow analysis, crucial for power system operations. The method's parallelizability allows for extensive utilization of GPU programming, significantly enhancing performance and scalability. We also present a novel "Pseudo-Random" Gradient Descent implementation that boosts convergence rates and propose algorithms for adaptive step sizing. This repository includes:

- Mathematical framework for gradient descent in load flow analysis.
- GPU-parallelized implementation using the CuPy library.
- Pseudo-random walk gradient descent and adaptive step gradient descent algorithms.
- Benchmarks and performance comparisons with traditional CPU-based algorithms.

### Features

- **Gradient Descent Load Flow Analysis**: Utilizes GPU parallelization for speedup.
- **Pseudo-Random Walk Gradient Descent**: Enhances convergence rates by randomizing step sizes.
- **Adaptive Step Sizing**: Dynamically adjusts step sizes based on system properties.
- **GPU Parallelization**: Accelerates computations using the CuPy library.
- **Comparative Analysis**: Includes benchmarks for different system sizes and convergence rates.

### Performance Benchmarks

The table below highlights the performance comparison between CPU and GPU-based implementations for different system sizes:

| System Size (Buses) | CPU Time (s) | GPU Time (s) |
|---------------------|--------------|--------------|
| 100                 | 30           | 5            |
| 500                 | 180          | 15           |
| 1000                | 400          | 40           |

### Future Work

Potential future improvements to this project include:

- **Sparse Data Structure**: Use sparse matrix representations to reduce computational overhead for large systems.
- **Custom GPU Programming**: Further optimization with custom GPU functions.
- **Second-Order Corrections**: Implementing more efficient second-order gradient methods for faster convergence.

### Acknowledgements

We would like to thank **Professor Ranjana Sodhi** for her invaluable guidance and support, and **Mr. Manish**, a dedicated Ph.D. scholar, for his assistance during the course of this project.
