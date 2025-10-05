# 🧮 Heap Sort — Assignment 2: Algorithmic Analysis and Peer Code Review

### 👤 Student
**Name:** [Твоё имя]  
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
