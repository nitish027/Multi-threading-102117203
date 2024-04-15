# Multi-threading-102117203

# Multi-Threading-102117203

The "Matrix Multiplication Performance Benchmark" project assesses how multi-threading influences the speed of matrix multiplication tasks. It utilizes Python libraries such as NumPy, threading, and Pandas to create random matrices and gauge the time taken for matrix multiplication with different thread counts ranging from 1 to 8. The outcomes are scrutinized and graphically represented to grasp the impact of concurrency on performance. This initiative provides valuable insights into enhancing efficiency for computational tasks involving matrix operations.

Function explanation:
1. **generate_random_matrices(n, size)**:
   - Generates `n` random matrices of size `size x size`.

2. **multiply_matrices(matrices)**:
   - Multiplies a list of matrices together, starting with a constant matrix.

3. **perform_multiplication_with_threads(num_threads)**:
   - Performs matrix multiplication using multiple threads, dividing the task among them for parallel computation.

The table corresponding to the time taken with respect to number of threads is as follows:
![image](https://github.com/nitish027/Multi-threading-102117203/assets/142744015/191ae050-0cd3-4317-ba48-31ba267c862c)




Graph:

![image](https://github.com/nitish027/Multi-threading-102117203/assets/142744015/6aed3560-a814-491a-8171-02aa6ac42465)


