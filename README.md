# String-Analytics-Showcase
This project implements several algorithms for analysing ordered collections of strings in Java. It was developed as part of a university coursework module focusing on searching, frequency analysis, and string manipulation in sorted data structures.

---

## Implemented Algorithms

All operations assume the list is in **ascending order**, which enables correct frequency analysis and efficient binary search.

| Method | Description |
|--------|-------------|
| `shortestWord` | Returns the shortest string. Ties are resolved by returning the earliest occurrence. |
| `countUnique` | Counts how many strings appear **exactly once** in the sorted list. |
| `countPalindrome` | Counts strings that read the same forwards and backwards. |
| `leastFrequent` | Finds the string that appears least often. If tied, returns the earliest in order. |
| `countLess` | Uses **binary search** to count how many strings are less than a given string. |
| `topKFrequent` | Returns the **k most frequent** strings in order of frequency. |

These algorithms demonstrate:
- Handling of **sorted structures**
- Use of **invariants**
- Application of **binary search**
- Counting, hashing, and string analysis

---

## Supporting Components

### `StringList`
A custom wrapper around `ArrayList<String>` used to:
- Load words from text files in ascending order

### `StringTest`
A console-based test program that:
- Loads strings from multiple test sets (tiny, small, medium, large)
- Executes each analytics method
- Prints results for verification and debugging

---

## Academic Integrity Notice

This work was submitted as part of an assessed coursework.  
To protect academic policy and avoid enabling plagiarism:

- Full source code is stored in a **private repository**
- Only recruiters may be granted access on request

