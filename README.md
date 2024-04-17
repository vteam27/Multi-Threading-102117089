# Multi-Threading-102117089

The "Matrix Multiplication Performance Benchmark" project evaluates the impact of multi-threading on matrix multiplication tasks. Using Python libraries like NumPy, threading, and Pandas, the project generates random matrices and measures the execution time of matrix multiplication with varying numbers of threads (1 to 8). The results are analyzed and visualized to understand how concurrency affects performance. This project offers insights into optimizing computational tasks involving matrix operations.

Function explanation:
1. **generate_random_matrices(n, size)**:
   - Generates `n` random matrices of size `size x size`.

2. **multiply_matrices(matrices)**:
   - Multiplies a list of matrices together, starting with a constant matrix.

3. **perform_multiplication_with_threads(num_threads)**:
   - Performs matrix multiplication using multiple threads, dividing the task among them for parallel computation.

The table corresponding to the time taken with respect to number of threads is as follows:
<img width="813" alt="Screenshot 2024-04-12 at 3 44 33 PM" src="https://github.com/ThatSpaceCowboy/Multi-Threading-102117114/assets/41112158/51c89bbb-28f5-4e67-a88c-db5f63df7b96">

Graph:

![download](https://github.com/ThatSpaceCowboy/Multi-Threading-102117114/assets/41112158/83a9d656-9f81-4e37-bf75-c14998ca6874)
