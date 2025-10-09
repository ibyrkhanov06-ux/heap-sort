# 🧮 Heap Sort — Assignment 2: Algorithmic Analysis and Peer Code Review

### 👤 Student
**Name:** [Zhanibek Ibyrkhanov]  
**Pair:** Pair 2 — Advanced Sorting Algorithms  
**Algorithm:** Heap Sort (In-place implementation with bottom-up heapify)

---

## 📘 Project Overview

This project implements **Heap Sort** as part of Assignment 2 for the “Algorithmic Analysis and Peer Review” coursework.  
The implementation focuses on **performance measurement**, **algorithmic complexity**, and **peer analysis**.

---

## ⚙️ Project Structure

heap-sort/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ └── com/assignment2/
│ │ │ ├── algorithms/HeapSort.java
│ │ │ ├── metrics/PerformanceTracker.java
│ │ │ └── cli/BenchmarkRunner.java
│ └── test/
│ └── java/
│ └── com/assignment2/algorithms/HeapSortTest.java
├── docs/
│ ├── analysis-report.pdf
│ └── performance-plots/
├── pom.xml
└── README.md
## 🚀 Running the Project

### 🧩 Build & Test
To build and test the project:
```bash
mvn clean test
Run Benchmarks
mvn clean compile
java -cp target/classes com.assignment2.cli.BenchmarkRunner
Performance Benchmark

The BenchmarkRunner runs Heap Sort for different input sizes (100, 1,000, 10,000, 100,000)
and records time and operation counts into a CSV file.
Complexity Analysis
Heap Sort is an in-place comparison-based sorting algorithm that builds a heap and repeatedly extracts the maximum element.


```
<img width="1580" height="980" alt="output" src="https://github.com/user-attachments/assets/5fadd527-858d-463d-a249-8269f6471cc7" />

Report from Zhahangir:
I’ve reviewed the Heap Sort assignment — great job overall.
The implementation is clean and functional, and the project is well-structured with Maven and proper JUnit 5 testing setup.

What’s Done Well

The HeapSort class correctly implements the core algorithm.

Unit tests in HeapSortTest cover the main cases (empty array, single element, sorted input).

PerformanceTracker and BenchmarkRunner are a nice touch — they make it easy to measure and compare performance.

The Maven project structure follows best practices.

What Could Be Improved

Add comparator support so the algorithm can handle custom sorting orders.

Include a visualization or output logs to show the heap building and sorting process.

Expand tests to include large datasets and performance validation.

Maybe compare Heap Sort with QuickSort or MergeSort to see performance differences.

Overall, it’s a solid implementation that demonstrates a good understanding of both Java and algorithmic design. 💪
