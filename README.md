# Notes

Exercising my knowledge in data structures and algorithms
These notes are based on the LinkedIn course: Programming Foundations: Data Structures Instructed by Kathryn Hodge 

# Algorithms

Algorithm - A set of instructions to describe the exact result

# Data Structures

- Data is information that is stored or processed by a computer
- Data Structures are containers, allowing to combine several pieces of data into a single structure
  - Data structures help connect and group data
  - Data structures give us organization, storage, and access
- Data Structure - A collection with a defined way of accessing and storing items

### Data Type

- Data Type - An attribute of data that describes the values it can have and how the data can be used
- Different numerical data types have different precision, meaning the difference is the range of numerical values the data type can store
  - Ex. Difference between short, int, and long are just the precision
    - In Java:
      - Short - Range of -32,768 to 32,767 - 16 bits
      - Int - Range of ~-2 billion to ~2 billion - 32 bits
      - Long - Range of -(2^63) to 2^63 - 64 bits
- Primitive types have fixed sizes of bits, we will always know the size of this primitive types
- Reference Types
  - Data types implemented with data structures are called reference types
    - A reference is used to find the location of where the data lives in memory
  - Object is a value in memory referenced by an identifier
  - Reference types reference their specific value from an address of where an item is stored rather than direct access to the data itself
    - If the address changes, the value that the variable represents also changes
  - A pointer is used to store the address of where the structure or part of the structure is in memory

### Size of Data Structure

Size of data structure depends on

- Allocated space for structure
- Number of pieces of data
- Size of each data piece

### Array

Collection of elements, where each item is identified by an index or key