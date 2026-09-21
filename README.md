# Tree Isomorphism

Python implementation for detecting whether two undirected trees are isomorphic using canonical encoding.

## Overview

This project implements a tree isomorphism algorithm based on canonical representations.

The algorithm:

1. Validates the input trees
2. Finds the center(s) of each tree
3. Roots the tree at its center
4. Generates a canonical encoding
5. Compares the resulting encodings

If the canonical encodings are equal, the trees are isomorphic.

## Technologies

- Python
- Graph Algorithms
- Tree Algorithms
- Data Structures

## Algorithm

The implementation uses the concept of canonical encoding to represent the structure of a rooted tree independently of the ordering of its vertices.

For each input tree, the algorithm identifies its center and generates a canonical representation. The representations of the two trees are then compared to determine whether they are isomorphic.

## Project Structure

```

├── README.md
├── T6.md
├── dados/
│   ├── iso-path4-a.txt                  
│   ├── iso-path4-b.txt               
│   ├── nao-iso-estrela5.txt 
│   ├── nao-iso-path5.txt       
│   ├── tree_dois_centros_a.txt    
│   ├── tree_dois_centros_b.txt  
│   └── invalid-ciclo3.txt   
└── src/
    ├── main.py                    
    ├── graph.py                   
    └── tree_isomorphism.py        
```
