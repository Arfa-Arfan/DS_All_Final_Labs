# DS_All_Final_Labs
This notebook contains Python implementations of key data structures and algorithms, including hash tables with linear probing, sorting algorithms (selection, insertion, merge, and heap sort), binary search trees with full operations, and graph traversals (DFS and BFS). 
# Data Structures & Algorithms in Python

A comprehensive collection of fundamental data structures and algorithms implemented in Python with clear explanations and examples.

## 📋 Table of Contents
- [Hashing with Linear Probing](#hashing-with-linear-probing)
- [Sorting Algorithms](#sorting-algorithms)
- [Binary Search Tree](#binary-search-tree)
- [Graph Traversals](#graph-traversals)

## 🚀 Features
- Clean, well-commented Python implementations
- Practical examples with sample outputs
- Educational focus on algorithm understanding
- Modular structure for easy integration

## 📁 Project Structure

### 1. Hashing with Linear Probing
Implementation of a hash table using linear probing for collision resolution. Includes:
- Fixed-size hash table
- Modulo-based hash function
- Insert, search, and display operations
- Collision handling with sequential probing

### 2. Sorting Algorithms
Four classic sorting algorithms:
- **Selection Sort**: O(n²) time complexity, in-place sorting
- **Insertion Sort**: O(n²) time complexity, efficient for small datasets
- **Merge Sort**: O(n log n) time complexity, divide-and-conquer approach
- **Heap Sort**: O(n log n) time complexity, uses heap data structure

### 3. Binary Search Tree
Complete BST implementation with:
- Insertion and search operations
- Deletion handling all three cases (leaf, single child, two children)
- Three traversal methods: inorder, preorder, postorder
- Utility functions: min/max, node count, height calculation
- BST validation and tree visualization

### 4. Graph Traversals
Graph implementation using adjacency lists with:
- Support for both directed and undirected graphs
- Depth-First Search (recursive and iterative)
- Breadth-First Search (iterative)
- Graph operations: add vertex/edge, check neighbors, verify edges

## 🛠️ Requirements
- Python 3.6+
- No external dependencies

## 📊 Sample Usage
```python
# Example: Using the Linear Probing Hash Table
ht = LinearProbingHashTable(size=10)
ht.insert(25, "Alice")
ht.insert(35, "Bob")
print(ht.search(35))  # Output: Bob

# Example: Sorting with Merge Sort
m = MergeSort()
data = [4, 1, 7, 3, 6]
sorted_data = m.sort(data)  # Output: [1, 3, 4, 6, 7]

# Example: BST operations
bst = BST()
bst.insert(50)
bst.insert(30)
bst.insert(70)
print(bst.inorder())  # Output: [30, 50, 70]

# Example: Graph DFS
g = Graph()
g.add_edge("A", "B")
g.add_edge("A", "C")
print(g.dfs_recursive("A"))  # Output: ['A', 'B', 'C']
```

## 📝 Key Concepts Covered
- **Hashing**: Collision resolution, probing sequences
- **Sorting**: Time/space complexity, algorithm design patterns
- **Trees**: Binary tree properties, recursion, traversal methods
- **Graphs**: Adjacency representation, search algorithms, graph types

## 🎯 Learning Objectives
- Understand implementation details of core algorithms
- Analyze time and space complexity
- Learn practical applications of each data structure
- Develop problem-solving skills with algorithmic thinking

## 🤝 Contributing
Feel free to fork this repository and submit pull requests with improvements or additional algorithms.

## 📄 License
This project is open source and available for educational use.

---
*Ideal for computer science students, coding interview preparation, and algorithm enthusiasts.*
