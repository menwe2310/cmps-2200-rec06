# CMPS 2200 Recitation 06
## Answers

**Name:** Menwe Okafor
**Name:**_________________________


Place all written answers from `recitation-06.md` here for easier grading.



- **1)** Before we implement a heap, let's consider if we just maintain
 an unordered list/sequence. 

  - **1a) (1 pt)** What is the work/span of *deleteMin*?
    O(n)

  - **1b) (1 pt)** What is the work/span ofand *insert(x)*?
    O(1)

- **2a) (1 pt)** For a heap with $n$ elements, what does this imply about the depth of the associated almost-complete binary tree? 
  log n

- **2b) (1 pt)** By maintaining the heap property, where is the minimum element of the heap? Can we say anything about the maximum element?
  For the minimum, it is the root H[0]
  For the max, we know its one of the leaves since a node with children can't be the max

- **4a) (1 pt)** What is the work/span of *reheapUp*($x$)?
  O(log n)

- **4b) (1 pt)** What is the work/span of *reheapDown*($x$)?
  O(log n)

- **6) (1 pt)** What is the work and span of `heapsort`?
  O(n log n)
