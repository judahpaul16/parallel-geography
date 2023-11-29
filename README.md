# Parallel Algorithm Comparison for Weather Data Analysis

## Introduction
This Jupyter Notebook is dedicated to demonstrating and comparing two parallel processing algorithms for weather data analysis. It focuses on calculating the distance between various cities and a given point, leveraging parallel processing techniques to optimize performance.

## Overview
The notebook presents a practical comparison between two different parallel processing approaches:
1. **Thread-based Parallelism**: Utilizes Python's threading module to divide the task among multiple threads.
2. **Queue-based Threading Parallelism**: Employs a queue-based system combined with threading for task distribution and management.

Both methods are applied to the same task: calculating the distance from a set point to various cities worldwide, demonstrating the efficiency and execution time of each approach.

## Features
- Detailed implementation of two parallel processing algorithms.
- Comparison of execution times and efficiency between thread-based and queue-based parallelism.
- Interactive cells for executing and comparing both methods.
- Visualization of results for easier comparison and understanding.
- Inclusion of a dataset containing city coordinates for practical demonstration.

## Usage
- The notebook guides the user through the implementation and execution of both parallel processing methods.
- Users can directly run the cells to observe the performance of each algorithm.
- The notebook allows for adjustments in parameters like the number of threads to experiment with different configurations.

## Development
This notebook serves as an educational tool for understanding and comparing parallel processing techniques in Python. It is structured to facilitate easy understanding and modification of the code for further experimentation.

## Testing
- The notebook includes examples and scenarios for testing both parallel processing methods.
- Users can input different coordinates or modify the number of threads to test the robustness and scalability of each approach.