Q3

**What does it mean to relax all edges from a vertex?**

    trying to lower the cost of getting to a vertiex by using another vertex

**What is the first key point of the algorithm?**

    the closest vertex

**What vertex is selected next?**

    the next closest vertex

**What does relaxation do?**

    it makes sure the cost from going from one vertex to the next is lower than the target value

**What data structures are used in this implementation? What is the purpose for each of the data structures?**

    indexded prioirty quese are used to perform index key operation

 
 

Q4

**Does the fact that it has no directed cycles make it easier to find the shortest path than in a general digraph?**

    Yes

**What condition holds after we are done with the relaxation?**

    Cost between v to w <= target value

**What is re-targeting?**

    resizing images without distortion

**What do the previous application have to do with shortest paths?**

    Each pixel is a vertex and they form directed acyclic graph

**What is the vertex?**

    pixels

**What are the directed edges?**

    edges from one pixel to three downward neighbors

**what weight is assigned to the pixels?**

    energy function of eight neighboring pixels

**What is the seam?**

    shortest path from top to bottom of the image

**How can the longest path be found in acyclic graph?**

    negating all the weights

**What are durations and precedence constraints?**

    Duration refers to the amount of time the job takes. Precedent constraints refers to how job one 
    cannot be started until job zero is done

**What is the parallel job scheduling problem?**

    given a set of jobs with durations and precedence constraints, schedule the jobs


**5 Shortest Paths - Negative Weights**

**What is a negative cycle?**

    a cycle with edges that have a negative weight sum

**How is the Bellman-Ford algorithm used to find a negative cycle?**

    go through all edges and relax each edge

**What are vertices, the edges and the weights in the arbitrage detection application?**

    vertex is currency, Edges are transaction, and weight is the exchange rate
