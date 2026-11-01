# Data Structures & Algorithms Core Syllabus

## Module 1: Complexity Analysis & Architectural Trade-offs
- Time complexity: Big-O, Big-Theta, Big-Omega notation.
- Common bounds: O(1), O(log n), O(n), O(n log n), O(n^2), O(2^n).
- Space complexity: Auxiliary space vs input space.
- Architectural trade-offs: Memory locality vs pointer indirection, cache hits vs CPU branch prediction.

## Module 2: Linear Data Structures: Arrays & Lists
- Dynamic Arrays: Contiguous memory, amortized O(1) append, O(n) arbitrary insertion and deletion.
- Linked Lists: Singly and doubly linked lists, non-contiguous pointer nodes, O(1) head/tail insertion, O(n) traversal.
- Deques and Stacks: LIFO and FIFO invariants, ring buffers.

## Module 3: Hashing & Maps
- Hash functions: Determinism, uniform distribution, avalanche effect.
- Collision resolution: Separate chaining (linked lists or trees) vs open addressing (linear probing, quadratic probing, double hashing).
- Load factors, re-hashing, amortized O(1) lookup.

## Module 4: Searching & Sorting Algorithms
- Binary Search: Invariant preservation on sorted intervals, midpoint calculation avoiding integer overflow.
- Divide & Conquer Sorting: Merge Sort (stable, O(n log n) time, O(n) space), Quick Sort (unstable, in-place, O(n log n) average, O(n^2) worst case).
- Adaptive Sorting: Insertion Sort (O(n) best for nearly sorted data), Timsort hybrid strategies.
