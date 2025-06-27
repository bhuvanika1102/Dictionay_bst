# 📚 Dictionary Using Binary Search Tree (BST)

A mini project implemented in **C programming** that simulates dictionary functionality using the **Binary Search Tree (BST)** data structure. This project was developed as part of the **Data Structures Lab** and demonstrates how BSTs can be used for efficient searching, insertion, and in-order traversal.

---

## 📌 Project Overview

This project is a simple digital dictionary where:

- Each word is stored in a **node** of a binary search tree.
- Each node contains a `word` and its `meaning`.
- Operations include:
  - 📖 **Search** for a word
  - ➕ **Insert** a new word and meaning
  - 👁️ **View** all dictionary entries (in sorted order using in-order traversal)

---

## 🧠 Data Structure Used

- **Binary Search Tree (BST)**  
Each node contains:
```c
struct dict {
    char word[10];
    char meaning[20];
    struct dict *left, *right;
};
```

---

## 🚀 Features

- ✅ Insert new words into the dictionary
- ✅ Search for a word and retrieve its meaning
- ✅ Display all words and meanings using in-order traversal
- 📈 Efficient searching (O(log n) in average cases)

---

## 🔧 How It Works

- Insertion is done based on **lexicographical order**.
- Duplicates are not allowed.
- Traversal is done in **in-order** to return sorted dictionary output.

---

## 💻 How to Compile & Run

1. Open the source file in **Dev C++** or any C compiler.
2. Compile the program:
```bash
gcc dictionary_bst.c -o dictionary
```
3. Run the executable:
```bash
./dictionary
```

4. Choose from the menu:
```
1. Search
2. Insert
3. View
4. Exit
```

---
## 📦 Requirements

- C Compiler (Dev C++ or GCC)
- Windows/Linux Machine

---

## 📚 Applications of BST in Dictionary

- 🔍 Real-time search and autocomplete systems
- 📖 Digital dictionaries and word-indexing tools
- 📂 Database indexing
- 📊 Sorted data maintenance in real-time

---

## ⚠️ Known Issues / Limitations

- ❌ No deletion operation implemented
- 📏 Word and meaning length is limited
- 📎 No file storage — data exists only during runtime

---

## ✅ Future Enhancements

- Implement deletion operation
- Add file-based persistence (save/load from file)
- Extend to support synonyms/antonyms
- Convert to graphical dictionary using GUI in C++

---

## 📚 References

- [GeeksforGeeks – BST in C](https://www.geeksforgeeks.org/binary-search-tree-data-structure/)
- [YouTube – C Projects using Data Structures](https://www.youtube.com/)
- [TutorialsPoint – Binary Search Tree](https://www.tutorialspoint.com/data_structures_algorithms/tree_data_structure.htm)

---

## 📞 Contact Me
Feel free to reach out to me via email at bhuvani1102@gmail.com or connect with me on LinkedIn at https://www.linkedin.com/in/bhuvani1102

