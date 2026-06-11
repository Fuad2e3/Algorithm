# Java Algorithm Implementations

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)
![Algorithms](https://img.shields.io/badge/Algorithms-Implemented-green?style=for-the-badge)

A professional collection of robust Java implementations for essential data structures and algorithms. Each module is engineered with a focus on modularity, performance analysis, and clean code principles.

## 🚀 Key Features

- **Modular Design**: Each algorithm is self-contained and easy to integrate.
- **Complexity Analysis**: Documentation includes insights into time and space complexity.
- **Educational Value**: Clear commenting and standard naming conventions for better learning.
- **Production-Ready Logic**: Adheres to standard Java SE best practices.

---

## 📂 Core Implementations

### 1. Crab Graph
**File**: [CrabGraph.java](file:///C:/Users/fuadk/Documents/GitHub/Algorithm/CrabGraph.java)
- **Description**: A specialized graph implementation utilizing the "Crab" structural model. It manages "Body" vertices with strict "Leg" edge constraints.
- **Use Case**: Network topology modeling where node capacity is limited based on roles.
- **Complexity**: $O(V + E)$ for graph construction.

### 2. Insertion Sort with Shift Analysis
**File**: [Sort.java](file:///C:/Users/fuadk/Documents/GitHub/Algorithm/Sort.java)
- **Description**: An optimized Insertion Sort that performs real-time shift counting.
- **Technical Insight**: The shift count is equivalent to the number of inversions in the array, providing a measure of the array's initial disorder.
- **Complexity**: $O(n^2)$ Time | $O(1)$ Space.

### 3. Ice Cream Parlor Search (Target Sum)
**File**: [Search.java](file:///C:/Users/fuadk/Documents/GitHub/Algorithm/Search.java)
- **Description**: An efficient search algorithm to find pairs of elements that meet a precise target sum.
- **Methodology**: Uses a 1-based indexing return format common in competitive programming.
- **Complexity**: $O(n^2)$ (Brute Force implementation provided).

---

## 🛠️ Technical Setup

### Requirements
- **JDK**: version 8 or higher
- **Tools**: Any standard Java Compiler (javac) or IDE (IntelliJ, Eclipse, VS Code)

### Compilation & Execution Guide

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/algorithm.git

# 2. Navigate to directory
cd algorithm

# 3. Compile a specific module
javac CrabGraph.java

# 4. Run the application
java CrabGraph
```

---

## 📈 Roadmap
- [ ] Add Hash-based $O(n)$ implementation for Search.java
- [ ] Implement Merge Sort for comparison with Insertion Sort
- [ ] Add Unit Tests (JUnit 5) for all modules

---


## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="center">
  Developed with ❤️ by <b>Team Softece</b><br>
  <i>Algorithm | Green University of Bangladesh</i>
</p>

