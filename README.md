# Assignment 3 - HashTable and Binary Search Tree (BST)

This project is created as part of the Algorithms and Data Structures course (ADS).

##  Project Structure

- **MyHashTable.java**
  - Custom implementation of a HashTable using chaining for collision resolution.
  - Supports methods:
    - `put(K key, V value)`
    - `get(K key)`
    - `remove(K key)`
    - `contains(V value)`
    - `getKey(V value)`
    - `size()`
- **MyTestingClass.java**
  - Custom key class used for testing HashTable.
  - Has its own `hashCode()` method without using default Java hashing methods.
- **Main.java**
  - Testing class.
  - Inserts 10,000 random elements into `MyHashTable`.
  - Prints the number of elements in each bucket.
- **BST.java**
  - Custom implementation of a Binary Search Tree (BST) without recursion.
  - Supports methods:
    - `put(K key, V value)`
    - `get(K key)`
    - `delete(K key)`
    - `size()`
    - `iterator()` — with **in-order traversal**.

##  How to Run
