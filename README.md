# Aproximate Nearest neighbor (ANN):

### a) LSH

Locality Sensitive Hashing (LSH) refers to a set of algorithmic techniques used to speed up the search for neighbours or duplicate data in the samples.
LSH can be used to filter out duplicates in a database, scrape web pages or any websites at an impressive speed.

### b) exhaustive search

The exhaustive search also know as  brute-force search, is a very general problem-solving technique and algorithmic paradigm that consists of systematically
enumerating all possible iterations for the solution and checking whether each iteration satisfies the problem's statement.
even though simple in it has high time complexity.

### c) product quantization

Works on the idea to decomposes the space into a Cartesian product of low dimensional subspaces and to quantize each subspace separately. A vectoris represented
by a short code composed of its subspace quantization indices. The Euclidean distance between two vectors can be efficiently estimated from their code

### d) trees and graphs

An Annoy index consists of N binary trees, where each tree partitions the vector space using random hyperplanes at each node in the tree.

### e) hnsw

HNSW (Hierarchical Navigable Small World Algorithm) builds a hierarchical graph incrementally, and has great search performance with high recall, motivating us 
to prototype it for comparison. Each node in the graph represents a point in the vector space, and nodes are linked to other nodes that are close in space.
