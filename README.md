<div align="center">

# ☕ JAVA Programs Collection
## Data Structures, Algorithms & Problem Solving

[![Java](https://img.shields.io/badge/Java-11+-orange?logo=java&logoColor=white)](https://www.java.com/)
[![DSA](https://img.shields.io/badge/DSA-Implementation-blue?logo=databricks&logoColor=white)](https://github.com/rajsurya519sr/JAVA-Program)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

*A comprehensive collection of Java programs covering basic to advanced concepts, data structures, algorithms, and problem-solving patterns.*

[Report Bug](https://github.com/rajsurya519sr/JAVA-Program/issues) • [Request Feature](https://github.com/rajsurya519sr/JAVA-Program/issues)

</div>

---

## 🎉 What's Inside

### 📚 Core Java Fundamentals
- Basic Syntax & Variables
- Control Structures (If-Else, Switch, Loops)
- Object-Oriented Programming (OOP)
- Classes & Objects
- Inheritance & Polymorphism
- Abstraction & Encapsulation
- Exception Handling
- Collections Framework

### 🧮 Data Structures
- Arrays & ArrayLists
- Linked Lists (Singly, Doubly, Circular)
- Stacks & Queues
- Trees (Binary, BST, AVL)
- Graphs (BFS, DFS)
- Hash Tables & HashMaps
- Heaps (Min Heap, Max Heap)

### 🔬 Algorithms
- Sorting (Bubble, Selection, Insertion, Merge, Quick)
- Searching (Linear, Binary)
- Recursion & Backtracking
- Dynamic Programming
- Greedy Algorithms
- Graph Algorithms
- String Algorithms

### 💡 Problem Solving Patterns
- Two Pointers
- Sliding Window
- Fast & Slow Pointers
- Merge Intervals
- Cyclic Sort
- In-place Reversal
- Tree BFS & DFS
- Backtracking

---

## 🚀 Getting Started

### Prerequisites

```bash
Java 11 or higher
Any IDE (IntelliJ IDEA, Eclipse, VS Code)
Git
```

### Installation

```bash
# Clone the repository
git clone https://github.com/rajsurya519sr/JAVA-Program.git
cd JAVA-Program

# Compile and run any program
javac ProgramName.java
java ProgramName
```

---

## 📊 Project Structure

```
JAVA-Program/
├── Basics/
│   ├── HelloWorld.java
│   ├── Variables.java
│   └── ControlStructures.java
├── OOP/
│   ├── Classes/
│   ├── Inheritance/
│   └── Polymorphism/
├── DataStructures/
│   ├── Arrays/
│   ├── LinkedLists/
│   ├── Stacks/
│   ├── Queues/
│   ├── Trees/
│   └── Graphs/
├── Algorithms/
│   ├── Sorting/
│   ├── Searching/
│   ├── Recursion/
│   └── DynamicProgramming/
└── ProblemSolving/
    ├── Easy/
    ├── Medium/
    └── Hard/
```

---

## 📚 Key Topics Covered

### Object-Oriented Programming
```java
// Example: Inheritance
class Animal {
    void eat() { System.out.println("Eating..."); }
}

class Dog extends Animal {
    void bark() { System.out.println("Barking..."); }
}
```

### Data Structures
```java
// Example: Linked List Implementation
class Node {
    int data;
    Node next;
    
    Node(int data) {
        this.data = data;
        this.next = null;
    }
}
```

### Algorithms
```java
// Example: Binary Search
public static int binarySearch(int[] arr, int target) {
    int left = 0, right = arr.length - 1;
    
    while (left <= right) {
        int mid = left + (right - left) / 2;
        
        if (arr[mid] == target) return mid;
        if (arr[mid] < target) left = mid + 1;
        else right = mid - 1;
    }
    
    return -1;
}
```

---

## 🎯 Learning Path

1. **Start with Basics** - Understand syntax, variables, and control structures
2. **Master OOP** - Learn classes, inheritance, polymorphism
3. **Study Data Structures** - Implement arrays, linked lists, stacks, queues
4. **Practice Algorithms** - Sorting, searching, recursion
5. **Solve Problems** - Apply patterns to real-world problems

---

## 👋 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/NewProgram`)
3. Add your Java programs with comments
4. Commit your changes (`git commit -m 'Add new program'`)
5. Push to the branch (`git push origin feature/NewProgram`)
6. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🙋 Support

If you found this helpful, please consider:
- ⭐ Starring the repository
- 📏 Sharing with others
- 👨‍🏫 Using for learning
- 💬 Providing feedback

---

## 👤 Author

**Surya Raj**
- GitHub: [@rajsurya519sr](https://github.com/rajsurya519sr)
- LinkedIn: [Surya Raj](http://in/suryaraj)
- Email: rajsurya519sr@gmail.com

---

<div align="center">

**Made with ❤️ by [Surya Raj](https://github.com/rajsurya519sr)**

[Back to top](#java-programs-collection)

</div>
