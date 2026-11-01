# Module 3: Hashing & Maps

## 1. The Concept
Mapping a key to an index using a hash function to achieve $O(1)$ average lookup.

## 2. Collision Handling
- **Separate Chaining**: Using a list (or tree) at each bucket.
- **Open Addressing**: Finding the next available slot.

## 3. Worst Case
If all items collide, a Map can degrade to $O(n)$ (Linked List) or $O(\log n)$ (Balanced Tree).
