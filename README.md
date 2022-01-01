# Algorithm_Learning

Collection of implementation of Algorithms in Stanford's Algorithm Specialization Courses

**1. Divide and Conquer, Sorting and Searching, and Randomized Algorithms**
1. Karatsuba Multiplication algorithm <br />
      - Recursive algorithm to calculater long int numbers. <br />
2. Merge Sort algorithm & Count Inversions (IntegerArray.txt is used) <br />
      - Divide and conquer, recursive algorithms. <br />
      - Merge Sort is to recursively sort 1st and 2nd half of the input array, then merge two sorted sublists into one. <br />
      - Count Inversions is to count number of pairs(i,j) of array indices with i<j and A[i] > A[j]. Using Merge Sort  <br />
3. Quick Sort algorithm (QuickSort.txt is used)  <br />
      - To sort an array by choosing a pivot and rearrange the array by putting amount less than pivot to the left of pivot, and others to the right <br />
4. Randomized Contraction algorithm (kargerMinCut.txt is used)  <br />
      - Compute a cut with fewest number of crossing edges in a Graph. (a mininum cut) <br />

**2. Graph Search, Shortest Paths, and Data Structures**
1. Kosaraju’s Two Pass algorithm w Depth First Search algorithm and stack (SCC.txt and test.txt are used)
2. Dijkstra algorithm with heap (dijkstraData.txt is used)
3. Median Maintenance algorithm with heap (median.txt is used)
4. 2-sum algorithm with Hash Tables (2sum.txt is used)


**3. Greedy Algorithms, Minimum Spanning Trees, and Dynamic Programming**
1. Prim's MST (Minimum Spanning Trees) algorithm (edges.txt and jobs.txt are used)
2. Kruskal's MST Algorithm (clustering_big.txt and clustering1.txt are used)
3. Huffman's Codes Algorithm with heap and WIS in path graph Algorithm  (huffman.txt and mwis.txt are used) <br />
      - Huffman's Codes Algorithm using heap: binary prefix-free encoding tree for a given set of characters based on their frequencies/weight. <br />
      - WIS in path graph Algorithm using dynamic programming: to get subset of nonadjacent vertices - an independent set - that gets maximum total weight. <br />
4. Knapsack Algorithm (knapsack_big.txt and knapsack1.txt are used) <br />
      - Knapsack Algorithm using dynamic programming and cache: to calculate maximum sum value within the capacity <br />


**4. Shortest Paths Revisited, NP-Complete Problems and What To Do About Them**
1. Johnson's Algorithm with Bellman-Ford Algorithm and Dijkstra's algorithm (g1.txt, g2.txt and g3.txt are used) <br />
      - To compute the length of a shortest u -> v path for all pairs of vertices u, v in graph; or report that the graph contains a negative cycle. <br />
2. Traveling Salesman Problem Algorithm (tsp.txt is used) <br />
      - To compute the minimum cost of a traveling salesman tour of 25 cities and only visit each city once. Dynamic programming and NP-Complete is used;
            Challenge of this algorithm is that it needs lots of memory. <br />
3. Heuristic TSP Algorithm (nn.txt is used) <br />
      - To **APPROXIMATELY** compute the minimum cost of a traveling salesman tour of cities and only visit each city once. Nearest Neighbor Heuristic TSP Algorithm on sorted large set of data (sorted by x-axis). <br />
      - Challenge of this algorithm is to know how to stop early on searching minimum distance from start city to possible end city. <br />
