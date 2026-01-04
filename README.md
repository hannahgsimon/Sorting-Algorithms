# Sorting Algorithms in Java

This project implements and applies multiple **sorting algorithms** in Java, including **selection sort, radix sort, merge sort (recursive), and insertion sort**. The algorithms are used to sort real-world data models (students and faculty) based on different attributes, demonstrating both algorithmic understanding and object-oriented design.

---

## ✨ Features
- Selection sort for ascending ID ordering
- Radix sort for descending ID ordering
- Recursive merge sort for GPA-based sorting
- Insertion sort for workload-based sorting
- Custom comparison logic using `Comparable`
- Menu-driven console interface for interactive testing
- Optional sample data generation for quick evaluation

---

## 🛠️ Technologies Used
- Java
- Object-Oriented Programming
- Comparable interface
- Recursive algorithms

---

## 📁 Project Structure
```bash
.
├── SortingAlgorithmsApp.java   # Main driver program
├── SortMethods.java            # Sorting algorithm implementations
├── SortProjectData.java        # Data management and coordination
├── Student.java                # Student data model (implements Comparable)
├── Faculty.java                # Faculty data model (implements Comparable)
└── README.md
```

---

## ⚙️ How It Works
- The program manages two data sets, students and faculty, and applies different sorting strategies depending on the data type and attribute:
  - IDs can be sorted using selection sort or radix sort
  - Student GPAs are sorted using recursive merge sort
  - Faculty course loads are sorted using insertion sort
- Both `Student` and `Faculty` implement the `Comparable` interface, allowing flexible and reusable sorting logic.
- An optional hidden mode (input -1) populates the system with sample data to allow immediate testing without manual input.

---

## 🧪 Build & Run
Compile all files:
```bash
javac *.java
```

Run the program:
```bash
java Sorting-Algorithms
```

---

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## 👤 Author
Hannah G. Simon
