
# **Hash Table Cheat Sheet for Beginners**

## **What is a Hash Table?**

- **Analogy:** Think of a hash table as a massive library where books are stored not alphabetically by author or title, but rather by a unique code (hash) assigned to each book. This code helps you find any book instantly, without having to search through every shelf.
- **Definition:** A hash table is a data structure that stores key-value pairs. It uses a hash function to compute an index into an array of slots, from which the desired value can be found.

### **Why Use Hash Tables?**

- **Efficiency:** Hash tables are incredibly efficient for lookup, add, and delete operations, typically offering O(1) complexity.
- **Flexibility:** They can store any type of data—numbers, strings, objects—and allow for fast data retrieval using keys.

#### **How Hash Tables Work:**

1. **Hash Function:** Converts keys into array indices.
   - Must be consistent: Same key always produces the same index.
   - Should minimize collisions: Different keys producing the same index.
2. **Handling Collisions:** Two main ways to handle collisions:
   - **Chaining:** Each array slot stores a list of items that hash to the same index.
   - **Open Addressing:** Finds another slot using a probing sequence if the first is full.

#### **Key Components:**

- **Key:** The identifier used to store and retrieve data.
- **Value:** The data associated with a key.
- **Hash Function:** Transforms the key into a hash code, which is then converted to an index.
- **Bucket/Slot:** The unit of storage within the array.
- **Collision:** Occurs when two keys hash to the same index.

#### **Walkthrough Example:**
1. **Storing a Value:**
   - Key: "username"
   - Value: "user1234"
   - Hash function converts "username" into an index, e.g., 4.
   - The key-value pair is stored in index 4 of the array.

2. **Retrieving a Value:**
   - Provide the key "username" to the hash table.
   - Hash function calculates the index 4.
   - The value "user1234" is found at index 4 and returned.

#### **Vocabulary:**
- **Load Factor:** Ratio of the number of stored elements to the table size. Affects performance.
- **Rehashing:** Process of resizing the hash table and rehashing all existing keys.

#### **Implementation Tips:**
- Choose a good hash function to minimize collisions.
- Plan for collisions with a collision resolution strategy.
- Consider dynamic resizing to maintain an efficient load factor.

#### **Quiz:**
1. What is the purpose of a hash function in a hash table?
2. Explain one method to handle collisions in hash tables.
3. What does it mean to rehash a hash table?

#### **Practice:**
- Implement a simple hash table in your favorite programming language.
- Experiment with different hash functions and measure the performance impact.
- Try adding, deleting, and retrieving various key-value pairs to understand the process fully.

