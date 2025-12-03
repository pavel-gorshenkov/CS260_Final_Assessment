# CS260_Final_Assessment
Implemented recursive sumOfLeafNodes and copyEven functions in table.cpp. Fixed logic to strictly separate concerns: one function sums leaves, the other deep copies even nodes. Verified 0 memory leaks with Valgrind and included Makefile.
#Overview
The project focuses on recursive traversal and memory management in a BST structure. It links against a supplied object file to perform specific operations on tree data.

#Sum of Leaf Nodes
A recursive function (sumOfLeafNodes) that traverses the tree to identify and sum the values of all leaf nodes (nodes with no children).

#Traversal and Copy
A recursive function (copyEven) that deep copies only the even numbers from a source tree into a new destination Binary Search Tree.

#Run commands
- make
- ./final_app

#Requirements
- GNU Make
- g++ compiler (C++11 standard)
