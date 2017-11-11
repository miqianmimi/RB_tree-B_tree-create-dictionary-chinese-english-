# RB_tree-B_tree-create-dictionary-chinese-english-
Project 1

1 Background
BSTs are good data structures for concepts like SETs or MAPs. In this course, you will learn two very important BSTs, RB-Tree and B-Tree. The former one is the backbone for std::map of C++, while the later one is a key data structure used in databases.

2 Your Mission
You mission is to design and implement a English-Chinese dictionary with the trees. You program should be able to store informations in-memory and respond to user’s commands.

3 Specification
Your program should be able to react to:

INSERT key value insert a key-value pair into your tree, if the key already exists, write to standard output: Error:key conflict

PUT key value update a key-value pair if key already exists otherwise insert the key-value pair as a new one 

GET key write to the standard output the value which is mapped to the given key, if the key doesn’t exist,write to standard output: Error: key missing 

DEL key delete the key-value pair indexed by key, if the key doesn’t exist, write to standard output: Error:key missing

LOAD filename read a file, the file contains interleaved keys and values, these key-value pairs should be PUT into your trees 

DUMP you should write to the standard output all the key-value pairs, these pairs should appear in key’s lexicographical order.

4 Programming
You should implement the problem in both RB-tree and B-tree in two separate files.

5 Documentation
Your documentations should at least contain your design details of your program and your thoughts about the project.
