# C# ALGORITHMS [![](https://travis-ci.org/aalhour/C-Sharp-Algorithms.svg?branch=master)](https://travis-ci.org/aalhour/C-Sharp-Algorithms)

#### Implementations of Data Structures and Algorithms in C#.

## DESCRIPTION

It originally started out as an interview preparation project. However, after receiving a great amount of positive responses on [reddit](https://redd.it/3etf9f), and noticing excitement from a few [GitHubers](https://github.com/aalhour/C-Sharp-Algorithms/graphs/contributors) to contribute furthermore to it, the project took on a different meaning. So I decided to keep maintaining it as a reference for data structures and algorithm implementations in C# as well as my research side-project under these topics.

#### Solution Hierarchy:

This is a C#.NET solution-project, and it contains three subprojects:

 1. [Algorithms](Algorithms): A class library project. Contains the Algorithms implementations.
 2. [Data Structures](DataStructures): A class library project. Contains the Data Structures implementations.
 3. [Main Program](MainProgram): Contains tests for the data structures and algorithms projects.

#### Requirements:
 1. C# 5
 2. .NET 4.5

#### A Note to Contributors:
If you wish to contribute to C# ALGORITHMS, then please make sure you check out the [Contribution Guidelines](CONTRIBUTING.md) first.

Note: The projects where tested on Xamarin Studio (MonoDevelop) on OSX 10, and Visual Studio on Windows 7.


## DATA STRUCTURES

#### Lists:
 * [Skip List](DataStructures/Lists/SkipList.cs).
 * [Array List](DataStructures/Lists/ArrayList.cs).
 * [Stack](DataStructures/Lists/Stack.cs).
 * [Queue](DataStructures/Lists/Queue.cs).
 * [Single-Linked List](DataStructures/Lists/SLinkedList.cs).
 * [Double-Linked List](DataStructures/Lists/DLinkedList.cs).

#### Heaps:
 * [Binary-Min Heap](DataStructures/Heaps/BinaryMinHeap.cs).
 * [Binary-Max Heap](DataStructures/Heaps/BinaryMaxHeap.cs).
 * [Binomial-Min Heap](DataStructures/Heaps/BinomialMinHeap.cs).
 
#### Priority Queues:
 * [Min-Priority Queue](DataStructures/Heaps/MinPriorityQueue.cs).
 * [Keyed Priority Queue](DataStructures/Heaps/KeyedPriorityQueue.cs).
 
#### Hashing Functions:
 * [Prime Hashing Family](DataStructures/Hashing/PrimeHashingFamily.cs).
 * [Universal Hashing Family](DataStructures/Hashing/UniversalHashingFamily.cs).

#### Hash Tables:
 * [Chained Hash Table](DataStructures/Dictionaries/ChainedHashTable.cs).
 * [Cuckoo Hash Table](DataStructures/Dictionaries/CuckooHashTable.cs).

#### Trees:
 * [Trie](DataStructures/Trees/Trie.cs).
 * [Trie Map](DataStructures/Trees/TrieMap.cs).
 * [AVL Tree](DataStructures/Trees/AVLTree.cs).
 * [Red-Black Tree](DataStructures/Trees/RedBlackTree.cs).
 * [Binary Search Tree](DataStructures/Trees/BinarySearchTree.cs).
 * [Augmented Binary Search Tree](DataStructures/Trees/AugmentedBinarySearchTree.cs).
 
#### Graphs:
 * Undirected Graphs:
  + [Clique Graphs](DataStructures/Graphs/CliqueGraph.cs).
  + [Undirected Sparse Graph](DataStructures/Graphs/UndirectedSparseGraph.cs).
  + [Undirected Dense Graph](DataStructures/Graphs/UndirectedDenseGraph.cs).
 * Undirected Weighted Graphs:
  + [Undirected Weighted Sparse Graph](DataStructures/Graphs/UndirectedWeightedSparseGraph.cs).
  + [Undirected Weighted Dense Graph](DataStructures/Graphs/UndirectedWeightedDenseGraph.cs).
 * Directed Graphs:
  + [Directed Sparse Graph](DataStructures/Graphs/DirectedSparseGraph.cs).
  + [Directed Dense Graph](DataStructures/Graphs/DirectedDenseGraph.cs).
 * Directed Weighted Graphs:
  + [Directed Weighted Sparse Graph](DataStructures/Graphs/DirectedWeightedSparseGraph.cs).
  + [Directed Weighted Dense Graph](DataStructures/Graphs/DirectedWeightedDenseGraph.cs).


## ALGORITHMS

#### Sorting:
 * [Insertion Sort](Algorithms/Sorting/InsertionSorter.cs).
 * [Quick Sort](Algorithms/Sorting/QuickSorter.cs).
 * [Merge Sort](Algorithms/Sorting/MergeSorter.cs).
 * [Heap Sort](Algorithms/Sorting/HeapSorter.cs).
 * [BST Sort](Algorithms/Sorting/BinarySearchTreeSorter.cs).
 * [Counting Sort](Algorithms/Sorting/CountingSorter.cs).
 * [LSD Radix Sort](Algorithms/Sorting/LSDRadixSorter.cs).

#### Graphs:
 * Graph Search:
  + [Depth-First Searcher](Algorithms/Graphs/DepthFirstSearcher.cs).
  + [Breadth-First Searcher](Algorithms/Graphs/BreadthFirstSearcher.cs).
 * Shortest Paths:
  + [Breadth-First SPs](Algorithms/Graphs/BreadthFirstShortestPaths.cs).
  + [Bellman-Ford SPs](Algorithms/Graphs/BellmanFordShortestPaths.cs).
  + [Dijkstra SPs](Algorithms/Graphs/DijkstraShortestPaths.cs).
  + [Dijkstra All-Pairs SPs](Algorithms/Graphs/DijkstraAllPairsShortestPaths.cs).
 * DFS Applications:
  + [Cycles Detector](Algorithms/Graphs/CyclesDetector.cs).
  + [Topological Sorter](Algorithms/Graphs/TopologicalSorter.cs).
 * BFS Applications:
  + [Connected Components](Algorithms/Graphs/ConnectedComponents.cs).
  + [Bipartite Graphs Coloring](Algorithms/Graphs/BipartiteColoring.cs).

#### Strings:
 * [Permutations and Anagrams](Algorithms/Strings/Permutations.cs).
 * [Edit Distance](Algorithms/Strings/EditDistance.cs).
  + Uses a generic custom class for passing costs: [EditDistanceCostsMap\<T\>](Algorithms/Strings/EditDistanceCostsMap.cs).

#### Numeric:
 * [Catalan Numbers](Algorithms/Numeric/CatalanNumbers.cs).

#### Visualization:
 * [Tree Drawer](DataStructures/Trees/TreeDrawer.cs).


## CONTRIBUTORS
 * [Edgar Carballo Domínguez](https://github.com/karv).


## LICENSE
This project is licensed under the [MIT License](LICENSE).
