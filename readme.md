## CHITRANAGARI : SMART CITY DESIGN

## Handled by SANIKA MADIHAL : 01FE23BCS135

### Business case identified
1. Waste management for industries
   Chitranagari is a city located in Rajasthan which is facing problems in managing the 
   industrial waste caused by its handicrafts and textile industries and also since it is 
   located near the fields the disposal might be hazardous for crops. The improper disposal of 
   waste might rise issues like polltuion of water bodies and loss of yield in the fields. This 
   needs a sustainable sensitive waaste management system that helps in maintaining and 
   preserving the clean environment for future generations.
3. Import and export of goods
4. Improving living standards for farmers

## COURSE LEARNING REFLECTIONS
### 1. Iteration, Recursion and Bactracking
There are several kind of phenomena we see in the nature which describes or can be solved using the daa techniques like iteration, recursion and backtracking.
   1. For instance when it comes to iteration the rise and fall of the tidal waves is one of the best example to explain the iteration process where there is repeated pattern or regularity between each tide.
   2. Recursion is best described by the pattern of the cauliflower which shows the recursive pattern of the flower from stem to the tips.
   3. Whereas, backtracking is widely applicable in navigating the maze OR sudoku. We can use these natural problem solving techniques in daa to solve similar kind of problems in algorithmic world
### 2. Time and Space efficiency and orders of growth
Time efficiency is defined as the time taken by algorithm to execute or how long an algorithm takes to execute. Space efficiency is defined as the extra space taken by the algorithm. Importance of time and space efficiency is that when there is a large set of data and if the algorithm is inefficient it might not run properly or it may not give instant outputs(slow processing). The different class of problems are:
   1. Constant time : The runtime remains the same regardless of the input size.Represented as O(1).
   2. Logarithmic time : The runtime grows slowly, increasing logarithmically as the input size grows. Represented as O(logn).
   3. Linear time : The runtime increases proportionally to the input size. Represented as O(n).
   4. Linearithmic time : The runtime grows faster than linear but slower than quadratic. Represented as O(nlogn).
   5. Quadratic time : The runtime grows quadratically. Represented as O(n^2)
   6. Cubic time : The runtime increases even more steeply that quadratic. Represented as O(n^3).
   7. Exponential time : The runtime grows exponentially, with each additional input. Represented as O(2^n).
   8. Factorial time : The runtime grows extremely fast.Represented as O(n!).
### 3. Design Principles
These principles helps us in problem solving in data structures by relating and breaking down the problem according to the available principles. Also these provides the best efficiency by reduicing space and time complexity. Some principles like partioning allows us to manange different types of large data sets. These principles are reliable and accurate for overcoming the challenges.
### 4. Tree Data Structures
The hierarchical data structures like tree are based on parent-child relationship and these are:
   1. BST: This helps in searching, insertion and deletion of sorted data but sometimes it can be unbalanced affecting the efficiency.
   2. AVL: This is balanced BST and has an efficiency of O(log n).
   3. 2-3 tree: This is used for dynamic set of data. It is simple compared to AVL.
   4. Red-Black tree: Even this is used in case of dynamic dataset with less number of rotations.
   5. Heap: This is used in case of problems like maximum/minimum.
   6. Trie: This is based on the prefix of the string. Here string is retrieved by traversing.
### 5. Array Query Algorithm
Array query algorithms is a technique used to operate arrays efficiently with respect to particular query like update, maximum or minimum.
These are used to obatin the most efficient algorithm by reducing the complexities and to handle large datasets. Different types of principles used are divide and conquer, lazy propagation, etc. to operate efficiently. Coming to applications we can use fenwick tree, segment tree and  many moe for data analysis and dynamic updtaes and also for range queries.
### 6. Difference between Tree and Graph
A tree deosnt have cycles in it and it follows hierarchy. Traversal follows in-order, post-order and pre-order.
A graph consists of cycles and it doesnt follow hierarchy. Traversal is done thriugh BFS and DFS.
Application of tree include in searching and sorting of large datasets and also priority queues. Graphs are mainly used in networking and navigation like roadlines airlines, etc.

### 7. Sorting and Searching
Sorting organizes data in a specific order using techniques like bubble, quick, etc.
   1. Bubble sort: It repeatedly swaps the elements which are in wrong order. basic algorithm required to understand sorting
   2. Selection sort: The smallest element from the inoput is selected and placed in sorted section. It can be used to choose the smallest item from the list
   3. Insertion sort: Sorted array is obtained by inserting elemnts in the correct position. Sorting of numbered cards.
   4. Merge sort: Firstly divides the array into half, sorts and then merges them. Used to sort large files or datasets.
   5. Qucik sort: Uses pivot to partition the data and then sorts recursively. 
   6. Heap sort: Builds a max or min heap and extracts the root to obtain sorted array.
Searching refers to finding an element within a data.
   1.BFSS: It uses queue to manage nodes and goes level by level in a graph. Used to find paths in map.
   2. Boyer-Moore: This uses bad character and good suffix to skip some comparisions and searches for pattern by comparing from right to left. Searching words in a document
   3. Knuth-Morris-Pratt: Uses prefix and suffix table to skip comparision.
   4. Rabin-Karp: Uses hashing to find a pattern in given text.
### 8. Spanning Tree and Shortest Path
These graph algorithms are widely applicable in real life applications like finding the shortest path or in networking world.
   1. Spanning Tree: In this all the vertices are connected with no cycles.
      -Kruskal's algorithm first sorts and keep adding the edges until it forms spanning tree n 
       it doesnt form cycle.
      -Dijkstra's doesnt visit every node but it can find the shortest path
      While other algorithms are used to fins whether there exists a path or shortest path or 
      no like in Floyd's, etc.
   2. Shortest Path: This algorithm is used to find the shortest path between two vertices. For 
      example kruskal's and dijkstra's are used to find the shortest path.
