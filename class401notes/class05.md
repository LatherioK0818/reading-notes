# Linked List Cheat Sheet

## Basic Concepts
- **Linked List:** A sequential collection of elements (nodes), where each node points to the next.
- **Node:** An individual part of a linked list, containing the data and a reference to the next node.
- **Head:** The first node in a linked list.
- **Tail:** The last node in a linked list, typically pointing to null.

#### Node Structure
```python
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None
```

#### Creating a Linked List
```python
class LinkedList:
    def __init__(self):
        self.head = None
```

#### Basic Operations

1. **Add at the Front:**
   - Create a new node.
   - Set its `next` to the current head.
   - Update the head to be this new node.
   ```python
   def add_at_front(self, data):
       node = Node(data)
       node.next = self.head
       self.head = node
   ```

2. **Add at the End:**
   - Create a new node.
   - If the list is empty, set it as the head.
   - Otherwise, traverse to the end and link the new node.
   ```python
   def add_at_end(self, data):
       node = Node(data)
       if not self.head:
           self.head = node
           return
       last = self.head
       while last.next:
           last = last.next
       last.next = node
   ```

3. **Delete a Node (by value):**
   - Locate the node preceding the one you want to delete.
   - Change its `next` reference.
   ```python
   def delete_node(self, key):
       temp = self.head
       if temp and temp.data == key:
           self.head = temp.next
           temp = None
           return
       prev = None
       while temp and temp.data != key:
           prev = temp
           temp = temp.next
       if temp is None:
           return
       prev.next = temp.next
       temp = None
   ```

4. **Search for a Node:**
   - Traverse the list.
   - Return true if the node is found.
   ```python
   def search(self, key):
       current = self.head
       while current:
           if current.data == key:
               return True
           current = current.next
       return False
   ```

5. **Display the List:**
   - Traverse and print each node.

   ```python
   def print_list(self):
       temp = self.head
       while temp:
           print(temp.data, end=" ")
           temp = temp.next
   ```
