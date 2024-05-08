# MultiThreading102103252
Multithreading Assignment 102103252

# Matrix Multiplication Performance Analysis

This project aims to analyze the performance of matrix multiplication using multithreading in Python. We investigate how the execution time and CPU usage vary with different numbers of threads.

## Methodology

- **Matrix Multiplication Function**: We define a function `multiply_matrices()` to perform matrix multiplication for a subset of matrices.
- **Random Matrix Generation**: Random matrices of size 1000x1000 are generated for experimentation.
- **Multithreading**: We utilize Python's `threading` module to parallelize matrix multiplication across multiple threads.
- **Performance Metrics**:
  - *Execution Time*: The time taken to complete the matrix multiplication task.
  - *CPU Usage*: Percentage of CPU utilized during the execution.

## Experiment

We perform matrix multiplication using varying numbers of threads (1 to 8) and measure the execution time and CPU usage for each case.

#### Execution Time

![Execution Time Graph](execution_time.png)

#### CPU Usage vs. Number of Threads

![CPU Usage Graph](cpu_usage.png)

## Conclusion

- The execution time tends to decrease initially with an increase in the number of threads but may plateau or even increase beyond a certain point due to overheads.
- CPU usage generally increases with the number of threads, indicating higher parallelism but also potentially increased contention for resources.
