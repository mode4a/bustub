# Bustub (Relational Database Management System)

> **Note on Academic Integrity:** In accordance with the CMU 15-445/645 academic integrity policy, the source code for this project is hosted in a **private repository**. 

## 🏆 Achievement
* **Leaderboard Rank:** Ranked **40th out of 200+ global submissions** for the B+Tree Indexing implementation.

## 🛠️ Technical Implementation
This project involved building a disk-oriented DBMS from the ground up in C++11/17. Key components I developed include:

* **Storage Engine:** Thread-safe Buffer Pool Manager using LRU-K replacement policy and RAII Page Guards to prevent memory leaks and deadlocks.
* **Indexing:** A concurrent B+Tree supporting point lookups, range scans, insertions, and deletions. Implemented **Latch Coupling** to allow multiple threads to traverse the tree simultaneously.
* **Execution Engine:** A Volcano-style query execution model with support for 10+ operators, including Nested Loop Joins, Aggregations, and Sequential Scans.

## 📂 How to View the Code
I am happy to walk through the codebase or provide temporary access to the private repository for hiring managers and technical recruiters.

**Please contact me at:**
* 📧 [mostafa.mahmoud.mohamed.mabrok@gmail.com](mailto:mostafa.mahmoud.mohamed.mabrok@gmail.com)
* 💼 [LinkedIn Profile](https://www.linkedin.com/in/mostafa-mahmoud-063073266/)
